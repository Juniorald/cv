# Document de Suivi de Projet : Version 1

**Fichier concerné :** `projet1.html` (basé sur `testprojet1.html`)
**Version précédente :** `testprojet.html`

## 1. Introduction
Cette première itération majeure marque la transition d'un prototype technique brut vers une structure de niveau jouable. L'objectif était de définir un parcours fixe pour tester les mécaniques de base sans la complexité de la génération aléatoire.

## 2. Modifications Fonctionnelles et Logiques

### A. Simplification des Mécaniques
* **Suppression des Obstacles :** La classe et la logique gérant les obstacles gris (bloquants) ont été retirées du code pour alléger le gameplay et se concentrer sur la plateforme pure.

### B. Level Design (Conception de Niveau)
* **Parcours Fixe :** Le niveau n'est plus aléatoire. Les plateformes ont été positionnées manuellement (codées en dur) pour créer un parcours en escalier progressant vers la droite.
* **Zone de Danger :** Une "ligne de pièges" continue a été ajoutée au bas de l'écran (Y: 510). Cela remplace le simple vide par une menace visuelle explicite.
* **Pièges Surprises :** Des pièges unitaires ont été placés manuellement à des endroits stratégiques sur les plateformes pour augmenter la difficulté.

### C. Objectif de Jeu
* **Précision de la Fin :** La zone de victoire (le drapeau) a été déplacée à des coordonnées fixes et précises (X:751, Y:81) pour correspondre à la fin du parcours en escalier.
* **Interface :** Le texte de l'objectif a été mis à jour pour guider le joueur vers ces nouvelles coordonnées.
