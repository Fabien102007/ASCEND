# ASCEND PWA

Application web installable (PWA) pour bilans quotidiens et hebdomadaires.

## Déploiement GitHub Pages
1. Créer un dépôt GitHub séparé, par exemple `ascend`.
2. Envoyer tout le contenu de ce dossier à la racine du dépôt.
3. Dans GitHub : Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Attendre la publication, puis ouvrir `https://TON-PSEUDO.github.io/ascend/` dans Chrome Android.
5. Menu ⋮ → Installer l'application / Ajouter à l'écran d'accueil.

## Données
Les bilans sont enregistrés dans le stockage local du navigateur (`localStorage`). Ils ne sont pas synchronisés entre appareils. Utiliser l'export JSON dans l'onglet Progression pour faire des sauvegardes.

## Fichiers
- `index.html` : interface et structure
- `app.js` : logique des bilans et stockage
- `manifest.webmanifest` : identité PWA
- `sw.js` : cache hors-ligne
- `icons/` : icônes d'application
