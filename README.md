# img_hosting

Ce dépôt sert à héberger des images et fournir une galerie statique simple.

Usage :
- Dépose tes images dans le dossier `images/`.
- Mets à jour `images.json` avec les noms de fichiers (relatifs à `images/`) ou utilise un petit script pour le générer automatiquement.

Options :
- Pour des fichiers volumineux, active Git LFS et ajoute des patterns dans `.gitattributes` (exemples fournis).
- Tu peux activer GitHub Pages dans les Settings et servir la galerie depuis la branche `main` (root) ou `gh-pages`.

Fichiers inclus :
- `index.html` — galerie responsive qui charge `images.json`.
- `images.json` — liste d’images (initialement vide).
- `images/.gitkeep` — placeholder pour tracker le dossier.
- `.gitattributes` — exemple pour Git LFS (commenté).
- `.gitignore` — ignores de base.
