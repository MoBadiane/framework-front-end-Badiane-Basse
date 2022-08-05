# framework-front-end-Badiane-Basse

## ESMT

### Présentation du travail
#### Description Partie Frontend
Dans ce projet, nous avons présenté de nombreuses bonnes fonctionnalités de Vue.js V2. Vous trouverez la **gestion d'état** à l'aide de plusieurs modules dans le répertoire. Pour le front-end, il existe un **flux d'authentification** avec une fonction de réinitialisation du mot de passe qui inclut **l'automatisation des e-mails**. Ensuite, nous avons ajouté le **moyen de paiement de Stripe** qui peut traiter différents types de cartes et de devises pris en charge par Stripe. Ensuite, à partir des pages de routage, vous trouverez un code détaillé sur la façon d'empêcher quelqu'un de visiter n'importe quel itinéraire et **afficher une page par défaut pour les demandes non authentifiées ou toute URL erronée ** saisie. Vous trouverez de nombreuses fonctionnalités avec la **mise à jour en temps réel** en ne rechargeant pas la page et bien d'autres. 
#### Backend Description
RESTful Api, la gestion de l'authentification est la partie la plus importante du backend. Ensuite, **le middleware de session, l'authentification JWT, ceux qui ont aidé à obtenir les données de la base de données en toute sécurité. encore une fois, la majeure partie de l'**automatisation des e-mails** s'est produite dans le backend. puis **session de paiement générée**. Ensuite, **séquelisez** orm pour travailler avec différents types de base de données. J'ai travaillé avec la base de données MySQL ici. Ensuite, enregistrez le fichier multimédia  et générez une URL publique. 

----------------------------------------------------------------------
1. Installer les dépendances du serveur node JS
* Entrer dans le dossier server et faire `npm install`
2. Installer les dépendances du frontend vue JS
* Entrer dans le dossier shop et faire `npm install`
Installer une base de donnée mysql et créer une base de donnée nommée `mydb`
Dans le dossier server faire : `npm run seed` pour insérer les données de l’api dans la base de donnée puis  faire `npm start`
 Dans le dossier shop lancez : `npm run serve`


3. Se connecter en tant que administrateur avec l’email admin@gmail.com et le mot de passe 12345678 
*	L’administrateur pourra voir tous les utilisateurs, en supprimer ou même modifier son statut (admin ou client)
*	Il pourra créer, modifier ou supprimer une catégorie d’article
*	Il pourra créer ou supprimer un produit de n’importe quelle catégorie
*	Supprimer l’avis d’un client sur un produit
*	Voir la liste des commandes avec les coordonnées de l’utilisateur, l’adresse de livraison et les informations sur le produit
*	L’admin peut voir son profil et modifier ses informations 

4. Se connecter en tant que administrateur avec l’email metamedzo18@gmail.com  ou liibaasseelaye@gmail.com  et le mot de passe 12345678
*	Il pourra rechercher des produits avec un mot clé 
*	Voir l’avis des autres clients sur un produit
*	Ajouter un avis, une note à un produit
*	Voir informations sur un produit
*	Ajouter produit dans le panier
*	Effectuer un paiement 

`### Nb : Pour la partie de paiement, on a utilisé Stripe dans l’api ; donc il faut créer un compte stripe et sur le champ zip code mettre la clé publique du compte pour effectuer un paiement `

----------------------------------------------------------------------

#### Les outils Frontend
[Vue js](https://vuejs.org/)\
[State management - Vuex](https://vuex.vuejs.org/)\
[Vue routing](https://vuejs.org/v2/guide/routing.html)\
[Component design - Bootstrap Vue](https://bootstrap-vue.org/)\
[Payment gateway - Stripe](https://stripe.com/)
#### Les outils Backend
[Node js](https://nodejs.org/en/)\
[Express js](http://expressjs.com/)\
[RESTful API](https://en.wikipedia.org/wiki/Representational_state_transfer)\
[Authentication - Passport js](http://www.passportjs.org/)\
[Mail automation - Nodemailer](https://nodemailer.com/about/)\
[Database interfacing - Sequelize](https://sequelize.org/)


 ```
 ### Mohameth BADIANE & Mame Libasse Laye BASSE 
 ### MP-ISI1 
 ### Professeur : **Mr KUASSI** Merci pour ce module !!! 
 
 ```
