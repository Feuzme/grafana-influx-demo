# GROUP BY

1. importer le fichier **/data/samples/donnees_influx2** en incluant la précision en secondes. Le résultat devrait être :
    ```
     02:42:42 Processed 1 commands
     02:42:42 Processed 76290 inserts
     02:42:42 Failed 0 inserts
    ```

2. placez vous dans le CLI de influx
   
3. Afficher les BDD. Nouvelle BDD : NOAA_water_database
   
4. Sélectionner NOAA_water_database
   
5. Afficher les mesures
   
6. Afficher 10 entrées de la température
   
7. Afficher le timestamp de façon lisible en tapant dans le CLI d'InfluxDB : ```precision rfc3339```
   
8. Donner la moyenne des températures groupées par chacun des lieux
   
9. Donner la température maximum groupées par chacun des lieux entre 2015-09-16T08:24:00Z et 2015-09-16T09:12:00Z

