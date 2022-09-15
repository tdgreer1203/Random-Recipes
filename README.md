# Random Recipes

## Table of Contents
1. [Description](#description)
2. [Built With](#built-with)
3. [Installation](#installation)
4. [Useage](#useage)
5. [Credits](#credits)
6. [License](#license)
7. [Features](#features)
8. [Contact](#contact)

## Description
------
This is a random recipe generator I created, to test my knowledge of third-party API calls. This project uses the Spoonacular API for its food recipe generation, and The Cocktail DB for it's cocktail recipes. The purpose of the site is to allow users the ability to type in a recipe/ingredient, and then receive a random recipe based on that value for either a food dish, or a cocktail. Once a recipe is populated, users have the ability to go through the list of ingredients, and add them to a grocery list. Once the items are added, the user can save the list for later, print the list, or remove items from the list. Items are added and removed from the list by double-clicking on the item. 

During this project, I also wanted to get some experience with another CSS framework (other than Bootstrap). To accomplish this, I ended up using Materialize (my first time using), and found it quite easy to work with. By using two third-part APIs I had never worked with before, and a CSS framework I had never worked with before, I was able to get a lot of experience with reading documentation. This was also one of the main reasons for undertaking this project. 





## Built With
------
* [![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)

* [![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/about/)




## Installation
------
This app can be installed by cloning the GitHub repository using the link above. After cloning the repo, be sure to run 'npn install',  to download any dependencies needed for the project. A local version of MySQL will also be needed, in order to run the program. The database schema and initial seed data is also included in the project. Use the schema.sql file to create the database, and then use the server.js file using the 'npm start server.js' command. You can then stop the server, and seed the database using the 'npm run seed' command. Afterwards, run the server.js command again, and the application is ready to go.



## Useage
------
When testing the app, I used Insomnia, to verify/test the routes. Any REST client (such as POSTMan) will do. Once you have a REST client, simply use it to call the routes included in the program.



## Credits
------
Theo Greer



## License
---
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)


Distributed under the "Unlicense" License.

[Click Here for More Information](http://unlicense.org/)



## Features
------
This program uses Sequelize, MySQL2, Express, and DOTEnv







## Contact
------
Theo Greer - tdgreer1203@gmail.com

Project Link: [https://github.com/tdgreer1203/fantastic-umbrella.git](https://github.com/tdgreer1203/fantastic-umbrella.git)

Video Walkthrough: [https://youtu.be/fS1Bnk7WoSs](https://youtu.be/fS1Bnk7WoSs)
