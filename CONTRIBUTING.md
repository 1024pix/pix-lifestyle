# Contribuer sur Pix-Lifestyle

## Modification d'une page existante

Pour modifier un fichier existant : 
- Créer une branche depuis `main`
- Faire les modifications sur le fichier
- Ouvrir une _Pull Request_ sur Github

## Ajout d'une nouvelle catégorie/nouvelle page
Pour modifier une page existante :
- Créer une branche depuis `main`
- Faire les ajouts/modifications souhaités
- Ajouter des liens si besoin sur les `README.md` (celui à la racine ou ceux des sous-dossiers)
- Modifier le fichier `_sidebar.md` pour ajouter un lien si besoin
- Ouvrir une _Pull Request_ sur Github


## Tester en local

Pix-Lifestyle est lisible sur le Github, mais aussi via le site  https://1024pix.github.io/pix-lifestyle/.
Ce site est généré grâce à [Docsify](https://docsify.js.org/).

Pour lancer le site en local :
- Installer Docsify : `npm i docsify-cli -g`
- Lancer le site : `docsify serve`