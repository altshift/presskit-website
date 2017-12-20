Utilise le projet https://github.com/pixelnest/presskit.html

Site  statique pour les presskits des jeux altshift

# Installation
* Installer https://nodejs.org/en/ version 6
* npm install -g presskit
* Une fois installé cloner le projet depuis https://github.com/altshift/presskit-website.git (avec gitkraken par exemple )
* le site est visible en ouvrant directement l'index.html dans docs

# Travailler sur le projet
* !IMPORTANT! travailler uniquement sur une branche, toutes les modifications poussées sur master irons en prod. tester et ne merge que lorsqu'on est sûr 
* Aller dans le repertoire du projet et faire presskit build --watch -o docs  (pour que chaque modif se voie directement)
* Pour modifier le site modifier uniquement les xml (racine pour l'entreprise et par folder pour les projet) (pour plus d'info voir la doc de https://github.com/pixelnest/presskit.html)
* Aller sur localhost:8080 pour voir le résultat

## Ajouter un produit

* Copier un répetoire produit existant et nettoyer les images et compléter le xml


