# Document de Suivi de Projet : Version 2

**Fichier concerné :** `projet2.html` (basé sur `testprojet2.html`)
**Version précédente :** `testprojet1.html`

## 1. Introduction
Cette version introduit le cœur technique du jeu : la génération procédurale. Le jeu passe d'une expérience statique à une expérience rejouable à l'infini grâce à la création aléatoire des niveaux.

## 2. Modifications Fonctionnelles et Logiques

### A. Génération Procédurale
* **Algorithme de Niveau :** Abandon du placement manuel. Le jeu utilise désormais un algorithme qui génère les plateformes les unes après les autres avec des écarts horizontaux et verticaux aléatoires.
* **Accessibilité :** La logique de génération intègre des contraintes pour s'assurer que chaque plateforme reste théoriquement accessible par un saut depuis la précédente.

### B. Système de Pièges Dynamique
* **Placement Aléatoire :** Les pièges ne sont plus fixes. L'algorithme décide aléatoirement, selon des pourcentages de chance, de placer :
    * Des pointes sur les plateformes.
    * Des blocs tombants dans les espaces vides entre les plateformes.
    * Des pièges à retardement.

### C. Éléments Audio (Infrastructure)
* **Préparation Sonore :** Mise en place de la structure de code pour gérer les effets sonores (saut, échec, victoire), bien que les fichiers audio ne soient pas encore pleinement exploités à ce stade.

### D. Adaptation de l'Objectif
* **Fin Dynamique :** La position du drapeau de fin n'est plus fixe (X:751). Elle est désormais calculée automatiquement pour se placer sur la toute dernière plateforme générée par l'algorithme.
