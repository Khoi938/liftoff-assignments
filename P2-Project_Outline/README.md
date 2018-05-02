# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
A Web Application for school where Student/Parent can login and and view their Home Work assigment, Grade and Topic they are learning. Educator can upload materials and creates lesson plan for Classes. Including an Area where student can dicuss, shares, collaborate and ask question on thier Assigment.
The purpose is to provide ease of acess to school materials and learning lesson while promoting "team based" learning experience.

The idea came from FaceBook and other Social Media platform where student spent the bulk of thier internet time. 
If the same feature is available with the scope on Individual School and Eduction Topic learning will be an constant event instead of only in the class room or at the student's desk.

### Features
Student:
    Login - Will be able to create an Account with a profile page including user upload image.
    View - Student can view Syllabus, Weekly/Daily Topic and Assigment. Can also see Test and Quiz Grade.
    DownLoad - Can download Course Materials uploaded by instructor.

Teacher:
    Login - Will be able to create an Educator Account with a profile page including user upload image.
    View and Edit - Syllabus, Weekly/Daily Topic Assigment. List of Student and thier Test Grade.
    Edit Student - Add/Drop Student 
    Upload - Be able to upload Course materials.

Administrator:
    Login - Precreate Account
    Create Course - Create new Subject and Course
    Add Instructor - Ability to add Teacher(s)/TA to Course
### Technologies
    Python
    Django
    SQLAlchemy
    AWS:
        EC2 with Amazon Linux 
        S3 for course materials storage
        RDS MySQL for Users Account and Course information
        VPC Only allowed access to S3 and RDS if EC2 is making the Call

### What I'll Have to Learn
Django - From the beginning, including Sytax and Feature
AWS - How to deployed on the cloud using Amazon Web Service
BootStrap - Dress it up.