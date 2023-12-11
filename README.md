
# ReserveTonLogisDoc

Documentation utilisateur markdown heberger sur github-pages avec mkdocs

## Déploiement local

Pour déployer le serveur en local : 

```bash
  pip install mkdocs
```

Pour build :

```bash
  mkdocs build
```

Et lancer le server sur : http://127.0.0.1:8000/

```bash
  mkdocs serve
```

## Déploiement gh-pages

Pour déployer le serveur sur github pages : 

```bash
  mkdocs gh-deploy
```

## Générer le PDF

Installation de pandoc : https://pandoc.org/installing.html

Installation de MikTex : https://miktex.org/download

Déplacez vous dans le dossier /docs
```bash
  cd docs
```

Commande pour générer les pdf en fonction du fichier md : 
```bash
  pandoc -s votre_fichier.md -o votre_fichier.pdf
```

## Documentation

Lien vers la [documentation de ReserveTonLogis](https://buathiertom.github.io/ReserveTonLogisDoc)


## Auteurs

- [@BuathierTom](https://www.github.com/BuathierTom)
- [@Mayel16](https://www.github.com/Mayel16)
- [@adriengmbt](https://www.github.com/adriengmbt)
- [@crepincorentin](https://www.github.com/crepincorentin)
