# Première Requête

Remarque :
Les données doivent bien être importée (voir TP1)

## Première requete

1. Se placer dans le Linux contenant InfluxDB

2. Taper la commande : ```influx```. Elle vous permet de vous connecter au SGBD en ligne de commande

3. Taper la commande : ```show databases;```. Elle vous montre les BDDs

4. Taper la commande : ```use holiday_france;```. Elle vous connecte à la BDD holiday_france et devrait afficher : ```Using database holiday_france```

5. Taper la commande : ```SELECT * FROM speed_ms;``` et devrait afficher : 
    ```
        time       location     speed     speed description
    ----       --------     -----     -----------------
    1502208946    france      13.57     speed in meter per second
    1502208947    france      13.32     speed in meter per second
    ```