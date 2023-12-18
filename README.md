# SGBDR

# Projet de Base de Données PostgreSQL avec Python

Ce projet implique la création et la gestion d'une base de données PostgreSQL, l'utilisation de Docker pour l'installation de PHPMyAdmin, et le peuplement de la base de données avec des données fictives générées par Faker.

## Configuration du Projet

### Prérequis

- PostgreSQL
- Python 3.x
- Docker (pour PHPMyAdmin)
- Bibliothèques Python : `psycopg2`, `Faker`

### Installation

1. **Installation de Docker Desktop** :
   - Pour Windows ou macOS, téléchargez et installez Docker Desktop depuis [Docker Hub](https://www.docker.com/products/docker-desktop).

2. **Installation de PostgreSQL** :
   - Installez PostgreSQL sur votre système.
   - Créez une base de données nommée `test`.

3. **Installation des Bibliothèques Python** :
   - Exécutez `pip install psycopg2-binary faker` pour installer les bibliothèques nécessaires.

4. **Démarrage de PHPMyAdmin avec Docker** :
   - Utilisez Docker pour lancer PHPMyAdmin en exécutant les commandes Docker appropriées.

## Utilisation

### Connexion à la Base de Données avec Python

- Utilisez `psycopg2` pour vous connecter à votre base de données PostgreSQL.
- Le script Python inclut des commandes pour créer un utilisateur et lui attribuer des droits, créer des tables et insérer des données.

### Génération de Données Fictives avec Faker

- Utilisez `Faker` pour générer des données fictives pour peupler la base de données.
- Le script Python génère des noms d'utilisateurs et des fruits préférés de manière aléatoire.

### Manipulations de Base de Données

- Le projet comprend des exemples de scripts pour créer des tables, insérer, mettre à jour et récupérer des données.

## Dépannage

- En cas de problèmes de connexion ou d'erreurs, vérifiez les paramètres de connexion, les privilèges de l'utilisateur et assurez-vous que toutes les commandes SQL sont correctement formulées.

## Sécurité

- Assurez-vous de suivre les meilleures pratiques de sécurité, notamment en utilisant des mots de passe forts et en n'accordant que les privilèges nécessaires.
