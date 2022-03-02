# popeyeDocker

Popeye docker est un projet EPITECH visant à découvrir et apprendre les bases de Docker ( Dockerfile, docker-compose..) <br>

## Caractéristiques du projet

Cinq éléments constituent l'application :
- Poll, une application web Flask Python qui recueille les votes et les pousse dans une file d'attente Redis.
- Une file d'attente Redis, qui contient les votes envoyés par l'application Poll, en attendant qu'ils soient consommés par le
le travailleur.
- Le travailleur, une application Java qui consomme les votes se trouvant dans la file d'attente Redis et les stocke dans une base de données PostgreSQL.
une base de données PostgreSQL.
- Une base de données PostgreSQL, qui stocke (de manière persistante) les votes stockés par le Worker.
- Resultat, une application web Node.js qui récupère les votes dans la base de données et affiche le. . . . eh bien, le résultat. 
