# module_13_ORM_challange_E-commerce_back_end

## Description

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

Acceptance Criteria
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

## Installation

A person will need to have express.js and Sequelize installed to interact with the MySQL database and API. Insomnia will also be required to perform CRUD operations on the database. 

## Usage

This is the URL for my GitHub repository for this challenge: https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end

This is the link for the walkthrough video demonstrating the functionality of the application: https://drive.google.com/file/d/1vVDMQZY9tuJp3ALuG2JRTU13fohHd3CB/view

![Screenshot1](https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end/blob/main/utils/images/mysql.PNG)
![Screenshot2](https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end/blob/main/utils/images/seed.PNG)
![Screenshot3](https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end/blob/main/utils/images/starting%20the%20server.PNG)
![Screenshot4](https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end/blob/main/utils/images/Insomnia%20categories.PNG)
![Screenshot5](https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end/blob/main/utils/images/Insomnia%20products.PNG)
![Screenshot6](https://github.com/melkali42/module_13_ORM_challenge_E-commerce_back_end/blob/main/utils/images/Insomnia%20tags.PNG)

## Credits

Create by Melissa Kalish. I conducted several searches in https://www.google.com/ and utilized https://stackoverflow.com/ and https://www.w3schools.com/ for reserach, viewing others code examples, questions and answers. I used https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide to create the challenge README for the repository.

## License

© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.