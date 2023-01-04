# Forum Follows Functions
  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)
  
  <br>
  
   ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)   ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)   ![javaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)   ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)   ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)   ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)   ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) 
  <br>

  ## TABLE OF CONTENTS

  


  [User Story](#userstory) *
  [Features](#features) *
  [Technologies](#technologies) *
  [Prerequisites](#prerequisites)*
  [Installation](#installation) *
  [Usage](#usage) *
  [Tests](#tests) *
  [Questions](#questions) *
  [License](#license)

  <br>

   <img src= './public/readmeimgs/landing.png'> 
  
  <br>
  
  Live: https://forumfollowsfunctions.herokuapp.com/
  <br>
  Repo: https://github.com/sihayah/forum_follows_functions

<br>

  ## UserStory

  AS A developer who writes about tech
  <br>
  I WANT a CMS-style blog site
  <br>
  SO THAT I can publish articles, blog posts, and my thoughts and opinions

  <br>

  ## Features

  This is a CMS-style tech blog/forum where users can create an account to make posts, and interact with the posts of other users by leaving comments. 

  MVC is implemented in this app for seperaton of concerns.

  <br>


## Technologies

  The following techonologies were used in the production of this application:

  * HTML5
  * CSS3
  * JavaScript
  * Node.js
  * MySQL
  * Sequelize
  * Heroku
  * APIs


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

  To demo this app from a browser navigate to https://forum-follows-functions.herokuapp.com/.

  To demo locally, clone the repo. Navigate to the root of the repo in the command line. Run npm install to install all dependencies:

    npm install
  
  In the root folder of the repo, create a .env file...

    touch .env
  
  Navigate to the .env file in VS Code and add the following code, updated with your data...

    DB_NAME='form_follows_functions_db'
    DB_USER=(your MySQL username)
    DB_PW=(your MySQL password)

  Once this is updated you can start the app from command line: 

    npm start

  If it's running the following response should occur in your command line...

   <img src= './public/readmeimgs/code-snippet.png'> 

  If you then navigate to http://localhost:3001, you should see the following:

  <img width=50% height=auto src= './public/readmeimgs/landing-no-data.png'> 


  <br>

  <br>

## Usage

  Begin by signing-up to create a user.

  <img src='./public/readmeimgs/ui1.png' width=50%>

  Upon sign-up, you'll be redirected to your dashboard automaticfally. From the dashboard, you can create a blog post. 

  <img src='./public/readmeimgs/ui2.png' width=50%>
  
  When you submit, the blog posts will populate below the post form in your dashboard along with the option to make edits to a post below each.

  <img src='./public/readmeimgs/ui3.png' width=50%>
  
  Then, if you navigate to the home page, you will see all of the posts that have been created.

  <img src='./public/readmeimgs/ui4.png' width=50%>
  
  You can select a post by clicking it's title, then leave comments. 

  <img src='./public/readmeimgs/ui5.png' width=50%>


  
  <br>

  ## Tests

  To test the helper function that accepts a string limited to 100 characters or less, in command line run following code:

    npm run test

  The result should appear in the command line as follows:

  <img src='./public/readmeimgs/test-snippet.png'>
  

  <br>

  ## Questions

  

  For any further inquiries, please contact me via gitHub: [(sihayah)](https://github.com/sihayah) or email: sihayaharris@gmail.com

  <br>

  

  ## License

  
  
  [click here for more information about ISC license.](https://opensource.org/licenses/ISC)
  

  <br>
  <br>
