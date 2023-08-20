# BusStationAPI
An API Project made in Anypoint Studio.
The project is supposed to simulate an API of a Bus Station Informatics System.
The database of which the data is being extracted has been made in MySQL. Therefore in order to access the data, you would have to have your own local database.
The DDL and INSERT query scripts are imported in the folder by the name of "QUERY SCRIPTS". Also, a class diagram for the database is included.
Although, keep in mind that you would need to specify new parameters in the "global.xml" global configuration elements.
Specifically for the "Configuration Properties" global element.

Afterwards, you could use the following endpoints to communicate with the api (assuming you have created the database and configured the parameters):

*localhost:8081* will be used for every endpoint (just add it before every string below).

GET:
/api/autobus - Get all buses
/api/autobus/1 - Get a bus with the id of 1

POST:
/api/autobus - Insert a new bus (also specify the correct body)

PUT:
/api/autobus/1 - Update a bus with the id of 1 also specify the correct body)

DELETE:
/api/autobus/1 - Delete a bus with the id of 1

In order to access other data, you would just change "autobus" with any of these other elements:

garaza,
karta,
korisnik,
ruta,
tipKarte,
vozac,
zaposleni
