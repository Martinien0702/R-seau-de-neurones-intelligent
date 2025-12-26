# **Projet UA 3 – Réseau de neurones intelligent**: 
## **Introduction**: 

### **Contexte**: 

Dans ce projet, vous devez créer un réseau de neurones dans le but de pouvoir jouer au jeu du
Tic-Tac-Toe. Vous connaissez certainement le jeu du Tic-Tac-Toe qui consiste simplement à placer un X ou O
dans l’une des 9 cases possibles à tour de rôle et former une ligne horizontale, verticale ou
diagonale pour gagner. Nous pouvons représenter cette grille dans un vecteur en associant
simplement un numéro de 0 à 8 pour chacune des cases. De plus, nous pouvons associer une
case vide (0), le X (1) et le O (-1) à des chiffres également.



### **Instructions**
Vous devrez dans un premier temps créer un réseau de neurones simple basé sur les
données fournies. Ensuite, vous devrez créer de nouvelles données d’entraînement en bataillant
votre modèle contre lui-même et enfin en entrainant un nouveau modèle sur ces données.

### Colonnes

Nous pouvons représenter cette grille dans un vecteur en associant
simplement un numéro de 0 à 8 pour chacune des cases. De plus, nous pouvons associer une
case vide (0), le X (1) et le O (-1) à des chiffres également.
En utilisant cette représentation, nous pouvons créer un réseau de neurones prenant l’état (-1, 0,1) de chacune des cases en entrées et prédisant la case avec le meilleur prochain mouvement. Il
s’agit d’un problème de classification multi-classe.

Donc les Cell_? représentes les cellules ou les case de notre grille de jeu

L'étiquette est move



### **Objectif**

Nous pouvons représenter cette grille dans un vecteur en associant
simplement un numéro de 0 à 8 pour chacune des cases. De plus, nous pouvons associer une
case vide (0), le X (1) et le O (-1) à des chiffres également.
En utilisant cette représentation, nous pouvons créer un réseau de neurones prenant l’état (-1, 0,1) de chacune des cases en entrées et prédisant la case avec le meilleur prochain mouvement. Il
s’agit d’un problème de classification multi-classe.

Donc les Cell_? représentes les cellules ou les case de notre grille de jeu

L'étiquette est move
