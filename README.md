# Portfolio informatique — Lina Rizki

Site statique HTML/CSS/JavaScript, prêt pour GitHub Pages. Les textes et captures de projets sont adaptés du portfolio Canva transmis en PDF.

## Ouvrir et modifier sur Mac
1. Ouvrir ce dossier dans Visual Studio Code.
2. Double-cliquer sur `index.html` pour l'ouvrir dans un navigateur.
3. Modifier les textes et liens dans `index.html`, le design dans `style.css`.
4. Enregistrer (`Cmd + S`), puis rafraîchir le navigateur (`Cmd + R`).

## Ajouter les liens de projets
Les cinq cartes affichent volontairement « Lien du projet à ajouter » : aucun lien de dépôt, vidéo ou démonstration n'a été fourni. Pour chaque projet, remplacer par exemple :

`<span class="pending">Lien du projet à ajouter</span>`

par :

`<a class="project-link" href="https://github.com/TON-PSEUDO/NOM-DU-PROJET" target="_blank" rel="noopener noreferrer">Voir le projet ↗</a>`

Ajouter éventuellement dans `style.css` : `.project-link{color:var(--accent);font-weight:700}`.

## Publier les changements sur le dépôt EXISTANT
**Ne crée pas un deuxième dépôt.** Si ton site est déjà en ligne, copie les nouveaux fichiers (`index.html`, `style.css`, `script.js`, `images/`) dans ton dossier local GitHub existant, en remplaçant les anciens. Dans GitHub Desktop, vérifie les changements, saisis un résumé, clique sur **Commit to main**, puis **Push origin**. GitHub Pages mettra le site à jour après déploiement.

## Confidentialité
L'adresse e-mail et le numéro de téléphone sont repris de ton PDF et seront visibles publiquement. Tu peux supprimer le téléphone dans `index.html` avant publication si tu préfères.

## Fichiers
- `index.html` : contenu et structure
- `style.css` : design responsive
- `script.js` : année du pied de page
- `images/` : captures recadrées depuis ton PDF Canva
