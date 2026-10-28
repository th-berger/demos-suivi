# Démos interactives Suivi

Démos interactives cliquables réalisées à partir de captures de Suivi, publiées avec GitHub Pages.

- Catalogue : https://th-berger.github.io/demos-suivi/
- Une démo : https://th-berger.github.io/demos-suivi/<nom-de-la-demo>/ (ajouter `#id-etape` pour ouvrir une étape précise)

## Mise en ligne (une seule fois)

1. Créer un dépôt sur GitHub (par exemple `demos-suivi`). GitHub Pages est disponible pour les dépôts publics
   avec un compte gratuit, et pour les dépôts privés avec les offres payantes. Le site publié est
   en général accessible publiquement, même quand le dépôt est privé.
2. Envoyer le contenu de ce dossier sur la branche `main` (glisser-déposer dans « Add file > Upload files »,
   GitHub Desktop, ou `git push`).
3. Settings > Pages > Build and deployment :
   Source = « Deploy from a branch », branche `main`, dossier `/ (root)`.
4. Attendre une à deux minutes, puis ouvrir https://th-berger.github.io/demos-suivi/

## Ajouter ou modifier une démo

Faire préparer la nouvelle démo par Claude à partir de ce dépôt (il conserve les démos existantes),
puis envoyer les fichiers modifiés. Les captures d'origine ne sont jamais publiées : seules les images
traitées (masques appliqués) figurent dans les pages.

## Intégrer une démo

Le catalogue propose un bouton « Copier le code iframe » pour chaque démo. Le code fonctionne dans le
widget Iframe d'un portail Suivi, dans un élément Code Embed de Webflow, ou dans un message Discourse
(après ajout du domaine `th-berger.github.io` au réglage « allowed iframes » du forum).
