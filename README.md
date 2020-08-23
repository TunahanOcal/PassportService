* It is a Rest service that is created with Spring Boot, Spring JPA and Hibernate.
* Crate a MySQL database using sql files under PassportDatabaseSqlfiles folder. The database containg all passports and their visa informations.
* Change application.properties access credential with yours.
* For packaging use "mvn package". It creates a jar file. "java -jar <your jar file>"


**Provided Rest Services**
***********************************************************************************
**Getting All Passports**
* URL: http://localhost:9090/passports
* Method: GET
* Path Variable: NA
* Request Body: NA
* Response Body: Passport List

**Getting All Relations for Country Origin**
* URL: http://localhost:9090/relations/countryCode(small case)
* Method: GET
* Path Variable: NA
* Request Body: NA
* Response Body: Passport List

