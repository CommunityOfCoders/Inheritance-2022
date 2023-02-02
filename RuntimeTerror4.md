<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance-2022">
    <img src="https://res.cloudinary.com/dn6vz8exv/image/upload/v1665664791/inh_zzefoy.jpg" alt="CoC Inheritance 2022" width="500" height="166">
  </a>
  <br>
  VJTI Hostel
</h1>

<div align="center">
   <strong>VJTI Hostel</strong> This website bridges the gap between hostellites and hostel authorities in every possible way.<br>
  CoC Inheritance 2022 || Runtime Terror(4)<br> <br>
</div>
<hr>

<details>
<summary>Table of Contents</summary>

- [Description](#description)
- [Links](#links)
- [Tech Stack](#tech-stack)
- [Progress](#progress)
- [Future Scope](#future-scope)
- [Applications](#applications)
- [Project Setup](#project-setup)
- [Usage](#usage)
- [Team Members](#team-members)
- [Mentors](#mentors)
- [Screenshots](#screenshots)

</details>

## 📝Description

- VJTI Hostel website deals with the problems on managing a hostel and avoids the problems which occur when work is carried manually. 
- Identification of the drawbacks of the existing system leads to the designing of computerized system that will be compatible to the existing system with the system Which is more user friendly and more GUI oriented. 
- Student/User can login and view details like events and submit complaints, and book hostel easily. Admin can add/manage rooms, courses, students and many more.

## 🔗Links

- Github link - [GitHub](https://github.com/AsmitaRaina/CoC_Hackathon.git)
- Demo Video - [DemoVideo](https://drive.google.com/file/d/1EKbS3PL5zTW0nI_igQ5THjNGaFH5QJuC/view?usp=sharing)
- Screenshots - [Screenshots](https://drive.google.com/drive/folders/1_PRda6ceWsLrk4S5O_WOdOPz1LJ0dRPb?usp=share_link)

## 🤖Tech-Stack

Mention all languages/libraries/frameworks used in your project **domain-wise**   
You can use icons too - find them [here](https://github.com/get-icon/geticon) 

#### Front-end
- ReactJS
- Material UI
- HTML
- CSS
- JavaScript

#### Back-end
- NodeJS
- ExpressJS
- Nodemon

#### Database
- PostgresSQL


## 📈Progress

Fully implemented - 

- Adding student details through and viewing it in a table on the same page (using db.json file and not database for the time being). For future scope, details would be added only from the admin side and viewing them would be done from the student/user side.
- Adding an upcoming hostel event and viewing them in another page. For future scope, adding event should be done only from the admin side and viewing should be done from the student/user side.
- Adding complaints of any sort and viewing them. For future scope, adding complaint should be done only from the student/user side and viewing should be done from the admin side.

Partially implemented - 

- Login/Signup - For the registration part, the details are being fetched from the site and added to the sql table. However, the toast which should be displayed on the site for successful/unsuccessful registration is not being shown. Also after logging in it's not redirecting it to the homepage.
- Roll based authorization
- Creating tables in database for student details, complaints, events.

## 🔮Future Scope

Future Scope - 

- We can keep the track of vacant seats in each room by using database of room number corresponding to each student. Each room can have only three people. This data can be used during room allocation for freshers.
- A segment for frequently asked questions can be added so that doubts regading various facilities and procedures can be resolved efficiently.

## 💸Applications

>The real-world problem which we can associate with our project can be the management of hostels in difference colleges e.g VJTI college hostel.
>It is inefficient and time taking to carry out several processes like hostel allotment processes, putting up a notice or an event brochure etc. that's why digitization of these processes through website can help us save time.

## 🛠Project Setup

>Frontend
- npm install
- npm start
>Backend 
- cd server 
- node index.js (provided nodemon is already installed)
>For db.json
- npx json-server --watch src/data/db.json --port 8000

## 💻Usage

- After we run the project through the client side, we are greeted by the homepage of our website. At the top there is a navigation bar consisting of Home, Events, Blocks, Contact, SignUp.
- After a new registration, it directs us to the login page and after login it directs us to the admin dashboard.
- In the URL, when we pass the /sidebar route, it redirects us to the admin page dashboard. In the sidebar, there is event, student, viewComplaints.
- Clicking on event, it will take us to the page where the admin can fill up the details of an upcoming event, which on submitting will view the events. Clicking on a particular event, will show us the details of the event on a new page. Similary viewComplaints will redirect to a page with a list of complaints wherein after clicking on a particular complaint, we can delete that once that issue is resolved.
- Students will redirect us to a form where admin fills the student details and them submits them, also giving an option of add,edit and delete.
- In the URL, when we pass the /sidebar2 route, it redirects us to the student/user dashboard, where, in Rules and regulation, there are the hostel rules mentioned on the page. 
- In the addComplaint section, student/user is given a form where they need to fill the details of the complaint and then submit it, after which all the complaints are listed on another page and viewed by the admin.
- Blocks tab has information and images about Block A and Block E.
- ContactUs tab has mail and contact info of hostel authorities.

## 👨‍💻Team Members

Team members, Github accounts and Mail ID.

- Devayani - [GitHub](https://github.com/),  drchandane_b21@ce.vjti.ac.in
- Asmita - [GitHub](https://github.com/AsmitaRaina), araina_b21@it.vjti.ac.in
- Nikhita - [GitHub](https://github.com/Nikhghar), nrgharpure_b21@it.vjti.ac.in
- Ruchi - [GitHub](https://github.com/Ruchi-Mankar), rdmankar@ce.vjti.ac.in

## 👨‍🏫Mentors

Sarvagnya Purohit
- [GitHub](https://github.com/saRvaGnya)

## 📱Screenshots

![Screenshot alt text](https://res.cloudinary.com/dyxnmjtrg/image/upload/v1675356320/Home_rcybu4.png )

![Screenshot alt text](https://res.cloudinary.com/dyxnmjtrg/image/upload/v1675356979/WhatsApp_Image_2023-02-02_at_10.24.09_PM_1_mi9il4.jpg)
![Screenshot alt text](https://res.cloudinary.com/dyxnmjtrg/image/upload/v1675356501/WhatsApp_Image_2023-02-02_at_10.15.49_PM_bchjnv.jpg)
![Screenshot alt text](https://res.cloudinary.com/dyxnmjtrg/image/upload/v1675356630/WhatsApp_Image_2023-02-02_at_10.16.15_PM_v0loda.jpg)