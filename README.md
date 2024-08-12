# Data-Modeling-SQL



Case 1
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



Case 2: 
There are many different driving schools, each school is described by a number (unique), a name and an
address. Each school has many instructors working for it, however each instructor only works for one school. Attributes
of instructor are instructor id (unique) and name.

Each instructor may have none, or may have many pupils at any particular time. Attributes of pupil are pupil id
(unique), name, address, and phone. A pupil has at least one, but may have different instructors assigned to
them at different times. An attribute of this instructor-pupil relationship is lesson date.

At the completion of their lessons, pupils may sit for a driving test. If they fail the test they may repeat it on
another date. The examiner who conducts the test is one of the instructors of the driving school.


Note: There is many to many relationship between Instructor and Pupils which is resolved by new join table Instructorpupil table, whcih contains the primary key from both table.


