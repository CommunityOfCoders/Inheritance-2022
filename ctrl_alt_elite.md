# Health-ID

<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance-2022">
    <img src="https://user-images.githubusercontent.com/103985810/216312683-4221cd84-d7bf-4a2c-8d13-aa42f630d147.png" alt="CoC Inheritance 2022">
   </a>

<div align="center">
   <br>This project aims to create a blockchain based database system for the peoples associated with the healthcare system. The most important objective was to keep the data of the patients secure and maintaining their privacy.
<br>
  CoC Inheritance 2022 || ctrl_alt_elite <br> <br>
</div>
<hr>

## Table of Contents
* [Introduction](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#introduction)
  * [About Health-ID](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#about-health-id)
  * [Tech-Stack](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#tech-stack)
  * [File Structure](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#file-structure)
* [Getting Started](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#getting-started)
  * [Pre-Requisites](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#pre-requisites)
  * [Installations](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#installations)
  * [Operating MySQL Tables](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#operating-mysql-tables)
  * [Usage](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#usage)
* [What we learned from this project](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#what-we-learned-from-this-project)
* [Future Scope](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#future-scope)
* [Contributors](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#contributors)
* [Mentors](https://github.com/KedarDhamankar/Health-ID/edit/main/README.md#mentors)
  

## Introduction
### About Health-ID
We have used the blockchain technology which we have implemented through Flask-Python on the server side. It also uses the MySQL database for storing the user, appointment, prescription details and theses uploaded from the research institutes. This website can be used by the Patients, Doctors, Researchers and Organizations such as the hospitals and research institutes. The blockchain service has been displayed on the website using HTML/CSS and Javascript. We have obtained a plethora of knowledge about Blockchain, MySQL and in general, database management systems.

### Tech-Stack
Frontend
1. HTML/CSS
2. Javascript

Backend
1. Python
2. APIs-Flask, Filestack
3. MySQL 
4. JSON

Code Editor
* Visual Studio Code

## Getting Started
### Pre-Requisites
* You must have the latest version of [Python3](https://www.python.org/downloads/).
* Since the website uses [Flask](https://pypi.org/project/Flask/), this framework should be present.
* You also have to install some modules such as passlib.hash, hashlib, wtforms, functool and sys if they are not already present in your system.
* To connect your flask with your MySQL database, you require the flask_mysqldb module.

### Installations
* Install Flask

`pip install flask`

`pip install flask-mysqldb`

`pip install passlib`

* Install wtforms

`pip install wtforms`

* Install [MySQL](https://www.mysql.com/downloads/)

* Install [Filestack](https://www.filestack.com/docs/api/sdk/python/)

`pip install --upgrade filestack-python`

### Operating MYSQL tables
Open your MYSQL Command Line Client or enter the following command in your command prompt
`mysql -u root -p`
On doing this, it would ask you for your password.

`CREATE DATABASE healthid;`

`USE healthid`

You would recieve the message that the database has been changed.

### Usage
We hope that you already have git installed in your system.

1. Clone our Git repository
`git clone https://github.com/KedarDhamankar/Health-ID.git`

2. Move into the directory
`cd .../Health-ID`

3. Run the app.py python file
`python app.py`

4. Run the app.py file with 2 different port numbers:

`python app.py 5000`

`python app.py 5001`

![ports_edited](https://user-images.githubusercontent.com/103985810/216396895-1d89e4c5-71fa-4a6b-af54-9d47d8e9f32a.png)

As shown here, the users can register through 2 different ports and thus, two different accounts would be created. For more users to be added, new tables will have to be linked and added in the app.py file.

## Important Links
GitHub Repository: [Health-ID](https://github.com/KedarDhamankar/Health-ID)

Google Drive: [Health-ID_media](https://drive.google.com/drive/folders/1F7z-bLzj19IVpKnTMOuB2iTgU4BdQ5y7?usp=sharing)

## What we learned from this project
* Rucha Patil-"Learnt front-end web development in HTML/CSS and Javascript framework and on a basic level the integration of front-end with back-end using flask and basics of database management using MySQL. Also got a glimpse of the functionality and implementation of a blockchain."

* Kedar Dhamankar- "In the past 4 months, I have learnt what a blockchain is and how it functions and how to implement it through code. Also learnt the framework Flask which helped in creating the backend of the website and linking it to the front end"

* Yash Singavi- "Learnt about basic to mediocre concepts of front-end web development such as resizing the components in various pages as per requirement. Eg: various position aspects. In future prospects will learn and try to implement the responsiveness in the website, so that the interface remains smooth and uniform throughout different screen sizes."

* Komal Sambhus- "These 3 months have been filled with a lot of excitement, that came with building my very first website. I learned about the usage of MySQL tables and their backend implementation through Flask. I was also introduced to the basics of front-end development. I am looking forward to taking these lessons forward."

## Future Scope
* Catalouging previous health records of the patient.
* More functionality for the Doctor user.
* Search Engine function for theses and research papers.
* Maintaining digital records of the Organisation user.
* Increasing security.
* GPU support for data mining.

## Contributors
* [Rucha Patil](https://github.com/Ruchapatil03)
* [Kedar Dhamankar](https://github.com/KedarDhamankar)
* [Yash Singavi](https://github.com/YashSingavi)
* [Komal Sambhus](https://github.com/Komal0103)

## Mentors
We are extremely grateful to our mentors for encouraging and guiding us throughout this project
* [Arnav Zutshi](https://github.com/AsRaNi1)
* [Abhishek Gupta](https://github.com/Abhishekohm)
