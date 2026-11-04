# HIPPO APPS — guide de publication

Catalogue statique gratuit des applications de @hippo.reporter.

## Publier sur GitHub Pages
1. Envoyez tous les fichiers et dossiers du projet dans le dépôt `hippo-apps`.
2. Ouvrez **Settings → Pages** et choisissez **GitHub Actions** dans Build and deployment.
3. Le workflow `.github/workflows/pages.yml` publie le site après chaque push sur `main`. Il utilise des versions récentes des actions GitHub et ne coupe pas automatiquement un déploiement en cours.
4. Site : `https://hippo13bot.github.io/hippo-apps/` (si le dépôt et le compte gardent ces noms).

## Wikhippo — liens directs configurés
- Mac Intel : téléchargement direct du DMG Intel.
- Mac ARM64 : téléchargement direct du DMG Apple Silicon.
- Windows : téléchargement direct de l’installateur EXE.
- Logo : `assets/wikhippo-icon.png`.
- Guide : `installation.html`.

Les liens pointent vers les fichiers de la Release GitHub, mais les boutons lancent directement le téléchargement du fichier, sans ouvrir la page des Releases.

## Modifier le catalogue
Éditez `apps.js`. Chaque application peut avoir `macIntel`, `macArm64` et `windows` pour afficher des téléchargements séparés.

## Personnaliser
- `index.html` : page d’accueil.
- `installation.html` : aide à l’installation et connexions facultatives.
- `styles.css` : design et responsive.
- `apps.js` : catalogue et liens.
- `script.js` : recherche, filtres et fenêtre de téléchargement.

Les liens « Contact » renvoient actuellement vers le guide d’installation. Vous pourrez les remplacer par votre adresse e-mail lorsque vous souhaiterez en afficher une.
