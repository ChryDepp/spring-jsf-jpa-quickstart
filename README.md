Spring + JSF + JPA Quickstart
=============================

- Version 1.0.3.GA

- What it is: a quickstart project containing initial structure to:
  - Spring Context 4.x as JEE context provider;
  - Jetty 9.2.x as Webserver;
  - Mojarra JavaServer Faces 2.2.x as JSF implementation;
  - Primefaces 5.x as JSF components library;
  - Built-in MySQL Server connection for JDBC/JPA (extensible to ANY database - add specific JDBC drivers to POM if needed);
    - Oracle;
    - PostgreSQL;
    - Microsoft SQL Server;
    - Informix;
    - H2;
    - Derby;
    - and many more...
  - Hibernate 4.x as JPA 2.2 provider (switchable to EclipseLink if convenient - see web.xml).

- To run:
  - Checkout using Git or SVN;
  - Configure properties over ```src/main/webapp/WEB-INF/database```;
  - Run using Maven 3.x ```mvn clean jetty:run```;
