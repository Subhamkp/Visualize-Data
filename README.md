Its a simple python code used to visualize the places present in the where.data file in google map. 

Google Maps Geocoding API is very useful and i used to get the latitude  and longitude of the places.

For more: https://developers.google.com/maps/documentation/geocoding/start

Steps to run:

1) Compile Geoload.py
2) Compile Geodump.py
3) Open where.html

    Success!!


Sqlite is used as a database in the program.

Geoload.py

geoload.py creates a table Locations and stores the address along with  the json data received from api call for each places present in where.data file.

Geodump.py

geodump.py read the datas from the database and writes the longitude and longitude along with formatted_address in JSON format in where.js
to visualize it on a map.

where.html

It contains simple google map code with marker. All the formatted_address with latitude,longitude are retrieved by including where.js and marker 
is placed.

Thank You !!
