
<h1 align="center">
  <img src="https://user-images.githubusercontent.com/114346679/216282361-ea758c05-756a-48a0-8077-70b5a230f49c.png" width="250" height="166">
  <br>
  Project Name: Pulse Fit
</h1>

<div align="center">
   <strong>Pulse Fit</strong> - One stop destination for all your fitness needs<br>
  CoC Inheritance 2022 || Frontend Warriors <br> <br>

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
- [Major Roadblocks](#major-roadblocks)
- [Usage](#usage)
- [Team Members](#team-members)
- [Mentors](#mentors)
- [Screenshots](#screenshots)

</details>

## 📝Description

<table>
  <tr>
    <td>
      The <strong>Pulse-Fit</strong> is a one stop destination for all ypur fitness related needs
    <br>
    <h3>Access Level</h3>   
    The React based web app has one access level
    <h4>Key Features</h4>
    <p>
    <ul>
            <li><strong>BMI Calculator:</strong>The users can calculate their BMI and will get workouts and diet plans suggested according to their health requirement</li>
            <li><strong>Heart Disease Predictor:</strong> Predicts if your heart is healty or at risk of heart diseases</li>
            <li><strong>Find naerby Gyms:</strong> uses google maps API to suggest nearby gyms </li>
            <li><strong>Book Appointments:</strong>Allows users to book doctor's appointments</li>
            <li><strong>Community:</strong>Allows users to  share their experiences and build a community</li>
            <li><strong>E-com:</strong>Buy all FItness related products</li>
    </ul>
    </p>
    <h3>Business Potential</h3>
    <p>
    <ul>
    <li>The companies can sell their fitness realted products on the website</li>
    <li>Website can earn add revenue from putting up advertisements</li>
    </ul>
    </p>
  </td>
 </tr>
</table>

## 🔗Links

- [GitHub Repository](https://github.com/rohanfatehchandka/Inheritance)
- [Demo Video](https://drive.google.com/file/d/1bnKnUom8AqrgfPURdQmmXl5GzxgywENu/view?usp=sharing)
- [Drive Link to Screenshots of your project](https://drive.google.com/drive/folders/1hZTCHkw_yaMnJ_c1jsrRcVmwoz0eGZFA?usp=sharing)
- [Hosted Website Link](https://frontend-fw.vercel.app/)



Add any more links/resources you used for your project

## 🤖Tech-Stack

Mention all languages/libraries/frameworks used in your project **domain-wise**   
You can use icons too - find them [here](https://github.com/get-icon/geticon) 

- **Server:** ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white), ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)  ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
- **Client:**   ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)   ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)


## 📈Progress

 fully implemented features :

- [x] BMI calculator : will calculate the bmi of a person and will suggest videos and diet tips.
- [x] Heart Disease Predictor : taking some information about habits of the user our predictor can predit if the user's heart is healthy or at risk of heart disease in future
- [x] Book Doctor's appointment : user can pre-book Doctor's appointment.
- [x] Ecommerce : user can buy all fitness realted products here
- [x] Community : All users of the website can communicate with each other.
- [x] Map : To find nearby gyms 
- [x] Login & sign-up : secure login and sigh-up using jwt tokens
- [x] Contact us: The user can contact us using this feature.It sends automated E-mails

## 🔮Future Scope
- Additional access level: An additional acces level for the admin who can manage the website 
- Improving the accuracy of Heart Disease Predictor : Currently the accuracy of the model is 85%. Training the model to increase the accuracy
- Payment checkout for E-commerce part of the website

## 💸Applications
- Pulse Fit is capable to host products of many health-realted buisnesses in the E-com part of our website 
- It can earn add revenue from putting up advertisements
- Our website contains various features and we aim at meeting all the fitness related needs

## 🛠Project Setup

For the Web-App
1.Clone the GitHub repo
```bash
git clone https://github.com/Bruhbytes/Frontend-Warriors.git
```
2.Enter the client directory. Install all the required dependencies.
```bash
  cd frontend
  npm install
  npm start
```
3.To start the backend server:
```bash
  cd backend
  npm install
  npm run dev
```
## 🚧Major Roadblocks
1. material-ui has a peer dependency conflict with React  
   ```
   npm ERR! code ERESOLVE
   npm ERR! ERESOLVE unable to resolve dependency tree
   npm ERR! 
   npm ERR! While resolving: portfolio@0.1.0
   npm ERR! Found: react@17.0.1
   npm ERR! node_modules/react
   npm ERR!   react@"^17.0.1" from the root project
   npm ERR! 
   npm ERR! Could not resolve dependency:
   npm ERR! peer react@"^16.8.0" from @material-ui/core@4.11.0
   npm ERR! node_modules/@material-ui/core
   npm ERR!   @material-ui/core@"*" from the root project
   npm ERR! 
   npm ERR! Fix the upstream dependency conflict, or retry
   npm ERR! this command with --force, or --legacy-peer-deps
   npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
   npm ERR! 
   npm ERR! See /Users/jordanhilado/.npm/eresolve-report.txt for a full report.

   npm ERR! A complete log of this run can be found in:
   npm ERR!     /Users/jordanhilado/.npm/_logs/2020-10-31T17_57_54_724Z-debug.log
   ```
   Solution:
   ```
   npm install -f @material-ui/core
   ```

## 💻Usage

>Steps to run your project once its setup. 
- login/Sign-up: Login to the website using your credentials.If you are a new user u can sign-up using your e-mail id and set up a secure password (for ex. rohan@gmail.com ,password:Rohan@12345)
- All the features are listed on the navbar can be used
    <h4>BMI</h4>
    <p>
    <ul>
            <li>click the BMI tab on navbar you will be directed to a page where at the bottom you will find a button "Calculate BMI" click to find your BMI </li>
            <li>Fill the form and click submit</li>
            <li>Your BMI along with suggested diet plans and videos will be displayed  </li>
    </ul>
    </p>
    <h4>heart</h4>
    <p>
    <ul>
            <li>click the heart tab on navbar you will be directed to a form </li>
            <li>Fill the form and click submit</li>
            <li>Your heart health will be displayed  </li>
    </ul>
    </p>
    <h4>findNearbyGyms</h4>
    <p>
    <ul>
            <li>click the findNearbyGym tab on navbar you will be directed to a page </li>
            <li>click on the compass at the top </li>
            <li>Gyms nearby you will be visible on the map</li>
    </ul>
    </p>
    <h4>Community</h4>
    <p>
    <ul>
            <li>click the community tab on navbar you will be directed to the community page </li>
            <li>you will see messages from other users of our website</li>
            <li>To post on the community page you will see a box at the bottom type your message there and click submit </li>
    </ul>
    </p>
    <h4>Appointment</h4>
    <p>
    <ul>
            <li>click the Appointment tab on navbar you will be directed to a form </li>
            <li>fill in the details </li>
            <li>choose your slot</li>
            <li>you cannot book a slot for the next 24hrs if it is already booked by someone </li>  
            <li>slots get vacant everyday</li>
            <li>Thus, one can book a slot for the coming day only</li>       
    </ul>
    </p>
    <h4>Shop</h4>
    <p>
    <ul>
            <li>click the Shop on navbar you will be directed to our shop </li>
            <li> the prodiucts are divided into three categories :clothes,equipments and suppliments </li>
            <li> click on shop now on there you will be directed to pages thus products  are filtered </li>
            <li>below these categories you will see popular products</li>  
            <li>click on the middle icon of any product you wish to view ,which is visible on hovering over the product </li>
            <li>you can now see the product choose quantity of the product you wish to buy</li>
            <li>click on add to cart button</li>
            <li>On the top right corner you will see a cart icon click on it to view your cart</li>
            <li>Fill in your address and phone no. oh the right hand side of the page and click submit</li>
            <li>Your order is placed</li>
             
    </ul>
    </p>
    <h4>Contact Us</h4>
    <p>
    <ul>
            <li>click the contactus tab on navbar you will be directed to a form </li>
            <li>fill in the details </li>
            <li>we will recieve your feedback/message</li>
            <li>you will recieve a confirmation email</li>  

    </ul>
    </p>
 

## 👨‍💻Team Members

 - [Rohan Fatehchandka](https://github.com/rohanfatehchandka) : rvfatehchandka_b21@ce.vjti.ac.in
 - [Tanaya Shelke](https://github.com/tanayaa1) :  tsshelke_b21@ce.vjti.ac.in
 - [Om Doiphode](https://github.com/Om-Doiphode) :  oadoiphode_b21@ce.vjti.ac.in
 

## 👨‍🏫Mentors
 - [Harsh Nag](https://github.com/Jigsaw-23122002)
 - [Devansh Joshi](https://github.com/devdev29)

## 📱Screenshots
- Home page preview:
![home1 (1)](https://user-images.githubusercontent.com/114346679/216269707-9257cfa4-4386-40a9-be32-29beb8a72750.png)

- login/sign-up![login](https://user-images.githubusercontent.com/114346679/216272704-6d2777ec-95cd-4fe8-a2fc-fc4480737de3.png)


- Heart disease predictor

![predictor](https://user-images.githubusercontent.com/114346679/216271912-58bc2427-4aff-4381-937d-77fc00c561f7.png)

- BMI calculator ![bmi form](https://user-images.githubusercontent.com/114346679/216272038-101f7f19-047a-4d40-8410-552c69de313c.png)

- shop
![shop home and filters](https://user-images.githubusercontent.com/114346679/216272855-d87dd683-c683-4f82-910e-9bcee09fcd94.png)
![shop-cart](https://user-images.githubusercontent.com/114346679/216272879-0139ea81-e07e-4a37-ae79-a5fcf710fe7a.png)

- Appointment:![book Appointment](https://user-images.githubusercontent.com/114346679/216272984-b1fa20cc-9999-4c03-8b68-946ab04e1d91.png)

- find nearby gyms:
![Map](https://user-images.githubusercontent.com/114346679/216273178-308abca4-a359-4cda-9ac0-f9bcebc3479e.png)
- community:

![community page](https://user-images.githubusercontent.com/114346679/216273261-1b517192-35b3-4387-b6cc-5afc7874d6f4.png)
- contact us![contact us](https://user-images.githubusercontent.com/114346679/216273351-5a938f43-d27b-4e26-80ba-7bcfa0593589.png)

