1. influx -precision s -import -path=/data/samples/donnees_influx2
2. influx
3. show databases
4. use NOAA_water_database
5. SHOW MEASUREMENTS;
6. SELECT * FROM h2o_temperature LIMIT 10;
7. precision rfc3339
8. SELECT MEAN(degrees) FROM h2o_temperature GROUP BY location;
9. SELECT location,MAX(degrees) FROM h2o_temperature WHERE (time>'2015-09-16T08:24:00Z') AND (time<'2015-09-16T09:12:00Z') GROUP BY location