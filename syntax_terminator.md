<h1 align="center">
  <img src="https://user-images.githubusercontent.com/116101909/216388090-19e5fb93-b902-4943-8578-4276ad7b5eb8.png">
  <br>
</h1>

<div align="center">
   <strong>Comparazon</strong> - A price comparison website for mobile phones
  <br>
  CoC Inheritance 2022 || Syntax Terminators 
  <br>
 <br>
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
<div align="center">
  <table>
    <tr>
      <td>

- Comparazon is an open-source project aimed at scraping data from e-commerce websites like Amazon and Flipkart. It is designed to be used for price comparison and product research and is built with the Scrapy framework and Python.

- The Scrapy framework, which is a powerful and versatile web crawling framework specifically designed for web scraping and data extraction, is at the heart of the project. The Python programming language is used to build the project, which is well-known for its simplicity, flexibility, and scalability.

- Comparazon's mission is to provide users with a website for comparing data from e-commerce websites quickly and easily. The project is intended for a variety of uses, including price comparison and product research, both of which mean a lot to an ecommerce consumer.
      </td>
    </tr>
  </table>
</div>

## 🔗Links

- [GitHub Repository](https://github.com/ShauryaSwarup/Syntax_Terminators)
- [Demo Video and Screenshots](https://drive.google.com/drive/folders/1HYFNCMZ5OK5kjx4IGP9QaDDi4yMoiiqh?usp=sharing)

## 🤖Tech-Stack
<div>
  <table>
    <tr>
      <td>

#### Front-end

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=ffffff)
![MUI](https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://camo.githubusercontent.com/5d16e7fdd964ebca50ca82d6c8b081045630340427c463f4470050acd4e50ef3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d5461696c77696e642b43535326636f6c6f723d323232323232266c6f676f3d5461696c77696e642b435353266c6f676f436f6c6f723d303642364434266c6162656c3d)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


#### Back-end

![Nodejs](https://img.shields.io/badge/-Nodejs-339933?style=flat-square&logo=Node.js&logoColor=ffffff)
![Express](https://img.shields.io/badge/express.js-%23404d59.svg?style=flat-square&logo=express&logoColor=%2361DAFB)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

#### Database
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat-square&logo=mongodb&logoColor=white)

#### Scraping

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
<img src="https://camo.githubusercontent.com/40d00cefb120a829517e503658aaf6c987d5f9cc6be5e2e35fb20bd63bdbceb5/68747470733a2f2f7363726170792e6f72672f696d672f7363726170796c6f676f2e706e67" width="100" height="30">
<img src="https://avatars.githubusercontent.com/u/85173056?s=200&v=4" height="35" width="35">
<img src="https://pbs.twimg.com/profile_images/1574710094872412160/yRJ5Coye_400x400.png" height="35" width="35">
<img src="https://avatars.githubusercontent.com/u/2810941?s=200&v=4" width="35" height="35">
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white)
![JSON](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
    <br>
      </td>
    </tr>
  </table>
</div>

## 📈Progress

#### Web Dev
- [x] Secure authentication for users to access the website.
- [x] Authorization system to manage user access.
- [x] Efficient rendering and fetching of mobile phones data from the MongoDB database.
- [x] Automated database update process through hourly scraping script.
- [x] User-friendly "Add to Favorites" feature for quick access.
- [x] Advanced filtering capabilities for better user experience.
- [x] Intuitive search feature to find desired content.
- [x] Comparison of the best deals from Amazon and Flipkart e-commerce websites.

#### Scraping
- [x] Scraping around 300 phones in a matter of seconds
- [x] Using that as a database scraping those products on Flipkart
- [x] Updating the remote database
- [x] Scraper runs every hour on a Google Cloud Platform Virtual Instance via a cronjob
- [x] Can Monitor the Scraping Jobs via a dashboard service
- [x] Implemented rotating proxies to avoid blocking of the spider
- [x] Can also use Selenium to scrape dynamic websites 

## 🔮Future Scope
<div align="center">
  <table>
    <tr>
      <td>
        <br>

- Extension for price comparison by checking the product opened in the user's browser
- Sending notifications to user if price drop on favorite items
- Scrape more ecommerce websites
- Scrape more categories and check for data errors if any
        <br>
      </td>
    </tr>
  </table>
</div>
## 💸Applications
<div align="center">
  <table>
    <tr>
      <td>
        <br>
        
- Comparazon is an open-source project that provides a cutting-edge solution for data collection from e-commerce websites like Amazon and Flipkart. The Scrapy framework and Python programming language are used to build the project, which provides an easy-to-use API service to access the data scraped from these websites. The scraped data can be exported in json format, allowing users to use and analyse the data in their preferred format.
- Comparazon provides e-commerce researchers, data analysts, and businesses with a powerful tool for collecting data from e-commerce websites in real-time. This enables them to make informed decisions about which products to buy and at what price, optimising their e-commerce strategy and increasing profits. The project intends to scrape and crawl data from more e-commerce websites in the future, as well as expand its capabilities to include more product categories such as laptops, accessories, footwear, and so on.
- Comparazon has an easy-to-use user interface that allows users to interact with the collected data. The website is designed to be user-friendly and to allow users to access and analyse data in a meaningful way. This allows them to identify trends quickly, compare prices, and make informed purchasing decisions. Users can use Comparazon to take control of their e-commerce strategy and make the most of data collected from e-commerce websites.
        <br>      
      </td>
    </tr>
  </table>
</div>

## 🛠Project Setup

1. Clone the repository
```
https://github.com/stealth-bombeer/Hostel-Management-Portal.git
```
To start the frontend user interface
```
cd frontend
npm install
npm start
```
To start the backend server
```
cd backend
npm install
nodemon index.js
```

## 📱Screenshots
#### Home Page
![SS2](https://user-images.githubusercontent.com/116101909/216410916-33d5ddc2-b99e-4419-bfb5-ae4840f2518c.png)
#### Product Page
![SS1](https://user-images.githubusercontent.com/116101909/216410928-f2d3068c-5e4e-432b-9b0f-a28ca0375756.png)
#### Registeration Page
![SS4](https://user-images.githubusercontent.com/116101909/216410945-e56b36aa-2d74-4d16-9019-73f7860ea2c1.png)
#### Login Page
![SS3](https://user-images.githubusercontent.com/116101909/216410966-0dbdec98-0a62-4a1e-a011-14448583a362.png)
#### Search Page with Pagination
![SS7](https://user-images.githubusercontent.com/116101909/216410986-fabea37a-96da-4d39-bfe1-d89f081b0a3e.png)
#### Favorites Page
![SS6](https://user-images.githubusercontent.com/116101909/216410996-03ebffe7-db01-4e07-87ad-0753a9300a54.png)
![Screenshot from 2023-02-02 23-37-26](https://user-images.githubusercontent.com/116101909/216409040-78551a56-f27a-49a4-bb0e-f1389841bb26.png)
#### Profile Page
![SS5](https://user-images.githubusercontent.com/116101909/216411778-cd647bcf-a3d8-49a9-af95-80ef84e1eb16.png)

#### Link to more screenshots for scraper and also website walkthrough
[Syntax Terminators Drive Link](https://drive.google.com/drive/folders/1HYFNCMZ5OK5kjx4IGP9QaDDi4yMoiiqh?usp=sharing)

## 👨‍💻Team Members

- [Shaurya](https://github.com/shauryaswarup) Email: srswarup_b21@ce.vjti.ac.in
- [Narayani](https://github.com/narayanibokde9) Email: nbokde_b21@ce.vjti.ac.in

## 👨‍🏫Mentors

- [Ankit Sharma](https://github.com/](https://github.com/AnkittSharmaa)
- [Nirbhay Hanjura](https://github.com/](https://github.com/botnirbhay)
