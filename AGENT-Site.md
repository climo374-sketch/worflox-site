# Instructions Agent — site public

Deux pages publiques, sans rien d'autre. Elles existent parce que Google exige une page
d'accueil et des règles de confidentialité pour publier une application OAuth en
production (voir [[../brain/connections|brain/connections.md]] § API ou connecteur).

- **En ligne** : <https://climo374-sketch.github.io/worflox-site/> et
  `/confidentialite.html`
- **Dépôt** : `climo374-sketch/worflox-site`, **public** (GitHub Pages l'exige), branche
  `main`, servi depuis la racine. Un `git push` suffit à mettre à jour le site, en une
  minute environ.
- **Déclaré chez Google** : projet `n8n-apps-494714`, page Branding, avec le domaine
  autorisé `github.io`.

## Règles

1. **Tout ce qui est ici est public et indexable.** Aucun nom de prospect, aucun chiffre
   d'affaires, aucune stratégie, aucun lien vers un classeur ou un artifact privé.
2. **Les règles de confidentialité doivent rester vraies.** Si les droits demandés
   changent (`SCOPES` dans `WAT — Lead Qualification Demo/tools/lib/google_auth.py`), si
   l'adresse d'envoi change, ou si un nouveau service traite les données, mettre la page à
   jour **et** sa date de dernière mise à jour. Une politique fausse est pire qu'absente :
   c'est ce que Google et la CNIL regardent.
3. **Pas de logo dans la page Branding de Google** : importer un logo déclenche une
   validation de plusieurs semaines. Le site, lui, peut en porter un.
4. Style : mêmes neutres Apple que Worflox OS (`style.css`), bleu réservé aux liens,
   clair et sombre. Pas de dépendance, pas d'outil de build.
