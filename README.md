<div align="center">
  <h1 align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
    <br>Projet Collectif - Vente de Meubles Vintage
  </h1>
  <h3>◦ Erreur HTTPStatus : 429</h3>
  <h3>◦ Développé avec les logiciels et outils ci-dessous.</h3>

  <p align="center">
    <img src="https://img.shields.io/badge/SVG-FFB13B.svg?style&logo=SVG&logoColor=black" alt="SVG" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style&logo=JavaScript&logoColor=black" alt "JavaScript" />
    <img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style&logo=PostCSS&logoColor=white" alt="PostCSS" />
    <img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style&logo=Autoprefixer&logoColor=white" alt="Autoprefixer" />
    <img src="https://img.shields.io/badge/Jest-C21325.svg?style&logo=Jest&logoColor=white" alt="Jest" />
    <img src="https://img.shields.io/badge/Bootstrap-7952B3.svg?style&logo=Bootstrap&logoColor=white" alt="Bootstrap" />
    <img src="https://img.shields.io/badge/Nodemon-76D04B.svg?style&logo=Nodemon&logoColor=white" alt="Nodemon" />
    <img src="https://img.shields.io/badge/Vite-646CFF.svg?style&logo=Vite&logoColor=white" alt="Vite" />

    <img src="https://img.shields.io/badge/Swiper-6332F6.svg?style&logo=Swiper&logoColor=white" alt="Swiper" />
    <img src="https://img.shields.io/badge/React-61DAFB.svg?style&logo=React&logoColor=black" alt="React" />
    <img src="https://img.shields.io/badge/Axios-5A29E4.svg?style&logo=Axios&logoColor=white" alt="Axios" />
    <img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style&logo=ESLint&logoColor=white" alt="ESLint" />
    <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style&logo=MySQL&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Express-000000.svg?style&logo=Express&logoColor=white" alt="Express" />
    <img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
    <img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
  </p>
  <img src="https://img.shields.io/github/license/DjihaneB/projet-collectif---vente-de-meubles-vintage_project?style&color=5D6D7E" alt="Licence GitHub" />
  <img src="https://img.shields.io/github/last-commit/DjihaneB/projet-collectif---vente-de-meubles-vintage_project?style&color=5D6D7E" alt="Dernier commit Git" />
  <img src="https://img.shields.io/github/commit-activity/m/DjihaneB/projet-collectif---vente-de-meubles-vintage_project?style&color=5D6D7E" alt="Activité des commits GitHub" />
  <img src="https://img.shields.io/github/languages/top/DjihaneB/projet-collectif---vente-de-meubles-vintage_project?style&color=5D6D7E" alt "Langage le plus utilisé sur GitHub" />
</div>

---

