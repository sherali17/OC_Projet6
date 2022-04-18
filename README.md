# OC_Projet5
Classifiez automatiquement des biens de consommation pour un site d'e-commerce.

## Contexte
L’entreprise "Place de marché”, souhaite lancer une marketplace e-commerce.
Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, 
et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et 
des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle,
il devient nécessaire d'automatiser cette tâche.

## Mission
Etudier la faisabilité d'un moteur de classification des articles en différentes catégories,
avec un niveau de précision suffisant.

Consignes :
Afin d’extraire les features image, il sera nécessaire de mettre en œuvre :
- un algorithme de type SIFT / ORB / SURF,
- un algorithme de type CNN Transfer Learning.
