# Requêtes SELECT

Remarque :
1. Les données doivent bien être importée (voir TP1)

2. Les données de la BDD **holiday_france** se présente ainsi :
    ```
        time       location     speed     speed description
    ----       --------     -----     -----------------
    1502208946   france      13.57     speed in meter per second
    1502208947   france      13.32     speed in meter per second
    ```

## Requêtes

1. Se placer dans la BDD holiday_france.
   
2. Afficher les mesures 
   
3. Afficher les series

4. Afficher toutes les données liées à la mesure de la vitesse

5. Afficher toutes les données liées à la mesure de l'altitude

6. Selectionner les 10 dernières valeurs de la vitesse

7. Selectionner les fields : time et speed de speed_ms. Limiter à 2 valeurs 

8. Afficher tous les fields de speed_ms

9. Afficher la vitesse de speed_ms en km/h (il faut multiplier par 3.6)

10. Afficher les 3 premières mesures de l'altitude et de la vitesse en une seule requête SELECT
    
11. Selectionner les 3 premières mesures de speed_ms dont la vitesse est inférieure à 12

12. Selectionner les 3 premières mesures de speed_ms dont la vitesse est supérieure à 12
    
13. Selectionner les 3 premières mesures de speed_ms dont la vitesse est supérieure à 12 et dont le timestampe est inférieur à 1502209296;
    
14. Afficher les données des 895 derniers jours
    
15. réimporter les données en donnant la précision en seconde

16. Afficher les données des 895 derniers jours
    
17. Afficher les données depuis le 30 juin 2017 à 21h24 UTC 
    
18. Afficher les données depuis le 29 juin 2017 inclus