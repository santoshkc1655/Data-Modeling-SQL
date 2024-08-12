# Data Modeling and SQL in Relational Database Design for Analytics
Data Modeling in analysis is the process of creating a visual representation, abstraction of data structures, relationships, and rules within a system or organization. The main objective of data modeling is to provide a <ins>precise and well organized framework for data organization and representation, since it enables efficent analysis and decision making</ins>. Analyst can discover trends, understand the connection between various items, and make sure that data is efficiently and accurately stored by building models.



## There are three levels of data models involved in the data modelling process; 
1.Conceptual Data Model: Represents data by exploring and detailing abstract, high-level business concepts and structures in depth.

2.Logical Data Model: In the logical data model, the conceptual model is further developed by providing a detailed representation of the data at a logical level. It defines the tables, columns, relationships, and constraints that form the data structure.  

3.Physical Data Model: In the Physical Data Model, the implementation is described in the context of a specific database system. It details all components and services required to build the database, including queries and the database language used for its creation.   

----

**ER-Model:** The Entity-Relationship Model (ER model) is a high-level relational model used to define the data elements and relationships between entities within a system. This conceptual design provides a clearer, more comprehensible view of the data. The entire database is represented in an Entity-Relationship Diagram (ERD), which consists of entities, attributes, and relationships.

In this model, a relationship between entities is referred to as an association. These associations can be characterized by mapping cardinalities such as:

One-to-one
One-to-many
Many-to-one
Many-to-many
Additionally, relationships can be classified as either mandatory or optional. In a mandatory relationship, an entity is required to participate in the association, whereas in an optional relationship, the entity's participation is not necessary.

____

*Case 1*
A real estate company operates a number of sales offices. Each sales office is identified by the following
attributes Office Number, Address and Phone number.
Each sales office is assigned one or more employees and an employee may work from many different sales
offices. An employee is identified by the following attributes Employee number, Employee name, and
Employee address.
A sales office is managed by one appointed employee and an individual employee may manage many sales
offices.
Each sales office has a list of one or more properties for sale. Attributes of property include Property number
and Property address.
Each individual property can only be listed with one sales office.
Each individual property may have one or more owners. Attributes of owner are Owner number, Owner name
and Owner address. An owner may own one or more properties.
For each property that an owner owns the percentage of ownership must be recorded and stored in a attribute
called OwnerPercentage


*Case 2:* 
There are many different driving schools, each school is described by a number (unique), a name and an
address. Each school has many instructors working for it, however each instructor only works for one school. Attributes
of instructor are instructor id (unique) and name.

Each instructor may have none, or may have many pupils at any particular time. Attributes of pupil are pupil id
(unique), name, address, and phone. A pupil has at least one, but may have different instructors assigned to
them at different times. An attribute of this instructor-pupil relationship is lesson date.

At the completion of their lessons, pupils may sit for a driving test. If they fail the test they may repeat it on
another date. The examiner who conducts the test is one of the instructors of the driving school.


*Case 3:*

Use the following business rules to create a Crow’s Foot ERD and give RDM for each
entity in your ERD.
A department employs many employees, but each employee is employed by one department.  

Some employees, known as “rovers,” are not assigned to any department.  

A division operates many departments, but each department is operated by one division.  

An employee may be assigned many projects, and a project may have many employees
assigned to it. A project must have at least one employee assigned to it.  

One of the employees manages each department, and each department is managed by only
one employee.  

One of the employees runs each division, and each division is run by only one employee.



**My Learnings:**
- Data modeling concepts
- Entity-Relationship Diagrams (ERD) including entities, attributes, relationships, cardinality, and participation
- Solving many to many relationship between entities
- Business rule implementation
- Relational database design
- Crow's Foot notation
