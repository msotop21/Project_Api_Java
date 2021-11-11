# Test_ApiRest_Users_Nisum

Informacion servicio de usuarios

Metodo POST Login

http://localhost:8080/login 
  -H 'content-type: application/json' 
  -d '{
    "email": "root@root.com",
    "password": "root"
}'
 
Metodo GET 

GET http://localhost:8080/users



Metodo GET Utilizando ID

GET http://localhost:8080/users/{id}



Metodo POST Usuario

POST http://localhost:8080/users 
  -H 'content-type: application/json' 
  -d '{
    "name": "Pedro Martinez",
    "email": "pmartinez@gmail.com",
    "password": "Pedro21",
    "phones": [
        {
            "number": "1234567",
            "citycode": "1",
            "contrycode": "57"
        }
    ]
}'

Metodo PUT Usuarios

PUT http://localhost:8080/users 
  'content-type: application/json' 
  '{
   "name": "Pedro Martinez",
   "email": "pmartinez@gmail.com",
   "password": "Pedro21",
   "phones": [
       {
           "number": "1234567",
           "citycode": "1",
           "contrycode": "57"
       }
   ]
}'
