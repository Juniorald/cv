# Document de Suivi de Projet : Version 7

**Fichier concerné :** `projet7.html` (basé sur `testprojet7.html`)
**Version précédente :** `testprojet6.html`

## 1. Introduction
La version finale introduit la sélection de la difficulté. Le jeu devient paramétrable, offrant des expériences très différentes selon le profil du joueur, allant de la promenade facile au défi hardcore.

## 2. Modifications Fonctionnelles et Logiques

### A. Sélection de Difficulté
* **Menu Principal :** Le menu propose désormais trois choix distincts : Débutant (Vert), Amateur (Jaune) et Expert (Rouge).
* **Styles Distincts :** Chaque bouton de difficulté possède sa propre identité visuelle.

### B. Paramétrage Dynamique (Vies)
* **Vies Variables :** Le capital de départ change selon le mode choisi :
    * Débutant : 6 Vies.
    * Amateur : 3 Vies.
    * Expert : 1 Vie (Mort subite).

### C. Génération de Niveau Adaptative
* **Densité de Pièges :** L'algorithme de génération reçoit maintenant le paramètre de difficulté.
* **Probabilités Ajustées :** La chance d'apparition d'un piège sur une plateforme passe de 30% (Débutant) à 90% (Expert).
* **Placement Vicieux :** En mode Expert, la logique de placement des pièges est modifiée pour être plus imprévisible (positionnement plus aléatoire sur la plateforme elle-même).

### D. Interface Adaptative
* **Feedback :** Le titre du niveau en jeu rappelle la difficulté et le nombre de vies.
* **Gestion de l'affichage :** L'affichage des cœurs s'adapte pour rester lisible même avec un grand nombre de vies (mode Débutant).
