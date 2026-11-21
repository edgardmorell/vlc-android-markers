# Compilation cloud du prototype VLC Marker (GitHub Actions)

Ce dépôt contient un prototype non validé. Le workflow GitHub Actions tente de construire un APK Debug sur un runner Linux.

## Démarrage rapide
1. Créer un dépôt **public** sur GitHub.
2. Importer/téléverser le contenu de ce dossier dans le dépôt (la racine du dépôt doit contenir `settings.gradle`, `build.gradle`, `application/`, etc.).
3. Dans GitHub, ouvrir l'onglet **Actions** et autoriser les workflows si GitHub le demande.
4. Le workflow se lance à chaque push sur `main`/`master`. Pour le lancer manuellement : Actions → **Build VLC Marker Debug APK** → Run workflow.
5. Quand le run est terminé avec succès, ouvrir le run et télécharger l'artifact **VLC-Marker-debug-apk**.

## Important
- Le prototype n'a pas été compilé ni testé sur appareil. Le workflow est une tentative de compilation, pas une garantie.
- Cet APK Debug n'est pas une version officielle VLC et n'est pas signé pour distribution Play Store.
- Le dépôt public rend le code source accessible à tous. Ne pas y mettre de données personnelles, secrets, clés ou fichiers privés.
- La compilation peut échouer si les dépendances ou les scripts VLC ont évolué ou si le prototype contient une erreur.
