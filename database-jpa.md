Database:
It is a place where data related to your users and product is stored

TYpes:
Relational
Non-Relational

DBMS:
It is an interface that sits blw the user and the database
Examples:
MySQL
Oracle Database
SQL Server
MongoDB
Cassandra

DBMS Terminologies:
Table : It is a structure that organizes data in a structured and organized way
Column : It repesents a property of the table
Row: It is also known as Tuple Or Record

SQL:
Stands for Structued Query Language
Used to retrieve, manage and update data 

ORM:
Whenever there is a class, that class can be automatically converted to a table with its attriutes being converted to columns
Developer does not have to write queries for table creation, its created automatically

JPA:
Stands for Java Persistence API
It allows the application to interact with the database 

Data Access Layer:
This is the layer where all the reposiory classes reside

H2 Database:
It is an open-source relational database and it is written in Java

@Entity:
This makes the class into a table form in the database
@Id:
THis makes the property id unique

Lombok:
It is a dependency that used reduce the repetitive code 

Lombok Annotations:
@Getter and @Setter
@NoArgsConstructor:
@RequiredArgsConstructor:
@AllArgsConstructor:
@Data:
@Value:
@NonNull:
@Builder:
@Cleanup:

Validations
Validations in Spring Boot are all about ensuring the data your application receives meets certain criteria before its processed

Validation in Spring Boot:
@NotNull
@NotEmpty
@Size(min=x, max=y)
@Email
@Min(value) and @Max(value)