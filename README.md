```markdown
# Site de Vente de Meubles

Ce projet est un site web de vente de meubles. Il comprend un backend et un frontend, ainsi qu'une base de données MySQL pour stocker les produits et les informations des utilisateurs.

## Lancer le Projet

### Récupérer la Dernière Version du Projet

Pour obtenir la dernière version du projet depuis la branche de développement (dev), suivez ces étapes dans Visual Studio Code :

```bash
git checkout dev
git pull origin dev
```

### Installation des Modules

Pour installer les dépendances nécessaires, exécutez la commande suivante à la racine du projet :

```bash
npm install
```

Répétez également cette étape dans les dossiers `/back` et `/front` du projet.

### Configuration de la Base de Données

Pour obtenir la base de données nécessaire, suivez ces étapes :

1. Récupérez le fichier `database.sql` du dossier `/back/sql`. Ce fichier sera utilisé pour créer la base de données via phpMyAdmin.
2. Importez le fichier `database.sql` dans phpMyAdmin pour créer la base de données "vente_meubles" avec au moins les tables "testmeubles" et "test_users".

### Configuration Backend

Si le fichier `.env` n'existe pas déjà à la racine du projet, créez-le. Remplissez ce fichier avec les paramètres de connexion à la base de données, le mot de passe et le port.

```bash
PASSWORD='root'
PORT_BDD=3306
PORT=3000
HOST='http://localhost'
```

Le mot de passe peut varier en fonction de votre configuration phpMyAdmin. Le port de la base de données est différent entre les systèmes Mac (8889) et Windows (3306).

### Configuration Frontend

Si le fichier `.env` n'existe pas déjà à la racine du dossier `/front`, créez-le. Assurez-vous que les informations suivantes sont correctes :

```bash
VITE_PORT=3000
VITE_HOST='http://localhost'
```

### Démarrage des Serveurs et de l'Application

Pour exécuter le projet, suivez ces étapes :

1. Lancez le serveur MySQL qui héberge votre base de données (par exemple, via MAMP).
2. Ouvrez un premier terminal, allez dans le dossier `/back` et lancez le serveur avec la commande :

```bash
nodemon
```

Vous devriez voir les messages suivants dans la console :

```bash
[nodemon] 2.0.22
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node serveur.js`
Listening on port 3000
Connecté à la base de données MySQL
```

3. Ouvrez un deuxième terminal, allez dans le dossier `/front` et lancez l'application avec la commande :

```bash
npm run dev
```

Vous devriez voir les messages suivants dans la console, indiquant que l'application est prête à être utilisée :

```bash
> front@0.0.0 dev
> vite

  VITE v4.3.9  ready in 1158 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```

Vous pouvez appuyer sur la touche "o" ou cliquer sur le lien (par exemple : http://localhost:5173/) pour ouvrir le site.

## Fonctionnalités

Le projet comprend actuellement les fonctionnalités suivantes :

- **Enregistrement des utilisateurs** : Les utilisateurs peuvent créer un compte et se connecter.
 (https://imgur.com/y6JU2cr)(https://imgur.com/zBMGkU2)
- **Ajout de produits au panier** : Les utilisateurs peuvent ajouter des produits à leur panier d'achat.
 [Nom de la Vidéo 1](lien_vers_la_video_1)
- **Gestion des produits** : Les administrateurs peuvent ajouter, modifier et supprimer des produits depuis la page d'administration.
 [Nom de la Vidéo 1](lien_vers_la_video_1)

Nous prévoyons d'ajouter d'autres fonctionnalités dans les futures versions.

## Contribuer

Nous accueillons les contributions de la communauté ! Si vous souhaitez contribuer au projet, suivez ces étapes :

1. Fork le projet.
2. Créez une branche pour votre contribution.
3. Implémentez et testez votre contribution.
4. Soumettez une demande de tirage (pull request) pour que nous puissions examiner votre contribution.
