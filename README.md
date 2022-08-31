# pgSQL_pgAdmin_docker_practics
this project pulls the PostgreSQL, Latest and the PGAdmin, Latest version docker image,
it comprices of a Dockerfile.txt, and a docker-compose.yaml file in it

>## THE PORTS MAPPING
>- pgSQL is listenig on its default port i.e 5432
>- PGadmin is litening on port 8080
>>     http://localhost:8080
>>- But the ports can be changed in the docker-compose.yaml file

>## LOGIN DETAILS
>- **For pgSQL :** 
>> ***hostname***
>>>       meecky-pgdb
>> ***password*** 
>>>       MEECKY
              
>- **For PGadmin :** 
>>  ***username***
>>>                user@domain.com
>>  ***password***
>>>                SuperSecret
>> But the ports can be changed in the docker-compose.yaml file

>## TO CONNECT WITH THE TERMINAL, USE THE FOLLOWING COMMANDS
>>     docker exec -it meecky-pgdb bash
>>>     psql -U postgres

>> **NOTE:** meecky meecky-pgdb, and meecky-pgadmin are the container name for the postgres db, and pgadmi respectively,
and they can be changed to whatever you want in the docker-compose.yaml file.
if changed, then remember ro also impliment changes every where necessary
