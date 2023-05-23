# Bowman_car_hire_finished
Level 3 Creating an object oriented computer program using C# (7540-039)

Candidate instructions:

This assignment is made up of two tasks:
 Task A - Design and create software from a given design specification
  [In this task you are required to design and create software to access an external database (Hire) 
with a single table via a database connection and a data form.]
 Task B - Test and document the software
  [Create test data and expected results to test the Update, Add, Delete, Cancel and 
Search buttons on the frmCars form and the Run button on the frmSearch form.]

Scenario
You work as a programmer for OmegaSolutions who develop software for clients. You have been asked to design, create and test the software to access an external database.
The interface to the database must enable the user to do the following:

 display individual records
 add a new record
 delete a record
 edit a record
 update a record
 cancel amendments for a record
 search records.

A database already exists named Hire containing a table tblCar which contains car details. The table tblCar contains the following fields:
Field Name                      Data Type                         Field Length
VehicleRegNo(Primary Key)       Text                              10
Make                            Text                              50
EngineSize                      Text                              10
DateRegistered                  Date                              dd/mm/yyyy
RentalPerDay                    Currency, 2 decimal places
Available                       Logical (Yes/No)                  1

The VehicleRegNo field is a primary key and there cannot be duplicate entries in this field and a zero-length entry is not allowed.
