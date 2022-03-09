# Argonauts
- REST API

## Stack
- Gradle
- Java 11
- Spring Boot 2.6.4
- MySQL

## Port
- default port 8080

## Endpoints

- POST /argonauts -> create
- GET	/argonauts -> getAll
- GET /argonauts/{id} -> get
- PUT /argonauts/{id} -> update
- DELETE /argonauts/{id} -> delete

## Model

``` json
student {
  "id": "Long",
  "name": "String",
  "identityNumber": "String",
  "studentSince": "LocalDate",
  "birthdate": "LocalDate",
  "cellphone": "Long",
  "email": "String",  
  "postalCode": "String",
  "addressLine": "String",
  "bill": "double",
  "lastPayDate": "LocalDate"
}
```