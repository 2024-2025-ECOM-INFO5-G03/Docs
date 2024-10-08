# Règles

## Règles générale
**TODO: Pamella**

## Règles d'utilisation de git

### Règles de base 

- Il est interdit de travailler directement sur la branche main
- Les commentaires de commit doivent être écrits en français et être le plus explicite du travail réalisé possible.

### Gestion des branches

- La convention de nommage d'une branche est la suivante : **prenom.nomDeFonctionImplementer**.
- Chaque branche est créée pour une unique fonctionnalité.
- Toutes les branches sont créées à partir de la branche dev.

Voilà un exemple d'arbre git obtenu en suivant les règles ci-dessus :
![alt text](https://github.com/2024-2025-ECOM-INFO5-G03/Docs/blob/main/Gestion%20projet/arbre_git.png?raw=true)

### Merge request

Une fois la fonctionnalité de votre branche actuelle implémentée, il faut demander une merge request afin de merge votre branche dans la branche dev.
Pour créer la merge request, aller sur github dans le répertoire où se situe votre branche, cliquez sur l'onglet Pull requests. À partir de cet onglet, cliquer sur "New pull request" et sélectionner :
dev <- votre branche puis "create pull request".

### Merge dans main

Une fois que la branche dev a atteint un certain niveau de développement, avec l'accord de tous les membres du groupe il est possible de prendre la décision de merge dev dans main afin de "mettre en production" une nouvelle version fonctionnelle de notre projet.
