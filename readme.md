# Comment optimiser les images

## Comment exécuter ?

1) Créer une nouvelle branche
```bash
git checkout -b test
```

2) Ajouter des images, renommer celles existantes ou déplacez les.

3) Ajouter les images sur git
```bash
git add .
git commit -m "Update images"
git push
```

4) Retourner dans l'interface de Github et créer une Pull Request entre votre branche "test" et celle de "main"

5) Observez le résultat en commentaire de la pull request

6) Le workflow ayant produit un commit (s'il y a eut des images à optimiser), vous devez donc récupérer les modifications en local
```bash
git pull
```

## Formation sur GitHub Actions

Ce projet fait partit d'une formation sur l'utilisation de GitHub Actions et découvrir comment automatiser vos intégrations continues sur Udemy : [Automatiser tout sur vos projets avec Github Actions](https://www.udemy.com/course/automatiser-tout-sur-vos-projets-avec-github-actions/?referralCode=268A353A1CAE10611EBD).

N'hésitez pas à explorer les fonctionnalités de Chromatic et de Storybook pour améliorer la qualité et la robustesse de vos composants d'interface utilisateur. Happy coding! 🚀