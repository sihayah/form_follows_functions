# Forum Follows Functions
  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)
  
  <br>
  
   ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)   ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)   ![javaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)   ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)   ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)   ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)   ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) 
  <br>

  ## TABLE OF CONTENTS

  


  [Description](#description) *
  [Prerequisites](#prerequisites)*
  [Installation](#installation) *
  [Usage](#usage) *
  [Tests](#tests) *
  [Questions](#questions) *
  [License](#license)

  <br>

   <img src= 'landing.png'> 
  
  <br>

  ## Description

  This is a CMS style tech blog forum where users can create an account to make posts, and interact with the posts of other users. 

  MVC is implemented in this app for seperaton of concerns.

  <br>
  <br>
  Deployment: https://forum-follows-functions.herokuapp.com/
  <br>
  Repo: https://github.com/sihayah/forum_follows_functions

<br>

  ## Prerequisites

  Make sure you have the following installed on your development machine:

  Git - [Download & Install Git](https://git-scm.com/downloads)
  <br>
  Node.js - [Download & Install Node.js](https://nodejs.org/en/download/)
  <br>
  Visual Studio Code - [Download & Install VS Code](https://code.visualstudio.com/download)
  <br>
  MySQL - [Download & Install MySQL](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide)

  <br>

  ## Installation

  Clone the repo locally. Open of the repo in VS Code. Run npm install to install all dependencies via the command line...

    npm install
  
  In the root folder of the repo, create a .env file...

    touch .env
  
  Navigate to the .env file and add the following code, updated with your data...

    DB_NAME='form_follows_functions_db'
    DB_USER=(your MySQL username)
    DB_PW=(your MySQL password)


  <br>

  <br>

## Usage

  To demo this app navigate to https://forum-follows-functions.herokuapp.com/.

  To view locally, run npm start in the command line. 

    npm start

  If it's running the following response should occur in your command line...

   <img src= 'code-snippet.png'> 

  If you then navigate to http://localhost:3001, you should see the following:

  <img width=50% height=auto src= 'landing-no-data.png'> 


  Sign-up and create a blog post. When you submit, the blog posts will populate below the post form in your dashboard. Then, if you navigate to the home page, you will see all of the posts that have been created and you can select a post to comment or upvote. 

  
  <br>

  ## Tests

  To test the helper function that accepts a string limited to 100 characters or less, in command line run following code:

    npm run test

  The result should appear in the command line as follows:

  <img src='test-snippet.png'>
  

  <br>

  ## Questions

  

  For any further inquiries, please contact me via gitHub: [(sihayah)](https://github.com/sihayah) or email: sihayaharris@gmail.com

  <br>

  

  ## License

  
  
  [click here for more information about ISC license.](https://opensource.org/licenses/ISC)
  

  <br>
  <br>
