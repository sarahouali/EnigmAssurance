Ce code crée une classe Produit qui représente un produit générique avec un nom et un prix.
Les classes Action et Obligation héritent de Produit et ajoutent des propriétés supplémentaires
 pour représenter des actions et des obligations d'État.
 

La classe Portefeuille contient une liste de produits et des méthodes pour
 ajouter des produits et calculer la valeur du portefeuille.

Dans la méthode main, le programme demande à l'utilisateur de saisir les informations
 pour une action et une obligation d'État, crée les objets correspondants.
Les trois classes Produit, Action et Obligation sont des classes qui représentent les 
produits d'assurance dans notre programme.
 La classe Produit contient les propriétés nom et prix.
 Les classes Action et Obligation héritent de la classe Produit et ajoutent des propriétés supplémentaires :
 entreprise pour Action et tauxInteret pour ObligationEtat.

La classe Portefeuille contient une liste de produits (ArrayList<Produit> produits) et deux méthodes :

ajouterProduit(Produit p) qui permet d'ajouter un produit au portefeuille
valeurPortefeuille() qui permet de calculer la valeur du portefeuille en faisant 
la somme des prix de tous les produits qu'il contient.
Dans la méthode main, nous créons un objet Scanner pour permettre à l'utilisateur
 de saisir les informations pour une action et une obligation d'État.

Nous créons ensuite un objet Portefeuille vide.

Nous demandons ensuite à l'utilisateur de saisir les informations pour une Action en utilisant 
la méthode nextLine() 
pour lire les chaînes de caractères entrées par l'utilisateur, et la méthode parseDouble() 
pour convertir une chaîne de 
caractères en un nombre décimal. Nous créons ensuite un objet Action avec les informations 
 saisies et nous l'ajoutons au portefeuille en utilisant la méthode ajouterProduit().

Nous affichons ensuite la valeur du portefeuille en appelant la méthode valeurPortefeuille().

Enfin, nous fermons l'objet Scanner pour libérer les ressources utilisées.

Ce programme permet donc de créer un portefeuille d'actions et d'obligations d'État,
 d'y ajouter des produits et de calculer la valeur du portefeuille. 
 Bien sûr, ce programme peut être étendu pour inclure plus de types
 de produits d'assurance et de fonctionnalités.

