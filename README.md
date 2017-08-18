college-drive
===================
This is a project to put into practice the knowledge of web applications

Description
-------------
The project is a platform where students can store documents used in classes to share with others.

Features
-------------
> Student
> * Create/Delete/Edit your his account
> * Choose your college
> * Send a document to a discipline linked to his college
> * Send a document anonymously
> * Delete a sent document
> * Comment on a document
> * Approve/disapprove a document
> * Request a new discipline

> Administrator
> * Create/Delete/Edit a college
> * Create/Delete/Edit a discipline
> * Approve/disapprove a new discipline


Business Rules
-------------
* A document that receives more than 30 disapprovals must be disabled
* A student can only view documents linked to his college
* A student must be over 18

Structure
-------------
> College
> * description
> * initials

> Discipline
> * description
> * college

> Tag
> * description 

> Document
> * discipline
> * description
> * file(image/doc/pdf)
> * reputation(approves/disapproves)
> * anonymous(bool)
> * student
> * author
> * comments
> * tags

> Student
> * name
> * photo
> * age
> * email
> * college


View
-------------
* Profile Page - infos of user
* College Page - list all disciplines in the college
* Discipline Page - list all documents in the discipline 
* Search Page - search a discipline in the college and/or tag


Tools
-------------
> Backend
> * Ruby (Ruby on Rails)

> Frontend
> * HTML 5
> * CSS 3 (Bootstrap)
> * JavaScript (JQuery)

> Database
> * Postgree SQL

> Server
> * Heroku (Host and Database)
> * Google Cloud Plataform (Storage)



