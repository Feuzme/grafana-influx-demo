1. SHOW DATABASES;
   USE holiday_france;
2. SHOW MEASUREMENTS;
3. SHOW SERIES;
4. SELECT * FROM speed_ms;
5. SELECT * FROM altitude_m;
6. SELECT * FROM speed_ms LIMIT 10;
7. SELECT time,speed FROM speed_ms LIMIT 2;
8. SELECT *::field FROM speed_ms LIMIT 2;
9. SELECT (speed*3.6) FROM speed_ms LIMIT 2;
10. SELECT * FROM speed_ms, altitude_m  LIMIT 2;
11. SELECT * FROM "speed_ms" WHERE "speed" < 12 LIMIT 3;
12. SELECT * FROM "speed_ms" WHERE "speed" > 12 LIMIT 3;
13. SELECT * FROM "speed_ms" WHERE "speed" > 12 AND time<1502209296 LIMIT 3
14. SELECT * FROM "speed_ms" WHERE time > now() - 895d LIMIT 3
15. influx -precision s -import -path=/data/donnees_influx1
16. SELECT * FROM "speed_ms" WHERE time > now() - 895d LIMIT 3
17. SELECT * FROM "speed_ms" WHERE time > '2017-06-30T21:24:00Z' LIMIT 3
18. SELECT * FROM "speed_ms" WHERE time >= '2017-06-30'