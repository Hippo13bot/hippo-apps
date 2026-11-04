# HIPPO APPS — guide de publication

## 1. Publier le site
1. Décompresse `HIPPO-APPS-GANDALF-MAC-SITE.zip`.
2. Envoie tous les fichiers et dossiers qu’il contient à la racine du dépôt `Hippo13bot/hippo-apps` (ne dépose pas le ZIP lui-même).
3. Dans GitHub : Settings → Pages → Build and deployment → Source : **GitHub Actions**.
4. Le site sera publié sur https://hippo13bot.github.io/hippo-apps/ après le déploiement.

## 2. Publier le téléchargement Gandalf OSINT
1. Dans le dépôt GitHub, ouvre **Releases** puis **Create a new release**.
2. Crée le tag exact `gandalf-v1.0.0`.
3. Ajoute le fichier `GandalfOSINT-mac-apple-silicon.zip` fourni séparément comme fichier joint à la release.
4. Publie la release. Le bouton Gandalf OSINT pointera alors vers ce fichier.

## Compatibilité
- Wikhippo : Mac Intel, Mac Apple Silicon et Windows.
- Gandalf OSINT : Mac Apple Silicon ARM64 uniquement. Aucun binaire Mac Intel ou Windows n’a été fourni.

Le fichier Gandalf OSINT fait environ 80 Mo. Le publier comme fichier joint d’une GitHub Release évite d’alourdir le dépôt et contourne la limite d’envoi de fichiers de l’interface web du dépôt.
