# JPA1
Object Relational Mapping with JPA exam prep
### Describe how you have handled persistence in the last three semesters. The considerations should include all relevant layers. File IO, Relational Databases, local storage and cookies in browsers.
Med JDBC, rene Servletter og JSP. 
### Explain the rationale behind the topic Object Relational Mapping and the Pros and Cons in using a ORM
Det er for at gemme objekter som relationelle entiteter i en database.<br>
Pros: Mindre skreven kode, intet JDBC/SQL kode, Objekt orienteret ”model”/paradigme.<br>
Cons: Low level er uklar, ikke optimalt designet for databaser, svært at mappe et objekt til en relationel database.
### Explain the JPA strategy for handling Object Relational Mapping and important classes/annotations involved.
Entities klasser, @Entity, @id, @Column @ManyToOne… EntityManager, Persistence
### Outline some of the fundamental differences in Database handling using plain JDBC versus JPA
Med jdbc skal du skrive sql, med JPA gør API’et og frameworket det. 
