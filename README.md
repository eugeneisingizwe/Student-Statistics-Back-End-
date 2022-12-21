# Student-Statistics-Back-End-
In this project I am adding aggregate methods to a Student controller to show a student's overall grade and the number of students.

I am starting  with an existing codebase for a mostly complete application.

I will be adding aggregate methods to the `Student` controller to show a student's overall grade and the number of students.

Finally, I am spent the remaining time deploying the application using MongoDB Atlas and Heroku.

## Installation 

## Usuage

```npm start```

## User Story


* As a user, I want to be able to view all the students and get a total of the number of students enrolled.

* As a user, I want to be able to view a specific student's overall grade in the class using MongoDB operators and their score on each assignment.

* As a user, I want to be able to execute create, read, update, and delete operations on `courses`, `students`, and `assignments`.

### Acceptance Criteria


* The application must make use of a MongoDB database, the Mongoose ODM, and Express.js.

* The database must be seeded with sample data.

* The `Student` controller should have a `headCount` aggregate function to get the total number of students by making use of MongoDB aggregate operators.

* The `Student` controller should have a `grade` aggregate function that returns a single student and also the student's overall grade using MongoDB aggregate operators.

* The project will require research of MongoDB operators such as `$addToSet`, `$unwind`, `$group`, `$match`, and `$avg`.

* `Student` lookup will require use of the `ObjectId()` method.

* The endpoints `api/students/<student id>` and `api/students/` should be tested using Insomnia to ensure that the aggregate functions return the student's overall grade and headcount respectively.

* This back-end application should be deployed using Heroku and MongoDB Atlas. Refer to the resources below for further instructions.


---
© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.

