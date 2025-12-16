# Document de Suivi de Projet : Version 6

**Fichier concerné :** `projet6.html` (basé sur `testprojet6.html`)
**Version précédente :** `testprojet5.html`

## 1. Introduction
Cette version se concentre sur l'immersion ("Game Juice") et l'expérience utilisateur globale (UX). Le jeu acquiert une identité propre avec une présentation soignée et une ambiance sonore complète.

## 2. Modifications Fonctionnelles et Logiques

### A. Écran d'Accueil (Splash Screen)
* **Nouvelle Interface :** Création d'un écran de bienvenue avant le menu principal, invitant le joueur à entrer dans l'univers du jeu.
* **Bouton Start :** Ajout d'un bouton "COMMENCER" animé pour lancer l'expérience.
* **Crédits :** Ajout des crédits du développeur.

### B. Refonte Audio Complète
* **Gestionnaire Audio :** Implémentation d'un système robuste (`AudioSys`) pour gérer les sons.
* **Ambiance :** Ajout d'une musique de fond (BGM) en boucle.
* **Effets Sonores (SFX) :** Intégration de sons pour toutes les actions : clic, saut, double saut, dégâts, mort, rire maléfique (Game Over) et victoire.

### C. Rythme de Jeu
* **Compte à Rebours :** Ajout d'une phase de préparation ("3, 2, 1, GO!") au début de chaque vie ou niveau, figeant le joueur momentanément pour lui laisser le temps d'analyser le terrain.

### D. Améliorations Visuelles
* **Animations CSS :** Ajout d'effets de pulsation sur les titres et de transitions fluides entre les différents écrans (Accueil, Menu, Jeu).
