
## Document de Synthèse : Choix Technologiques de *Mes Meilleurs Menus*

### 1. Technologie Backend : JHipster

JHipster est basé sur **Spring Boot** pour le backend et supporte plusieurs technologies pour le front-end et la base de données.

#### Avantages de JHipster :
- **Productivité élevée** : JHipster permet de générer automatiquement une architecture d'application complète, incluant le front-end, le back-end, et la base de données.
- **Support pour les microservices** : Offre une architecture modulaire qui permet la gestion de microservices, facilitant ainsi la scalabilité.
- **Intégration CI/CD** : JHipster propose des pipelines d'intégration continue pour déployer l'application rapidement sur différents environnements.

### 2. Technologie Frontend : React

**React** a été choisi comme technologie de développement pour l'interface utilisateur. 
**Raison pour ce choix**: l'équipe de développement a plus d'expertise dans React que dans les autres technologies front proposés par JHipster (Vue, Angular, ...).
React est une bibliothèque JavaScript moderne et permet de construire des interfaces utilisateur dynamiques et réactives.

#### Avantages de React :
- **Modularité** : React encourage le développement en composants réutilisables, facilitant la maintenance et l'évolution du projet.
- **Performance** : Grâce à son "Virtual DOM", React optimise les mises à jour de l'interface, ce qui améliore la réactivité et la fluidité.
- **Écosystème riche** : React bénéficie d'un large écosystème d'outils et de bibliothèques pour faciliter le développement (comme Redux pour la gestion d'état, ou React Router pour la navigation).

### 3. Base de données : PostgreSQL

Pour la gestion des données, **PostgreSQL** a été retenu comme base de données relationnelle. PostgreSQL est une solution open-source, robuste et scalable.

#### Avantages de PostgreSQL :
- **Fiabilité** : PostgreSQL garantit l'intégrité des données grâce à ses fonctionnalités avancées comme la gestion des transactions ACID (Atomicity, Consistency, Isolation, Durability).
- **Extensions** : Le support d'extensions permet d'ajouter des fonctionnalités supplémentaires comme la gestion des données géospatiales.
- **Scalabilité** : PostgreSQL gère efficacement des volumes massifs de données et peut s'adapter à la montée en charge.

### 4. Conteneurisation : Docker

L'application *Mes Meilleurs Menus* est déployée et exécutée à l'aide de **Docker**. Docker permet de conteneuriser l'application et ses dépendances, ce qui garantit une portabilité et une consistance entre les différents environnements (développement, test, production).

#### Avantages de Docker :
- **Isolation des environnements** : Chaque service (application, base de données) fonctionne dans son propre conteneur, réduisant ainsi les conflits de dépendances.
- **Déploiement simplifié** : Docker simplifie la gestion des déploiements en permettant de créer des images reproductibles de l'application.

### 5. Hébergement sur Azure VM

Le choix de l’hébergement s’est porté sur une **machine virtuelle (VM) Azure**. Azure offre un environnement cloud sécurisé et fiable, capable de supporter les besoins d’une application web à fort trafic.

#### Avantages d’Azure VM :
- **Flexibilité** : Les VM Azure permettent de choisir la configuration adaptée en termes de CPU, mémoire, et stockage, selon les besoins de l’application.
- **Sécurité** : Azure propose des fonctionnalités avancées de sécurité comme la gestion des identités, la protection des données et la surveillance des menaces.
