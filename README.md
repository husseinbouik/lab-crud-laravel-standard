# lab-crud-standard

## Prérequis : lab-crud-basic

Avant de commencer le travail sur le lab-crud-standard, assurez-vous d'avoir préalablement accompli les étapes du lab-crud-basic. Le lab-crud-basic crée la base nécessaire pour le lab-crud-standard en fournissant une implémentation initiale des opérations CRUD pour les tâches.

## Travail à Faire
Votre mission consiste à compléter les opérations CRUD de base dans le laboratoire Laravel en suivant le design pattern Repository. Il est également nécessaire d'implémenter la fonctionnalité de recherche AJAX, d'ajouter la pagination, d'intégrer une table pour les projets, et de coder les opérations CRUD associées aux projets et aux tâches.

## Critères de Validation
Veuillez vous assurer que les critères suivants sont respectés :
- Réaliser les opérations CRUD de base pour le laboratoire Laravel, incluant les tâches et les projets.
- Mettre en œuvre la pagination pour améliorer l'expérience utilisateur.
- Implémenter la fonctionnalité de recherche en utilisant AJAX.
- Utiliser le design pattern Repository pour une organisation optimale du code.
- Intégrer la possibilité de filtrer les tâches par projet, offrant ainsi une gestion efficace des projets.

## Flux de Travail 

Pour faciliter le processus de configuration et de travail sur le laboratoire, suivez ces étapes optimisées :

1. **Clonez le Projet de Base :**
   ```bash
   git clone https://github.com/husseinbouik/lab-crud-standard.git
   ```
   Commencez par cloner le projet de base pour la gestion des tâches.

2. **Configuration de l'Environnement :**
   ```bash
   cd "lab-crud-standard"
   cp .env.example .env
   ```
   Créez le fichier .env en utilisant le modèle fourni et ajoutez le nom de la base de données approprié.

3. **Installation des Dépendances avec Composer :**
   ```bash
   composer install
   ```
   Assurez-vous que toutes les dépendances du projet sont correctement installées.

4. **Génération de la Clé de l'Application :**
   ```bash
   php artisan key:generate
   ```
   Assurez-vous de générer une clé unique pour votre application Laravel.

5. **Migration des Tables vers la Base de Données :**
   ```bash
   php artisan migrate
   ```
   Migrez les tables nécessaires vers la base de données.

6. **Peuplement de la Base de Données avec des Données d'Exemple :**
   ```bash
   php artisan db:seed
   ```
   Facilitez les tests en ajoutant des données d'exemple à votre base de données.

7. **Lancement du Serveur Local :**
   ```bash
   php artisan serve
   ```
   Exécutez cette commande pour démarrer votre serveur local et surveiller l'avancement de votre projet.

## References

- [Laravel Documentation](https://laravel.com/docs/10.x)
- [Découverte de Laravel 10 Grafikart](https://grafikart.fr/formations/laravel)
