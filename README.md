# ORM_API_e-liquide
Thomas Dumont

B2A

## Objectifs

Faire une API rest en utilisant expressJS et l'ORM Sequelize.

## Fonctionnalités & technologies

* Authentification :
  * Requête post pour créer un compte
  * Requête post pour se connecter avec la génération d'un token
* Compte :
  * Requête get pour récuperer les informations du compte de la personne connecté
  * Requête put afin que la personne connecté puisse modifier ses informations de compte
* Sequelize :
  * Utilisation de sequelize pour construire les tables de la base données
* Express :
  * Utilisation d'express pour créer le serveur HTTP
* NodeJs :
  * Utilisation de NodeJs pour son gestionnaire de modules

## Comment faire fonctionner le projet ?

* Se placer avec un terminal dans API_eliquide après l'avoir téléchargé
* Pour configurer la BDD, créer une bdd `database_development_eliquide, database_test_eliquide` et `database_production_eliquide` faire `sequelize db:create` et `sequelize db:migrate`
* Faire `npm install`
* Faire `nodemon server.js`