# PaymWallet
PaymWallet, est un wallet életronique qui permet de recevoir et de transférer de l'argent. Vous devez mettre en place ce service en consommant une api RESTFUL.

## Langage
Les langages qui doivent être utilisés sont, PHP, TypeScript ou Java, en ce qui concerne le framework, vous avez libre choix.

## Architecture
Clean code ou Hexagonal architecture

## Base de données
PostgreSQL

## Exigences de l'application
* Les utilisateurs doivent pouvoir se connecter à l'application en utilisant leur adresse e-mail et leur mot de passe. S'il s'agit d'un nouvel utilisateur, il doit pouvoir s'inscrire en fournissant les informations nécessaires telles que le nom, l'adresse e-mail et le mot de passe.
* L'utilisateur doit pouvoir se déconnecter.
* L'utilisateur doit pouvoir recharger son wallet à partir de son numéro mobile money en renseignant les informations suivantes : opérateur, numéro de téléphone, montant.
* L'utilisateur doit pouvoir transférer de l'argent de son wallet vers son mobile money en renseignant les informations suivantes : opérateur, numéro de téléphone, montant.
* L'utilisateur doit pouvoir visualiser l'historique des transactions effectuées sur son wallet.

## Exigences techniques
* L'application doit être développée en utilisant l'architecture Hexagonal.
* L'application doit être développée en utilisant soit Node.js, PHP ou Java.
* L'application doit utiliser une base de données relationnelle pour stocker les données des utilisateurs.
* L'application doit être testée unitairement et intégrée à l'aide d'une bibliothèque de tests.
* L'application doit être livrée avec un script d'installation et une documentation technique complète.
* L'API doit etre documentée avec Swagger
* L'application devra consommer cette API pour les services de paiement et de retrait [Paymetrust API](https://documenter.getpostman.com/view/16390052/Tzedg4ca#564ae987-056e-4f62-9e1c-27515ce081f8)

## Tâches
* Créer un diagramme d'architecture Hexagonal pour l'application.
* Créer une base de données relationnelle pour stocker les données des utilisateurs.
* Écrire le code pour les fonctionnalités de connexion, d'inscription et de déconnexion des utilisateurs.
* Écrire le code pour la fonctionnalité de rechargement.
* Écrire le code pour la fonctionnalité de transfert.
* Écrire des tests unitaires et intégrés pour toutes les fonctionnalités.
* Écrire un script d'installation pour l'application et fournir une documentation technique complète.

## Bon à savoir
Nous évaluerons votre code en fonction des critères suivants:

* Respect de l'architecture Hexagonal.
* Qualité du code et respect des meilleures pratiques de développement.
* Qualité et pertinence des tests unitaires et intégrés.
* Qualité de la documentation technique.
* Respect des exigences fonctionnelles et techniques.
* Capacité à livrer un code fonctionnel et bien testé dans les délais impartis.


---

# PaymWallet
PaymWallet is an electronic wallet that allows you to receive and transfer money. You need to implement this service by using a RESTFUL api.

## Language
The languages that must be used are, PHP, TypeScript or Java, regarding the framework, you have free choice.

## Architecture
Clean code or Hexagonal architecture

## Database
PostgreSQL

## Application requirements
* Users must be able to login to the application using their email address and password. If it is a new user, they must be able to register by providing the necessary information such as name, email address and password.
* The user must be able to log out.
* The user must be able to recharge his wallet from his mobile money number by providing the following information: operator, phone number, amount.
* The user must be able to transfer money from his wallet to his mobile money by providing the following information: operator, phone number, amount.
* The user must be able to view the history of transactions made on his wallet.

## Technical requirements
* The application must be developed using the Hexagonal architecture.
* The application must be developed using either Node.js, PHP or Java.
* The application must use a relational database to store user data.
* The application must be unit tested and integrated using a test library.
* The application must be delivered with an installation script and complete technical documentation.
* The API must be documented with Swagger
* The application must consume this API for payment and withdrawal services [Paymetrust API](https://documenter.getpostman.com/view/16390052/Tzedg4ca#564ae987-056e-4f62-9e1c-27515ce081f8)

## Tasks
* Create a Hexagonal architecture diagram for the application.
* Create a relational database to store user data.
* Write code for user login, registration and logout functionality.
* Write code for the reload functionality.
* Write code for the transfer functionality.
* Write unit and built-in tests for all features.
* Write an installation script for the application and provide complete technical documentation.

## Good to know
We will evaluate your code according to the following criteria:

* Compliance with the Hexagonal architecture.
* Quality of the code and respect of the best development practices.
* Quality and relevance of unit and integrated tests.
* Quality of the technical documentation.
* Compliance with functional and technical requirements.
* Ability to deliver a functional and well-tested code within the given deadlines.
