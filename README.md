# Luna Barbu — portfolio

Site portfolio statique en HTML / CSS / JavaScript, conçu pour être publié sur GitHub Pages.

## Structure

- `index.html` — page d'accueil
- `projet.html` — gabarit des fiches projets
- `assets/css/styles.css` — design
- `assets/js/main.js` — données des projets, filtres et navigation
- `assets/img/` — images issues du portfolio PDF
- `.github/workflows/deploy.yml` — déploiement automatique GitHub Pages

## Mise en ligne sur GitHub

1. Créer un dépôt GitHub dédié, par exemple `luna-barbu-portfolio`.
2. Déposer tous les fichiers de ce dossier à la racine du dépôt.
3. Aller dans **Settings → Pages** puis choisir **GitHub Actions** comme source.
4. Pousser la branche `main`. Le workflow publiera automatiquement le site.

Avec un dépôt projet, l'adresse prendra normalement la forme :
`https://TON-USERNAME.github.io/TON-REPOSITORY/`

## Ajouter de nouvelles images

Ajouter les fichiers dans `assets/img/`, puis modifier la liste `projects` dans `assets/js/main.js`.

## À faire avant publication

- remplacer les images d'exemple par les exports haute définition finaux si nécessaire ;
- ajouter le lien LinkedIn ;
- vérifier le titre SEO et la description ;
- définir un domaine personnalisé lorsque le nom de domaine sera choisi.
