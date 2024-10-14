

 Application de Gestion de Projet

Cette application Java permet de gérer des projets et d'imputer le temps passé sur chaque tâche.  

Fonctionnalités
- Gestion des projets, tâches, et employés.
- Affichage des tâches réalisées par un employé.
- Affichage des projets gérés par un employé.
- Affichage des tâches planifiées pour un projet.
- Détails des tâches réalisées dans un projet.
- Filtrage des tâches dont le prix est supérieur à 1000 DH.
- Affichage des tâches réalisées entre deux dates.

 Structure du Projet
- Couche Persistance : Entités dans `ma.projet.classes`, configuration dans `hibernate.cfg.xml`, et gestion de session avec `HibernateUtil`.
- Couche Service : Interface `IDao` et classes `ProjetService`, `TacheService`, `EmployeService`, `EmployeTacheService`.

 Installation
1. Créer la base de données `projets` sous MySQL.
2. Ajouter les bibliothèques Hibernate et JPA.
3. Configurer `hibernate.cfg.xml`.
