# PL/SQL Connector Builder Example - Spring Boot MVC Demo

## Prerequisites

Run **run_oracle.sh** from the command line of the project root to start a preconfigured database. 

- An Oracle 21c XE (Express Edition) will be downloaded as Docker image.
- All Sql scripts in the folder **ora_db_startup** will be executed after startup.
- About 5 GB will be downloaded and require about 12 GB in the docker registry.

### Oracle Connection Info

- The default password for the administration users SYS, SYSTEM and PDBADMIN are set to 'oracle'.
- A preconfigured schema 'HR' identified by password 'hr' is created during setup.
- Url to the schema 'HR' is 'jdbc:oracle:thin:@localhost:1521/xepdb1'


## Master-Detail Demonstration
This is a Master-Detail Demonstration written in Spring Boot MVC using the Oracle HR Demo Schema.

1. The Master-View works as a search dialog for employees.
2. The Detail-View allows editing or deleting of employees.

## Getting Started

Use two command shells to run both commands.

- **run_oracle.sh** runs the preconfigured Oracle Database. 
- **mvn spring-boot:run** runs the PL/SQL Connector Builder, compiles the Spring-Boot-Application and starts the Spring-Boot-Application using the Oracle DB.

