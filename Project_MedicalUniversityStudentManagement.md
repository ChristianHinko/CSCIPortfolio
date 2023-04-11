[Back to Portfolio](./)

# Medical University Student Management

**Class:** Systems Analysis & Software Design (CSCI 495)

**Grade:** A

**Language(s):** C#, T-SQL, HTML, CSS

**Source Code Repository:** [ChristianHinko/MedicalUniversityStudentManagement](https://github.com/ChristianHinko/MedicalUniversityStudentManagement)

(Please [email me](mailto:cthinkle9@csustudent.net?subject=GitHub%20Access) to request access.)

## Project Description

The Medical University Student Management (MUSM) system is designed to allow students to easily submit documents to their advisors. This system provides a centralized location for both staff and student to submit documents and information making the registration process streamlined and hassle-free.

## Design

MUSMWebApplication: Website for various operations regarding Medical University Student Management. Admins have the ability to assign required artifacts, staff have the ability to submit and checkoff artifacts, students have the ability to submit artifacts.

MUSMModelsLibrary: Class equivalents for database data. Dapper (our project's open-source ORM) will direct database data into these classes.

MUSMDataTools: Database schema. The database we are using will structure itself around this project.

MUSMDataLibrary: Class library making database communication from C# simple

MUSMDatabaseServicesAPI: The Web API that uses the Data Library to access the database.

[Back to Portfolio](./)
