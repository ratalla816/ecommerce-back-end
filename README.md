# E-commerce Back End

  ![badge](https://img.shields.io/github/languages/top/ratalla816/ecommerce-back-end)
  <br> 
  ![badge](https://img.shields.io/github/languages/count/ratalla816/ecommerce-back-end)
  <br>
  ![badge](https://img.shields.io/github/issues/ratalla816/ecommerce-back-end)
  <br>
  ![badge](https://img.shields.io/github/issues-closed/ratalla816/ecommerce-back-end)
  <br>
  ![badge](https://img.shields.io/github/last-commit/ratalla816/ecommerce-back-end)
  <br>
  ![badge](https://img.shields.io/badge/license-MIT-important)

  
  ## User Story 

  * AS A manager at an internet retail company
  * I WANT a back end for my e-commerce website that uses the latest technologies
  * SO THAT my company can compete with other e-commerce companies

  ## Acceptance Criteria
  
  * GIVEN a functional Express.js API
  * WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
  * THEN I am able to connect to a database using Sequelize
  * WHEN I enter schema and seed commands
  * THEN a development database is created and is seeded with test data
  * WHEN I enter the command to invoke the application
  * THEN my server is started and the Sequelize models are synced to the MySQL database
  * WHEN I open API GET routes in Insomnia Core for categories, products, or tags
  * THEN the data for each of these routes is displayed in a formatted JSON
  * WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
  * THEN I am able to successfully create, update, and delete data in my database
   
  ## Table of Contents
  - [Description](#description)
  - [Documentation](#documentation)
  - [Screenshot](#screenshot)
  - [Features](#features)
  - [Acknowledgements](#acknowledgements)
  - [License](#license)
  - [Testing](#testing)
  - [Contact](#contact)

  ## Documentation
  insomnia <https://docs.insomnia.rest/>
  <br>
  express <http://expressjs.com/en/guide/routing.html>
  <br>
  jawsDB <https://www.jawsdb.com/docs/>
  <br>
  mysql <https://dev.mysql.com/doc/>
  <br>
  dotenv <https://www.npmjs.com/package/dotenv>
  <br>
  sequelize <https://sequelize.org/master/>
  

 
  ## Screenshot
  ![Screenshot](github/images/screenshot.png)

  ## Features
  Technologies used include: sequelize, dotenv, mysql, jawsDB, insomnia, and express. 
  Login credentials are hidden from the public by storing them in an .env file. 
  Users have the ability to view an inventory list stored in the database by products, categories, and tags. 
  Products can be sorted using GET requests to view all or view one. Attributes for individual products can be edited using PUT requests. 
  Post requests will add new products, and delete requests will delete products from the database. 
  
  # Acknowledgements
  
  * Rob Atalla
  
  * Nathan Szurek (Tutor)
  
  * KU Coding Bootcamp, Module 13 Challenge Assignment © 2021 Trilogy Education Services, LLC, a 2U, Inc. brand Confidential and Proprietary.
  All Rights Reserved.

  * KU Coding Bootcamp, Module 14 lesson activity, "Just Tech News" © 2021 Trilogy Education Services, LLC, a 2U, Inc. brand Confidential and Proprietary.
  All Rights Reserved.
  
    
  ## License
  ![badge](https://img.shields.io/badge/license-MIT-important)
  <br>
  Permission to use this application is granted under the MIT license. <https://opensource.org/licenses/MIT>


  ## Testing
  Insomnia

  ## Contact:
  Holler at me! <a href="mailto:rob.atalla@robatalla816.com">rob.atalla@robatalla816.com</a>