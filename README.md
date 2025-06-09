Projet Web - Monsieur Larmoire
1. Introduction
Monsieur Larmoire est un artisan menuisier ébéniste en Normandie, dans le Nord de la France. Il fabrique et rénove des meubles artisanaux tels que des tables, portes, armoires, chaises, frises et sculptures en bois massif. Ce projet vise à créer un site web moderne pour présenter ses réalisations et offrir un espace de contact aux clients.
2. Description du projet
Le projet est développé en utilisant ASP.NET Core MVC et SQL Server. Il inclut l'authentification des utilisateurs (admin et visiteur), la gestion complète des produits, la gestion des catégories, un système de panier avec paiement, une demande de devis et un système de commentaires.
3. Fonctionnalités du site
- Connexion et inscription utilisateur
- Ajout, modification, suppression des produits (admin uniquement)
- Gestion des catégories
- Ajout au panier et paiement simulé
- Demande de devis pour un produit
- Système de commentaires avec réponses
4. Architecture du projet
Le projet est structuré selon le modèle MVC (Model-View-Controller) avec séparation claire des responsabilités :
- Models : Contiennent les classes de données
- Views : Affichage côté utilisateur
- Controllers : Gestion de la logique
- Services et Interfaces : Gestion de la logique métier
- AppDbContext : Gestion des accès à la base de données
5. Base de données
Le projet utilise une base de données relationnelle SQL Server avec les tables suivantes :
- Utilisateurs
- Produits
- Catégories
- DemandesDevis
- Commentaires
6. Services et Interfaces
Les services permettent de gérer les données de manière centralisée (par exemple, gestion des produits, catégories, utilisateurs). Les interfaces assurent que le code est découplé et facilement testable, favorisant la maintenance et l'évolution du projet.
7. Design et thème
Le site suit un thème d'ébénisterie artisanale avec un fond inspiré du bois naturel. L'utilisation de CSS personnalisé donne une touche artisanale chaleureuse à toutes les pages.
8. Déploiement
Pour exécuter le projet sur un autre ordinateur, il suffit de restaurer la base de données, mettre à jour la chaîne de connexion dans appsettings.json et exécuter les migrations Entity Framework.
9. Difficultés rencontrées
Les principales difficultés rencontrées ont été la gestion des paiements simulés, l'intégration des commentaires imbriqués (réponses), et l'application d'un design homogène.
10. Conclusion
Le projet répond à toutes les exigences demandées : présenter les réalisations de M. Larmoire, permettre aux visiteurs de demander un devis, de commenter et d'interagir avec les produits. Le site est prêt pour être montré à des clients potentiels ou être développé davantage pour inclure de vrais paiements en ligne
