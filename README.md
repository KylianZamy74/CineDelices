# 🎬 CinéDelices

## Bienvenue sur le projet Cinédelices ! 🎉

### Qu'est-ce que ce projet ? 🤔

**Cinédelices** est une application web responsive développée avec **React**, **NodeJs**, **PostgreSQL** et **Sequelize**. Cette application permet aux utilisateurs d'explorer un catalogue de films et d'émissions de télévision tout en découvrant des recettes inspirées des plats présents dans les films 🍿🍔. Les visiteurs peuvent également créer et partager leurs propres recettes en lien avec leurs films préférés 🎥🍽️. Grâce à une interface conviviale et une expérience fluide, l'application est accessible sur tous les types d'appareils 📱💻.

Le **backend** est construit avec **NodeJs**, offrant une gestion efficace des données grâce à l'ORM **Sequelize** et à la base de données **PostgreSQL**. Cette solution garantit une expérience performante et sécurisée pour les utilisateurs 🔐🚀.

### Objectifs du projet 🎯

Ce projet collaboratif a été entrepris dans le cadre de notre programme de formation pour préparer l'examen final 📝. Ses principaux objectifs étaient de :  
- 🚀 Évaluer nos forces et nos faiblesses individuelles,
- 💡 Améliorer notre expertise technique,
- 🤝 Développer nos compétences en travail d'équipe et en communication,
- 🔧 Renforcer nos capacités de collaboration et de résolution de problèmes dans des conditions réelles.

### Comment démarrer l'application ? 🚀

#### Backend 🖥️

1. Allez dans le répertoire du backend :

   ```bash
   cd projet-cines-delices-back


2. Installer les dépendances avec npm :

    ```
    npm install

3. Démarrez le serveur : 

    ```
    npm run dev

#### Frontend 🎨

1. Aller dans le répertoire du frontend : 

    ```
    cd projet-cines-delices-front
    cd CineDelice-front
2. Installez les dépendances avec npm :

    ```
    npm install
3. Lancez l'application :

    ```
    npm run dev

### Configuration de la base de données 🗄️

1. Copiez le fichier .env.example et renommez-le en .env.

2. Ajoutez votre mot de passe PostgreSQL dans le fichier .env en remplissant la variable PGPASSWORD.

3. Créez les rôles et la base de données avec les commandes suivantes :
    ```
    CREATE ROLE root WITH LOGIN PASSWORD 'yourpassword';
    CREATE DATABASE cinedelices OWNER root;

4. Exécutez les scripts SQL pour créer les tables et insérer les données :

    ```
    psql -U root -d cinedelices -f create_tables.sql
    psql -U root -d cinedelices -f seeding_tables.sql


🎉 Voilà ! Vous êtes maintenant prêts à explorer l'application **CinéDelices**. 🎬


