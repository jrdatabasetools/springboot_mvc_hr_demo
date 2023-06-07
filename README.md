# PL/SQL Connector Builder Example - Spring Boot MVC Demo using Oracle HR Demo Schema

This is a Master-Detail Demonstration written in Spring Boot MVC using the Oracle HR Demo Schema.

1. The Master-View works as a search dialog for employees.
2. The Detail-View allows editing or deleting of employees.

## Prerequisites

You need an Oracle Database (11g to 21c) with an Oracle HR Demo Schema containing employees and the depending tables and objects.

## Configuration

1. Configure the Database Setup in the Spring Boot configuration file 'application.yaml'.
2. Configure the Database Connection for the PL/SQL Connector Builder in the Maven 'pom.xml' or via the PL/SQL Connector Builder Plugin in the Connector Setup itself.

## Getting Started

mvn spring-boot:run

