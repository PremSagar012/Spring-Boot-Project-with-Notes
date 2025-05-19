This document outlines the core concepts related to databases, DBMS, SQL, ORM, JPA, and Spring Boot validations, including annotations and dependencies like Lombok.

🔹 Database
A database is a structured repository where data related to your application—such as users and products—is stored and managed.

Types of Databases
Relational (e.g., MySQL, PostgreSQL)

Non-Relational (e.g., MongoDB, Cassandra)

🔹 DBMS (Database Management System)
A DBMS is an interface between the user and the database, used to manage, retrieve, and manipulate data.

Common DBMS Examples:
MySQL

Oracle Database

SQL Server

MongoDB

Cassandra

🔹 Key DBMS Terminologies
Table: Organizes data in a structured format (rows and columns).

Column: Represents a property/attribute of the table.

Row (Tuple/Record): A single record in a table.

🔹 SQL (Structured Query Language)
Used to retrieve, manage, and update data in a relational database.

Enables interaction with the database using statements like SELECT, INSERT, UPDATE, DELETE, etc.

🔹 ORM (Object-Relational Mapping)
Converts classes into tables automatically.

Attributes in the class are mapped to columns in the table.

Developers do not need to manually write SQL queries for table creation.

🔹 JPA (Java Persistence API)
An interface specification for accessing, persisting, and managing data between Java objects and a relational database.

Allows seamless interaction with the database through object-oriented code.

🔹 Data Access Layer
Contains all the repository classes.

Acts as the medium between the service layer and the database.

🔹 H2 Database
An open-source, in-memory relational database.

Written in Java.

Commonly used for testing and development purposes in Spring Boot applications.

🔹 JPA Annotations
@Entity → Maps a class to a table.

@Id → Marks the primary key (unique identifier) of a table.

🔹 Lombok
Lombok is a Java library used to reduce boilerplate code in your applications.

Common Lombok Annotations:
@Getter / @Setter – Generates getters and setters automatically.

@NoArgsConstructor – Generates a no-argument constructor.

@RequiredArgsConstructor – Generates a constructor with required arguments.

@AllArgsConstructor – Generates a constructor with all class fields.

@Data – Shortcut for @Getter, @Setter, @ToString, @EqualsAndHashCode, and @RequiredArgsConstructor.

@Value – Used for immutable classes.

@NonNull – Ensures that the field is not null during object creation.

@Builder – Provides the Builder pattern for object creation.

@Cleanup – Ensures a resource is cleaned up automatically.

🔹 Validation in Spring Boot
Validations help ensure the integrity and correctness of user input before processing.

Common Spring Boot Validation Annotations:
@NotNull – Field must not be null.

@NotEmpty – Field must not be null or empty.

@Size(min = x, max = y) – Ensures the field length is within bounds.

@Email – Ensures the field contains a valid email format.

@Min(value) / @Max(value) – Sets numeric lower and upper bounds.