<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance-2022">
    <img src="https://i.imgur.com/GNPngUw.png" alt="CoC Inheritance 2022" width="500" height="166">
  </a>
  <br>
  No-Code DL
</h1>

<div align="center">
   <strong>No-Code DL</strong> - A no-code tool for users as well as developers to collaborate and  build deep learning models using drag and drop functionality.

**COC - Inheritance || minimum-spanning-three** <br> <br>
<!--   Add any <a href="https://shields.io/">Shields</a> here -->
![stars](https://img.shields.io/github/stars/sameergupta4873/no-code-DL?style=social)
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



---


## 🔗Links

- [GitHub Repository](https://github.com/sameergupta4873/no-code-DL)
- [Demo Video](https://drive.google.com/drive/folders/1nTdGLqMaLw5w6jy9hSQVxU4aLwmL2aD1)
- [Drive Link to Screenshots of your project](https://drive.google.com/drive/folders/1uDzJL7eXIvwrKsvx8wim04i3tAQi_hn7)
- [Hosted Website Link](https://github.com/sameergupta4873/no-code-DL)
- [Hosted Backend Link](https://github.com/sameergupta4873/no-code-DL)


---


## 📝Description

Deep Learning **frameworks** have speeded up the model development process by abstracting away the underlying implementations and providing a **high level API**. However it still requires one to have a foundational knowledge in DL and a good **programming experience** to use those APIs for developing models. We **solve this** by providing a user-friendly webapp, where users with little or no programming exeprience can develop models for Standard **Neural Network**, Convolutional Nueral Networks as well as Recurrent Neural Networks. The user **choses the model architecture using a drag and drop functionality**, developing a network/graph of how different layers are interconnected, our server processes this information and **generates equivalent PyTorch** code for the model and puts the model on training.  The user gets back the **model code, inference code and the trained model**.

We have also **integrated a collaboration system** for a group of people to work together on a project, a version control system type mechanism to keep track of how different architecture perform by making and keeping a record of all the commits.


- Users with **no deep learning** or programming **experience** can quickly develop models of their choice to solve their problems
- An **automation tool for developers** to quickly try out different model architectures and chose the best one instead of starting from scratch on each try.
- **Collaboration feature** to allow a group of people to work together on a project and design the best architecture.


---


## 🤖Tech-Stack


#### Front-end
- ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
- ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) 

#### Back-end

- ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
- ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
- ![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
- ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

#### Database
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

#### DL Framework

- ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
- ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)



---


## 📈Progress

- [x] Support drag and drop functionality for NN, CNN, RNN
- [x] Develop a collaboration system for multiple users to work on a project.
- [x] Provide model code, infernce code and the trained model
- [ ] provide little information about what each layer does for unfamiliar people



---

## 🔮Future Scope

- **Advanced/SOTA models** : Allowing complex sequence netowrks such as **rnn-encoder cnn-decoder, transformers**, generative networks such as **GANs, diffusion models** to be developed on our webapp. This will require **refactoring** the current code-gen technique and defining functors to handle each possible block of the network. Also develop a **common endpoint** to allow layers from cnn,rnn and snn so users have more customizability.
- **Inferring user's problem** : Instead of just giving them an interface to develop a model, we could them an **interface to describe the problem they're facing**, and generate recommendation about what type and architecture of model they should proceed with. This can be achieved by training a **miny language model** on existing models data with a **'problem description - model architecture used'** labels.


---

## 💸Applications

This can be used anywhere Deep Learning models can be of value. The main objective is, its not limited to people with a lot of Deep Learninig experienc or proficiency in programming. It can be used by anyone, as it abstracts the code writing part.

We can **monetize** this providing **trained model to subscribed users**. Training custom models is heavy computational taks and requires alot of infrastructure to be setup. The **code generation** part will be **accessible to anyone**.


---


## 🛠Project Setup

Start by cloning the repo
> `git clone https://github.com/sameergupta4873/no-code-DL/tree/master`

Setup the flask server
> #requires [cuda capable devices](https://developer.nvidia.com/cuda-gpus)
>
>`cd flask_server`
>
> #have [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) installed
> 
>#create environment with required dependencies
>
>`conda env create -f environment.yml`
>
>#switch environment
>
>`conda activate flask`
>


Setup the backend
> `cd ../backend`
> 
>#install dependencies
>
>`npm i`

Setup the Frontend
> `cd ../client`
>
>#install dependencies
>
>`npm i`
>
## 💻Usage

>#start the flask server
>
>`cd flask_server`
>
>`python app.py`
>
>#start the server
>
>`cd../server`
>
>`nodemon server`
>
>
>#start the webapp
>
>`cd../client` 
>
>`npm run dev`

visit loclhost:3000 and do your thing!



---

## :star: Team - minimum-spanning-three

- [Labib Asari](https://github.com/labeeb-7z) : labeebasari@gmail.com 
- [Sameer Gupta](https://github.com/sameergupta4873) : sameergupta4873@gmail.com
- [Viraj Shah](https://github.com/virajbshah) : shahvirajbiren@gmail.com
- [Adwait Mandge](https://github.com/adwaitmandge) : adwaitmandge@gmail.com


---

## 👨‍🏫Mentors :pray:


- [Sarvagnya Purohit](https://github.com/saRvaGnyA): sarvagnyapurohit@gmail.com 
- [Neel Shah](https://gist.github.com/Neel-Shah-29): nbshah_b20@ce.vjti.ac.in
- [Arnav Zutshi](https://github.com/AsRaNi1) 



---

## 📱Screenshots
Home Page for website
![](https://i.imgur.com/3jmwC9D.png)



Home Page for logged in users
![](https://i.imgur.com/lnWd7t8.png)


A project in progress 
![](https://i.imgur.com/CU70JPN.png)

![](https://i.imgur.com/31SCJB0.png)



Collaboration System
![](https://i.imgur.com/DIYZyUt.png)

![](https://i.imgur.com/TUDSWJO.png)



Final Project
![](https://i.imgur.com/6UNx91S.png)

Generated Code 
![](https://i.imgur.com/xqr0erP.png)
