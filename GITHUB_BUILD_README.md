# MalagAI — GitHub APK Builder

Ce projet contient MalagAI dans une application Android et un workflow GitHub Actions
qui compile automatiquement un APK debug dans le cloud.

## Depuis un téléphone

1. Crée un dépôt GitHub vide.
2. Envoie tout le contenu de ce projet dans le dépôt (y compris `.github/workflows/build-apk.yml`).
3. Ouvre l'onglet **Actions**.
4. Lance **Build MalagAI APK** avec **Run workflow**.
5. Quand le build est terminé, ouvre l'exécution réussie.
6. Dans **Artifacts**, télécharge **MalagAI-debug-APK**.
7. Décompresse l'artefact et installe l'APK sur Android.

Aucun Android Studio n'est nécessaire sur le téléphone : la compilation se fait sur
les machines GitHub Actions.

## Important

Il s'agit d'un APK debug destiné au test et à l'installation personnelle.
