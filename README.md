# Data-Modeling-SQL


Case 2: 
#Business rules relating to driving schools, instructors and pupils:

There are many different driving schools, each school is described by a number (unique), a name and an
address. Each school has many instructors working for it, however each instructor only works for one school. Attributes
of instructor are instructor id (unique) and name.

Each instructor may have none, or may have many pupils at any particular time. Attributes of pupil are pupil id
(unique), name, address, and phone. A pupil has at least one, but may have different instructors assigned to
them at different times. An attribute of this instructor-pupil relationship is lesson date.

At the completion of their lessons, pupils may sit for a driving test. If they fail the test they may repeat it on
another date. The examiner who conducts the test is one of the instructors of the driving school.


Note: There is many to many relationship between Instructor and Pupils which is resolved by new join table instructorPuils table, whcih contains the primary key from both table.


