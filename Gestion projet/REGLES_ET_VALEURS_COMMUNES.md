# Règles

## Règles générales

Dans le cadre du projet *Mes Meilleurs Menus*, l'équipe de développement applique une organisation claire des rôles et une gestion rigoureuse du projet en suivant la méthodologie **Agile**. Chaque membre de l'équipe a des responsabilités définies, et des pratiques de suivi et de gestion des tâches sont mises en place pour assurer la livraison efficace du projet.

#### 1. **Rôles et Responsabilités**
Chaque membre de l'équipe a des responsabilités bien définies pour assurer une gestion claire des tâches et un bon déroulement du projet :
- **Chef de projet (Pamella Hani)** : Responsable de la planification générale, de la coordination entre les équipes, et du suivi des délais.
- **Scrum Master (Lilian Puech)** : Garant de l’application de la méthodologie Agile, facilitateur des réunions Scrum et suivi des sprints.
- **Git Master (Rémi Del-Medico)** : Gère le versionnement du code et la gestion des branches dans le dépôt Git. Administrateur des merges et des pull requests. 
- **Développeurs (Brice Vittet, Laure-Anne Bluteau, Noé Flechon)** : Chargés de l’implémentation des fonctionnalités, des corrections de bugs, et des tests. 
#### 2. **Méthodologie Scrum Agile**
Le projet suit une approche Agile basée sur la méthodologie **Scrum**, permettant une gestion itérative et incrémentale des développements. Les principes clés sont :
- **Sprints** : Chaque sprint dure environ 2 à 4 semaines, avec des livraisons régulières des fonctionnalités prioritaires.
- **Rétrospectives** : À la fin de chaque sprint, l’équipe se réunit pour analyser ce qui a bien fonctionné et les axes d’amélioration.

#### 3. **Suivi des Tickets et Surveillance du Backlog**
Le suivi des tâches est centralisé dans un outil de gestion de projet, via les **issues** de GitHub, avec un suivi précis des tickets :
- **Backlog produit** : Maintenu et priorisé par le Product Owner et l’équipe, il contient toutes les fonctionnalités à implémenter ainsi que les améliorations proposées.
- **Tickets** : Chaque fonctionnalité ou bug est suivi sous forme de tickets, avec des statuts tels que "à faire", "en cours", et "terminé".
- **Monitoring continu** : Le backlog est constamment mis à jour pour refléter l’état d’avancement du projet, et les tickets sont redistribués au fur et à mesure de la progression. 

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
