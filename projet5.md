# Document de Suivi de Projet : Version 5

**Fichier concerné :** `projet5.html` (basé sur `testprojet5.html`)
**Version précédente :** `testprojet4.html`

## 1. Introduction
Cette mise à jour change fondamentalement la boucle de jeu (Game Loop). Le concept de "mort instantanée = recommencer tout" est remplacé par un système de gestion de points de vie, rendant le jeu plus tolérant et moderne.

## 2. Modifications Fonctionnelles et Logiques

### A. Système de Vies (Health System)
* **Capital de Vies :** Le joueur dispose désormais d'un compteur de 3 vies.
* **Gestion des Dégâts :** Toucher un piège ne réinitialise plus le niveau complet immédiatement. Cela décrémente une vie et replace le joueur au début du niveau actuel.
* **Game Over :** La réinitialisation complète du niveau (génération d'une nouvelle carte) ne se produit que lorsque le compteur de vies atteint zéro.

### B. Feedback Visuel (Juice)
* **Flash Rouge :** Lorsqu'une vie est perdue, un effet de flash rouge couvre l'écran pour indiquer visuellement le dégât.
* **Effets de Mort :** Lors du Game Over définitif, un système de particules (taches de sang) apparaît à l'écran pour dramatiser l'échec.

### C. Interface Utilisateur (UI)
* **Affichage des Cœurs :** L'interface affiche désormais visuellement les vies restantes (ex: ❤️❤️❤️).
* **États du Jeu :** Les textes d'information distinguent maintenant l'état "Blessé" de l'état "Mort définitive".
