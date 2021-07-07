# Échantillonnage

1. Se placer dans la base de donnée docker
2. afficher les mesures
3. Afficher les séries de cpu en tapant : ```SHOW SERIES FROM cpu```
4. Afficher les noms des tags avec : ```SHOW TAG KEYS FROM cpu```
5. Afficher les noms des fields avec : ```SHOW FIELD KEYS FROM cpu```
6. Afficher les 100 dernières données du field usage_user du tag ayant pour valeur cpu0 de la mesure cpu
7. Grouper la précédente requête par intervalle de 10mn
8. Remplir les valeurs vides par une valeur linéaire
9. Placer les précédentes valeurs dans une autre mesure appelée cpu0_10m
10. Afficher la mesure cpu0_10m
11. Supprimer la mesure cpu0_10m avec ```DROP MEASUREMENT cpu0_10m```
12. Utiliser la requête 9 et ajouter un ALIAS à la colonne avec le mot ```clé AS usage_user```
13. Créer une base de données nommée : copy_data avec la commande ```CREATE DATABASE copy_data```
14. Reprendre la requête 12 mais cette fois, en plaçant les données dans copy_data