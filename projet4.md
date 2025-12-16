# Document de Suivi de Projet : Version 4

**Fichier concerné :** `projet4.html` (basé sur `testprojet4.html`)
**Version précédente :** `testprojet3.html`

## 1. Introduction
L'objectif de cette version était d'améliorer l'expérience utilisateur initiale en créant une difficulté progressive et en résolvant des problèmes d'ergonomie liés à la position de l'arrivée.

## 2. Modifications Fonctionnelles et Logiques

### A. Logique Spécifique "Niveau 1"
* **Introduction à la Douceur :** Le code distingue maintenant le "Niveau 1" des autres.
* **Restriction des Pièges :** Pour ce premier niveau, les pièges complexes (blocs tombants, pièges retardés) sont désactivés. Seules les pointes fixes (Spikes) sont générées, permettant au joueur d'apprendre les bases sans être submergé.

### B. Contraintes de la Plateforme de Fin (Goal)
* **Centrage Vertical :** De nouvelles constantes ont été introduites pour forcer la plateforme de fin à apparaître dans une zone centrale de l'écran.
* **Amélioration Ergonomique :** Cela empêche le drapeau d'apparaître tout en haut (difficile à voir) ou tout en bas (risque de confusion avec le vide), rendant l'objectif final toujours clair.

### C. Nettoyage du Code
* **Optimisation :** Suppression définitive des anciens segments de code liés aux obstacles statiques et aux méthodes de génération obsolètes pour ne conserver que la logique dynamique optimisée.
