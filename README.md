# Prédiction de Pourboires et Types de Forêt

Ce dépôt Git a été réalisé dans le cadre d'un projet universitaire pour la matière *Apprentissage Supervisé*.  
Nous disposons de deux jeux de données distincts :  
1. Un dataset sur les pourboires de taxi à New York (problème de régression).  
2. Un dataset sur les types de forêt dans le Colorado (problème de classification).  

L'objectif est de développer des modèles prédictifs adaptés à chacun de ces contextes.

---

## 1. Taxi Tips

Nous nous intéressons à la prédiction du montant des pourboires (tips) versés pour des courses de taxi à New York.  
### Jeu de données :
- **Taille** : 100 000 courses de taxi effectuées en janvier 2024.
- **Variables disponibles** :  
  - Coordonnées géographiques des points de départ (*pick-up*) et d'arrivée (*drop-off*).  
  - Distance du trajet.  
  - Heure de début et de fin.  
  - Montant total de la course, etc.  

### Objectif : 
Prédire le montant des pourboires à partir des informations descriptives de chaque course.  


---

## 2. Forest Cover Type

Nous étudions ici un problème de classification consistant à prédire le type de forêt pour des parcelles situées dans la **Roosevelt National Forest**, au nord du Colorado.  
On dispose de variable tels que l'altitude, la distance a la route la plus proche, la distance au points d'eau le plus proche...

### Objectif :
Prédire le plus correctement possible le type de forets pour des parcelles données. 
