Enveloppe Convexe :
===================

But du projet :
---------------

Mettre en place un algorithme permettant de récupérer l'enveloppe convexe d'un nuage de point dans un plan en 2 dimensions.  
Ce programme a été réalisé en C++ avec OpenGL.  
Il permet d'exécuter différents algorithmes afin de récupérer les points de l'enveloppe convexe.

Comment utiliser le programme :
-------------------------------

## Installer 

Verifier que `gcc` est installe afin de compiler le c.  
Ainsi que `cmake` pour le makefile.  
Pour la partie opengl, verifiez que ces package linux soient installes `libglfw3-dev libgl1-mesa-dev libglu1-mesa-dev freeglut3 freeglut3-dev`

## Lancer le code

Pour compiler : `make`  

Pour executer (compile si ce n'est pas fait) : `make execute`  
Pour executer en précisant le nom d'un fichier de points : `make execute FILE=points.don`

L'ensemble des actions possibles sont écrites dans la console.
Avec l'auto-completion de make dans la console il est possible de voir les differentes commandes pre-ecrite

Pour nettoyer : `make clean`