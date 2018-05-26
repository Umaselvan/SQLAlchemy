# SQLAlchemy
Basic SQLAlchemy 


SQLAlchemy is a library that facilitates communication between Python programs and databases. 
This library is used as an Object Relational Mapper (ORM) tool that translates Python classes to tables on relational databases and 
automatically converts function calls to SQL statements. 

SQLAlchemy allows developers to create database-agnostic code to communicate with a wide variety of database engines.
Boilerplate code to handle tasks like database connections is abstracted away to let developers focus on business logic.

##### Reference:
https://auth0.com/blog/sqlalchemy-orm-tutorial-for-python-developers/

I have the below table structure & I use ORACLE db.

### Movies

| title | director | year |
| --- | --- | --- |
| Citizen Kane | Orson Welles | 1941 |
| La Dolce Vita | Federico Fellini | 1960 |
| Dr. Strangelove | Stanley Kubrick | 1964 |
| Pather Panchali | Satyajit Ray | 1965 |
| Seven Samurai | Akira Kurosawa | 1954 |

### Genre

| title | genre | runtime |
| --- | --- | --- |
| Citizen Kane | Drama | 120 |
| La Dolce Vita | Drama | 110 |
| Dr. Strangelove | Comedy | 90 |
| Pather Panchali | Drama | 100 |
| Seven Samurai | Action | 180 |



