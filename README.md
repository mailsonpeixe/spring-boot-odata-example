# spring-boot-odata-example

Spring boot project example for OData protocol

##Example for Requests:

###For get Resources

GET in 
http://localhost:8080/odata/$metadata

###For get objects

GET http://localhost:8080/odata/Fathers

or GET http://localhost:8080/odata/Mothers

For return json format, add ?$format=json like http://localhost:8080/odata/Fathers?$format=json

### Create a entity

POST
http://localhost:8080/odata/Fathers

Object Format(json)

    {
        "Name":"Peter"
    }