## 📖 Table des matières
- [📦 Fonctionnalités](#-fonctionnalités)
- [📂 Structure du Répertoire](#-structure-du-répertoire)
- [⚙️ Modules](#modules)
- [🔧 Installation](#-installation)
- [📝 Réalisation](#-réalisation)
- [🤝 Contribution](#-contribution)


---

## 📦 Fonctionnalités

> - [X] Enregistrement des utilisateurs : Les utilisateurs peuvent créer un compte et se connecter.
> - [X] Ajout de produits au panier : Les utilisateurs peuvent ajouter des produits à leur panier d'achat.
> - [X] Gestion des produits : Les administrateurs peuvent ajouter, modifier et supprimer des produits depuis la page d'administration.
> - [X] Profil utilisateur : Les utilisateurs peuvent consulter et mettre à jour leur profil.
 
> - [ ] Nous prévoyons d'ajouter les fonctionnalités suivantes dans les futures versions :
> - [ ] Paiement en ligne : Intégration d'un système de paiement en ligne pour finaliser les achats.
> - [ ] Filtrage des produits : Ajout de fonctionnalités de filtrage pour faciliter la recherche de produits.
---
(https://imgur.com/y6JU2cr)
(https://imgur.com/zBMGkU2)
## 📂 Structure du Répertoire

```sh
└── projet-collectif---vente-de-meubles-vintage_project/
    ├── .gitignore
    ├── README.md
    ├── back/
    │   ├── Assets/
    │   ├── app.js
    │   ├── client/
    │   ├── controllers/
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── routes/
    │   ├── serveur.js
    │   └── sql/
    ├── front/
    │   ├── .eslintrc.cjs
    │   ├── .gitignore
    │   ├── index.html
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── postcss.config.js
    │   ├── public/
    │   ├── src/
    │   ├── tailwind.config.js
    ├── package-lock.json
    └── package.json

⚙️ Modules
<details closed><summary>Front</summary>
Fichier	Résumé
.gitignore	Ignorer les fichiers
package.json	Informations du projet
tailwind.config.js	Configuration Tailwind CSS
.eslintrc.cjs	Configuration ESLint
index.html	Page d'accueil HTML
vite.config.js	Configuration Vite
postcss.config.js	Configuration PostCSS
</details>


📦 Installer les Modules Nécessaires

Assurez-vous d'installer les bibliothèques requises en exécutant la commande suivante à la racine du projet :

bash
Copy code
npm install
Répétez également cette étape dans les dossiers /back et /front du projet.

💾 Télécharger la Base de Données

Pour obtenir la base de données nécessaire, suivez ces étapes :

Récupérez le fichier database.sql du dossier /back/sql. Ce fichier sera utilisé pour créer la base de données via phpMyAdmin.

Importez le fichier database.sql dans phpMyAdmin pour créer la base de données "vente_meubles" avec au moins les tables "testmeubles" et "test_users".

🔧 Vérifier la Configuration Backend

Au cas où le fichier .env n'existe pas déjà à la racine du projet, créez-le. Remplissez ce fichier avec les paramètres de connexion à la base de données, le mot de passe et le port.

bash
Copy code
PASSWORD='root'
PORT_BDD=3306
PORT=3000
HOST='http://localhost'
Le mot de passe peut varier en fonction de votre configuration phpMyAdmin (par exemple, 'root', vide, etc.). Le port de la base de données est différent entre les systèmes Mac (8889) et Windows (3306).

🔧 Vérifier la Configuration Frontend

Au cas où le fichier .env n'existe pas déjà à la racine du dossier /front, créez-le. Assurez-vous que les informations suivantes sont correctes :

bash
Copy code
VITE_PORT=3000
VITE_HOST='http://localhost'

🚀 Lancer les Serveurs et l'Application

Pour exécuter le projet, suivez ces étapes :

Lancez le serveur MySQL qui héberge votre base de données (par exemple, via MAMP).

Ouvrez un premier terminal, allez dans le dossier /back et lancez le serveur avec la commande :

bash
Copy code
nodemon
Vous devriez voir les messages suivants dans la console :

bash
Copy code
[nodemon] 2.0.22
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node serveur.js`
Listening on port 3000
Connecté à la base de données MySQL
Ouvrez un deuxième terminal, allez dans le dossier /front et lancez l'application avec la commande :
bash
Copy code
npm run dev
Vous devriez voir les messages suivants dans la console, indiquant que l'application est prête à être utilisée :

bash
Copy code
> front@0.0.0 dev
> vite

  VITE v4.3.9  ready in 1158 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
Vous pouvez appuyer sur la touche "o" ou cliquer sur le lien (par exemple : http://localhost:5173/) pour ouvrir le site.

📝 Réalisation
Dans le cadre de ce projet, j'ai contribué au développement de plusieurs fonctionnalités et à la création de l'interface utilisateur. Voici un aperçu de ce que j'ai accompli :

Pages "Log In" et "Sign Up"
J'ai conçu et développé les pages "Log In" et "Sign Up" de l'application. Cela inclut la mise en place des formulaires de connexion et d'inscription pour les utilisateurs. L'objectif était de créer une expérience utilisateur fluide et conviviale pour l'authentification.

Intégration des Fonctionnalités Backend
J'ai collaboré étroitement avec l'équipe Backend pour intégrer les fonctionnalités qu'ils avaient développées. Cela comprenait la gestion du hachage des mots de passe des utilisateurs pour garantir leur sécurité, ainsi que la création d'une fonction pour vérifier si un utilisateur existe dans la base de données. Cette intégration était essentielle pour que l'interface utilisateur fonctionne de manière transparente avec le backend.

Conception Visuelle
J'ai également participé à la création de maquettes visuelles pour les pages "Log In" et "Sign Up". L'objectif était de garantir une expérience utilisateur optimale en utilisant une conception attrayante et convaincante.

🤝 Contribution
Les contributions sont toujours les bienvenues ! Veuillez suivre ces étapes :

Dupliquez le référentiel du projet. Cela crée une copie du projet sur votre compte que vous pouvez modifier sans affecter le projet d'origine.
Clonez le référentiel dupliqué sur votre machine locale en utilisant un client Git comme Git ou GitHub Desktop.
Créez une nouvelle branche avec un nom descriptif (par exemple, nouvelle-branche-de-fonctionnalité ou correctif-bogue-123).
sh
Copy code
git checkout -b nouvelle-branche-de-fonctionnalité
Effectuez des modifications dans le code du projet.
Validez vos modifications dans votre branche locale avec un message de validation clair expliquant les modifications que vous avez apportées.
sh
Copy code
git commit -m 'Implémentation de la nouvelle fonctionnalité.'
Poussez vos modifications vers votre référentiel dupliqué sur GitHub en utilisant la commande suivante :
sh
Copy code
git push origin nouvelle-branche-de-fonctionnalité
Créez une nouvelle demande d'extraction vers le référentiel du projet d'origine. Dans la demande d'extraction, décrivez les modifications que vous avez apportées et pourquoi elles sont nécessaires. Les mainteneurs du projet examineront vos modifications et fourniront des commentaires ou les fusionneront dans la branche principale.

