# SQUAT 220 — GitHub Pages

Application mobile statique de suivi et d'ajustement de l'entraînement squat.

## Mise en ligne
1. Sur GitHub, créez un nouveau dépôt public `squat220`.
2. Décompressez cette archive et envoyez **tous les fichiers à la racine** du dépôt via **Add file → Upload files**. Ne téléversez pas le .zip tel quel.
3. Allez dans **Settings → Pages → Build and deployment**.
4. Choisissez **Source : Deploy from a branch**, **Branch : main**, **Folder : /(root)** puis **Save**.
5. L'adresse sera `https://VOTRE-PSEUDO.github.io/squat220/`.

Sur Android, ouvrez l'URL HTTPS dans Chrome, puis **Installer l'application** ou **Ajouter à l'écran d'accueil**.

### Données importantes
Les séances et RPE sont stockés dans le navigateur du téléphone, via localStorage. Ils ne sont pas envoyés sur GitHub et **ne se synchronisent pas entre appareils**. Exportez régulièrement un fichier JSON de sauvegarde depuis l'application ; importez-le si vous changez de téléphone, de navigateur ou d'adresse du site.

L'ajustement des charges repose sur des règles locales programmées, pas sur une conversation ChatGPT automatisée.
