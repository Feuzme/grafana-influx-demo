# Mise en place de la base de données


## Installation :
Docker : 

* Vérifier si docker n'est pas déjà installer :
   1. Rechercher si l'application est déjà présente dans windows en cliquant sur le bouton de recherche
   2. Vérifier s'il n'est pas déjà lancé en ouvrant un terminal et simplement taper ```docker```

* Dans le cas où il n'est pas installé
  1. créer un compte sur : https://hub.docker.com/signup
  2. Se connecter : https://id.docker.com/login
  3. Télécharger en cliquant sur le bouton : **Get started with Docker Desktop**
  4. Installer docker

* Une fois installé :
  1. Chercher l'icone DOCKER (baleine) qui se trouve en bas à droite de votre écran à côté de l'horloge
  2. Faire un clic droit sur la baleine et choisir **settings**
  3. Dans **advanced**, réhausser la mémoire et le nombre de CPU selon les besoins puis cliquer sur **Apply**
  4. Toujours dans les **settings**, cliquer sur **Shared drive** et cocher toutes les cases puis **Apply**

## Lancer le projet

1. ouvrir un terminal à la racine du projet qui doit contenir un fichier **docker-compose.yml**
   
2. taper la commande : ```docker-compose up -d```, cela va lancer les applications.
    Nous devrions avoir :
    ```
    Starting tick_logstash ... done
    Starting tick_influx   ... done
    Starting grafanaV6       ... done
    Starting tick_kapacitor  ... done
    Starting tick_chronograf ... done
    Starting tick_telegraf   ... done
    ```

3. Taper ensuite la commande : ```docker exec -ti tick_influx bash```. Cela nous connecte au terminal du Linux contenant InfluxDB
   
4. Se placer dans le répertoire ```/data``` en tapant la commande ```cd /data```. Dans ce répertoire se trouve des jeux de données. Vérifiez que les fichiers **donnees_influx1** et **donnees_influx2** sont présents en tapant ```ls```
   
5. importez les données en tapant : ```influx -import -path=/data/donnees_influx1```. Cela devrait afficher : 
    ```
     21:57:10 Processed 1 commands
     21:57:10 Processed 1177 inserts
     21:57:10 Failed 0 inserts
    ```
