# Modal JavaScript

Ce projet est une démonstration d'un modal simple réalisé en utilisant HTML, CSS et JavaScript. Un modal est une fenêtre contextuelle qui s'affiche par-dessus le contenu principal de la page pour afficher des informations supplémentaires ou une interaction spécifique.

## Fonctionnement

Le modal est déclenché à partir d'un bouton "Open". Lorsque l'utilisateur clique sur ce bouton, le modal s'affiche avec un effet de transition. Le contenu du modal comprend un titre et un paragraphe.

Le modal peut être fermé en cliquant sur le bouton "X" situé en haut à droite de la fenêtre modale ou en cliquant en dehors de la fenêtre modale sur le fond sombre en arrière-plan.

## Structure du Projet

Le projet est constitué de trois fichiers principaux :

index.html: Ce fichier contient la structure HTML de la page, y compris le bouton qui déclenche le modal et la structure du modal lui-même.

style.css: Ce fichier contient les styles CSS qui définissent l'apparence du modal, du bouton et du fond sombre en arrière-plan.

app.js: Ce fichier contient le code JavaScript qui gère le fonctionnement du modal. Il utilise la méthode classList.toggle() pour ajouter ou supprimer la classe "active" du conteneur du modal, ce qui contrôle son affichage en fonction de l'état actuel.

## Personnalisation

Vous pouvez personnaliser le contenu du modal en modifiant le balise h1 et la balise p ainsi que la balise avec l'id "modalTitle" et "dialogDesc" respectivement, dans le fichier index.html. Vous pouvez également ajuster les styles du modal en modifiant les règles CSS dans le fichier style.css.






