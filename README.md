# BENART Morocco - Portfolio interactif

Ce dossier contient un site HTML/CSS/JS prêt à être publié sur GitHub Pages.

## Fichiers

- `index.html` : rapport interactif complet.
- `assets/benart-logo.png` et `assets/benart-logo.webp` : logo BENART.
- `assets/benart-drop-raja.webp` : visuel vert fourni.
- `assets/benart-drop-wydad-placeholder.webp` : illustration rouge de remplacement, à remplacer par la photo rouge originale si nécessaire.
- `.nojekyll` : évite les problèmes de publication GitHub Pages.

## Déploiement GitHub Pages

1. Créer un nouveau repository GitHub, par exemple : `benart-portfolio`.
2. Glisser-déposer tous les fichiers de ce dossier dans le repository.
3. Aller dans `Settings` > `Pages`.
4. Dans `Build and deployment`, choisir :
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Cliquer sur `Save`.
6. Attendre 1 à 3 minutes. Le lien du site apparaît dans GitHub Pages.

## Remplacer l'image rouge

La photo rouge affichée dans le message n'était pas disponible comme fichier exploitable dans le dossier sandbox. Pour l’utiliser exactement :

1. Ajouter la photo rouge dans `assets/` avec ce nom : `benart-drop-wydad.webp`.
2. Dans `index.html`, chercher `assets/benart-drop-wydad-placeholder.webp`.
3. Remplacer par `assets/benart-drop-wydad.webp`.

## Conseils

- Pour exporter en PDF : ouvrir le site dans Chrome puis cliquer sur `Exporter PDF` ou faire `Ctrl + P`.
- Pour modifier le contenu : ouvrir `index.html` dans VS Code, les sections sont clairement séparées par `id`.
