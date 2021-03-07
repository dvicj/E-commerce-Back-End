# E-commerce Back End Starter Code

Hello, and welcome to my README! This is for my Week 13 Challenge, which was to create an E-commerce Back End using Object-Relational Mapping(ORM). 

[Please check out this video for a demonstration.](https://drive.google.com/file/d/1Ouo594L4fp3JZsVYB7RvyZ0_xultI-GG/view?usp=sharing)


It was my job to ensure the E-commerce back end had the following features:

- Connect to a database using Sequelize
- When using Insomnia Core, user is able to GET, POST, PUT and DELETE items in "Categories", "Products" and "Tags
- Uses models (Category, Product, Tags and ProductTag)
- Uses associations (Product to Category, Category to Product, Product to Tag, Tag to Product)
- store sensitive data

I was to create this Employee Tracker app, and meet all of the requirements listed above, by using:

- [Node.js](https://nodejs.org/en/)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Insomnia Core](https://insomnia.rest/download/core)
- JavaScript - ES6

I completed this project as a way to work on my skills using MySQL and Insomnia Core, as well as creating databases, something I am still learning. 

Features:

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [Learning](#learning)
* [License](#license)

## Installation

The user must clone all files from this repo. It is important that the location of the files is not changed. 

The user must have [Node.js](https://nodejs.org/en/download/) installed on their computer. 

The user must open the terminal, both command line and powershell will work, then enter "npm install" to download all the required dependencies (mySQL2, Sequelize, and dotenv). This will allow the user to run the application as intended. 
The user's MySQL information will have to be added into a .env file with the following structure: 

  DB_NAME='ecommerce_db' 
  
  DB_USER='root'
  
  DB_PW='USER'S PASSWORD'
  
 Please ensure this .env file is saved in the root directory of the project.

To run the application, user must enter "node server.js" in the command line. If the MySQL login information is correct, this will start the server. 

The localhost must then be opened on Insomnia Core. This will allow the user to GET, POST, PUT and DELETE data as they see fit. This backend will only be available to the user on their own computer. 

## Usage
Here are some user experience highlights from my page:

An example of the models used:

![models](https://github.com/dvicj/E-commerce-Back-End/blob/master/Develop/images/model%20example.PNG)

An example of the associations used:

![associations](https://github.com/dvicj/E-commerce-Back-End/blob/master/Develop/images/association%20example.PNG)

An example of the routes used: 

![routes](https://github.com/dvicj/E-commerce-Back-End/blob/master/Develop/images/route%20example.PNG)


## Credits
These are some sources I used to help me along:

- [Node.js](https://nodejs.org/en/download/)
- [MySQL2 NPM](https://www.npmjs.com/package/mysql2)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Insomnia Core](https://insomnia.rest/download/core)
- [How to save .env file in Windows?](https://stackoverflow.com/questions/48770643/how-to-save-env-file-in-windows/48771278)
- [DECIMAL Sequelize](https://sequelize.org/master/class/lib/data-types.js~DECIMAL.html)
- [Class DataTypes](https://sequelize.org/v3/api/datatypes/)
  
## Learning
Here are the highlights of what I learned and issues I had while writing this code.

- I had a lot easier time working with MySQL2 this week. I understood things much better thanks to the module lesson and using it in the challenge the previous week
- I enjoyed using Sequelize as I found using queries and joins very confusing, it was nice to have another option to use that returns the same outcome
- The models made sense to me and it was easy to extrapolate data from one model to the other to keep the code consistent 
- The associations were a little more tricky to me, I will have to continue studying and practicing them to have them make more sense. 

## License
MIT License

![license](https://img.shields.io/static/v1?label=license&message=MIT&color=blueviolet)

Copyright (c) 2021 Devin Jones

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


2
