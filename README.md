# E-commerce Back-End

## Table of Contents
* [Description](#Description)
* [User Story](#User-Story)
* [Acceptance Criteria](#Acceptance-Criteria)
* [GitHub Repository](#GitHub-Repository)
* [Installation](#Installation)
* [Tests](#Tests)
* [Video Links](#Video-Links)


## Description 
This project is the back-end of an e-commerce website. This project is not deployed.

**Built With**
* JavaScript ES5  
* JavaScript ES6  
* JSON
* Node.js 
* Express.js 
* npm dotenv express mysql2 sequelize nodemon
* MySQL
* REST

## User Story

<details>
<summary>Expand</summary>  

    AS A manager at an internet retail company
    I WANT a back end for my e-commerce website that uses the latest technologies
    SO THAT my company can compete with other e-commerce companies
</details>

## Acceptance Criteria

<details>
<summary>Expand</summary>  

    GIVEN a functional Express.js API
    WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
    THEN I am able to connect to a database using Sequelize
    WHEN I enter schema and seed commands
    THEN a development database is created and is seeded with test data
    WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the MySQL database
    WHEN I open API GET routes in Insomnia Core for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON
    WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
    THEN I am able to successfully create, update, and delete data in my database
</details>

## GitHub Repository
The project's repo link: https://github.com/rosefrancis-tech/e-commerce

## Installation
In order to run the application in your local, follow the steps
* Install [Node.js](https://nodejs.org/en/), [MySQL](https://dev.mysql.com/downloads/windows/installer/8.0.html)
* Download the codes from [repo](https://github.com/rosefrancis-tech/e-commerce)
* In the terminal navigate to the local repo 
* To install dependencies, run `npm install`
* To [create database](https://drive.google.com/file/d/1Z5hmoqcAQ3qq2GC4aOYkCr6VuG4_HmWX/view?usp=sharing), open MySQL shell and run `source db/schema.sql`  
![Set up Database](/assets/images/setUpDatabase.gif)
* To seed the application with sample data, run `npm run seed`
* To start the application, run `npm start`  
![Start and Seed](/assets/images/Start-Seed.gif)
* To test endpoints, follow [Tests](#Tests)
* To exit, type `Ctrl+C` in terminal  


## Tests

Endpoints can be tested in Insomnia core or similar API client after start running the application from the terminal using 'npm start'.

The list of End Points are:
* Category
    * Return all categories or create category  
        localhost:3001/api/categories  
    * Get a single category, update or delete a category  
        localhost:3001/api/categories/:id
* Product
    * Return all products or create product  
        localhost:3001/api/products  
    * Get a single product, update or delete a product  
        localhost:3001/api/products/:id
* Tag
    * Return all tags or create tag  
        localhost:3001/api/tags  
    * Get a single tag, update or delete a tag  
        localhost:3001/api/tags/:id  

Testing in Insomnia Core are given below as screenshots.  

![GET routes](/assets/images/GET-all-models.gif)  
![Get routes by id](/assets/images/GET-by-id.gif)  
![Category routes](/assets/images/POST-PUT-DELETE-category.gif)  
![Product routes](/assets/images/POST-PUT-DELETE-product.gif)  
![Tag routes](/assets/images/POST-PUT-DELETE-tag.gif)  

## Video Links

1. [Set up Database](https://drive.google.com/file/d/1Z5hmoqcAQ3qq2GC4aOYkCr6VuG4_HmWX/view?usp=sharing)
2. [Start and Seed](https://drive.google.com/file/d/1xaby8Zm2IMsie3iGWI3rH932ihzES0lZ/view?usp=sharing)
3. [GET routes](https://drive.google.com/file/d/1ouur7fNtbI1g9ZchEe-SM9dd8CzSDStt/view?usp=sharing) to return all categories, all products, and all tags being tested in Insomnia Core
4. [Get routes by id](https://drive.google.com/file/d/1U52CSpug9DoC9stL12tKZPRByAF_khl5/view?usp=sharing) to return a single category, a single product, and a single tag being tested in Insomnia Core
5. [Category routes](https://drive.google.com/file/d/1UCELBBtd0VoF6D1huoPDUow1lESHldn7/view?usp=sharing) to POST, PUT, and DELETE routes for categories being tested in Insomnia Core
6. [Product routes](https://drive.google.com/file/d/1a0jU1GgFtHsHmkdgNm-mYXfNN1jMWJYm/view?usp=sharing) to POST, PUT, and DELETE routes for categories being tested in Insomnia Core
7. [Tag routes](https://drive.google.com/file/d/15FsipZ_IPN_uuiN2rOrhORqiE7YTqsVA/view?usp=sharing) to POST, PUT, and DELETE routes for categories being tested in Insomnia Core