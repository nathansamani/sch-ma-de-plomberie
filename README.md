# schéma de plomberie

Logiciel sans installation de réalisation simple d'installations.

## Démarrage

Servez le dossier via un petit serveur HTTP puis ouvrez la page dans votre navigateur :

```bash
python -m http.server 8000
# ensuite : http://localhost:8000/Designer.html
```

Un lancement direct du fichier (`file://`) empêche le chargement de la bibliothèque de composants.

## Bibliothèque de composants

Ajoutez vos images de composants (SVG, JPG, WebP) dans le dossier `bibliotheque/` à la racine du projet. Les sous‑dossiers deviennent des catégories dans l'interface. Un fichier optionnel `bibliotheque/_index.json` peut lister les fichiers pour accélérer le chargement.

Des exemples sont fournis dans `bibliotheque/Exemples`.

La barre d'outils permet de choisir l'outil, le matériau, le diamètre et la couleur des tuyaux.