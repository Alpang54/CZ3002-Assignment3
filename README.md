# CZ3002-Assignment2
Repository for assignment 2 of cz3002 course in NTU

Java Development Kit 8 or later.
Java 7
Apache Tomcat 8

MySQL statements to execute to create the database:

CREATE DATABASE login;

CREATE TABLE `accounts` (
  `username` varchar(45) NOT NULL,
  `password` varchar(45) NOT NULL,
  PRIMARY KEY (`username`,`password`)
);

