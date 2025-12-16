# Document de Suivi de Projet : Version 3

**Fichier concerné :** `projet3.html` (basé sur `testprojet3.html`)
**Version précédente :** `testprojet2.html`

## 1. Introduction
Cette version est une étape de consolidation ("Polishing"). Elle vise à corriger les défauts observés dans la génération aléatoire de la version précédente pour garantir que le jeu est toujours jouable et visuellement cohérent.

## 2. Modifications Fonctionnelles et Logiques

### A. Amélioration de la Génération (Bounds Checking)
* **Limites du Monde :** La logique de génération a été renforcée pour empêcher les plateformes d'être créées hors de l'écran (trop haut ou trop bas).
* **Sécurité de la Fin :** Une correction spécifique a été appliquée à la plateforme finale pour s'assurer que le drapeau de fin est toujours accessible et ne sort pas du cadre du canvas.

### B. Équilibrage
* **Ajustement des Sauts :** Les distances minimales et maximales entre les plateformes ont été ajustées pour fluidifier les déplacements du joueur.
* **Probabilités :** Les chances d'apparition des pièges ont été calibrées pour éviter des situations impossibles ou frustrantes.

### C. Fiabilité du Reset
* **Cycle de Jeu :** Le mécanisme de redémarrage (Reset) a été optimisé pour garantir qu'une nouvelle "graine" (seed) est bien utilisée à chaque mort, assurant un niveau totalement différent à chaque essai.
