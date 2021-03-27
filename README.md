

# Envoy-Product
A Hub for memebers to post, rate, review and talk about environmentally friendly products!

## Table Of Content
* [General Info](#general-info)
# Envoy-Product
A Hub for memebers to post, rate, review and talk about environmentally friendly products!

## Table Of Content
* [General Info](#general-info)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Demo](#demo)
* [Questions](#questions)

## General Info
The application follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Technologies
Project is created with 
* [Bootstrap](https://getbootstrap.com/)
* [Javascript](https://www.javascript.com/)
* [Node.js](https://nodejs.org/en/)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Express](https://www.npmjs.com/package/express)
* [Dotenv](https://www.npmjs.com/package/dotenv)
* [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize)
* [Express-Handlebars](https://www.npmjs.com/package/express-handlebars)
* [Flickity](https://www.npmjs.com/package/flickity)
* [bcrypt](https://www.npmjs.com/package/bcrypt)
* [jquery-bar-rating](https://www.npmjs.com/package/jquery-bar-rating)
* [typed.js](https://www.npmjs.com/package/typed.js)

## Installation
To get started clone this repository using 
<br>
```terminal
git clone git@github.com:Envoy-products/Envoy-Products.git
```
Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm install
``` 
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
Use database
```terminal
envoy_db
```
Then quit MySQL shell and input the following in your terminal to start running application
```terminal
npm start
```
Once all that is done, navigate to - http://localhost:3001 to begin!


## Usage
This application is deployed on Heroku at https://envoy-guide.herokuapp.com/
<br>
There are three types of access
	<br>
	Admin access
	<br>
	General access
	<br>
	Visitor access

<br>
Admin status assigned users will have full access to the site which includes <br>
	full access to all content for general users
	<br>
	ability to approve articles posted by general users
	<br>
	ability to approve products being posted by general users.  
<br>
General access allows one to <br>
	view all web content including featured/approved product and articles
	<br>
	Products can be viewed by product or retailer category.
	<br>
	create user profile
	<br>
	upload content (which requires approval by admin for others to view)
	<br>
	Post products (which requires approval by admin for others to view)
	<br>
	Create/Edit their profile as needed
	<br>
	Comment on existing articles posted on the site. 

<br>
Visitor access allows one to <br>
	view all web content including featured/approved product and articles
	<br>
	Products can be viewed by product or retailer category.
	<br>
	has the option to become a member by creating a general access profile. 

 
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>
This repository is licensed under the MIT license.

## Demo


## Questions
Questions about this repository? Please contact us at [envoyproducts90@gmail.com](mailto:envoyproducts90@gmail.com). View more of our work in GitHub at [Envoy-Products](https://github.com/Envoy-products/Envoy-Products) 













# my-e-commerce

Table of Contents:
#Usage
#Installation
#Technology Used
#Files and Folders
#GitHub link
#Demo
#Questions and contact


#Usage
This is a functional Express.js API. 
User can connect with database name, MySQL username, and MySQL password to an environment variable file
User able to connect to a database using Sequelize
A development database will be creat and is seed with test data when user enter schema and seed commands
User enter the command to invoke the application then server is started and the Sequelize models are synced to the MySQL database
User can see JSOn formated data by open API GET routes in Insomnia Core for categories, products, or tags
User able to successfully create, update, and delete data in the database by API POST, PUT, and DELETE routes in Insomnia Core


#Installation
Node.js and MySQL must be installed on your computer.
Clone the repo by copying and pasting in your command line:
git clone https://github.com/shamimimtiaz/my-e-commerce.git
Navigate to the root directory and run: npm install
To start the server, in the command line run:npm start
Add a .env file to the root of the app with the following details
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'


#Technology Used
Node
Express
MySQL
Sequelize
Dotenv


##Files and Folders
*config 	: connection.js
*db 	: schema.sql
*model	:Category.js, Product.js, ProductTag.js, Tag.js, index.js
*routes	: index.js 
	api: category-routes.js, index.js, product-routes.js, tag-routes.js
*seeds	: category-seeds.js, product-seeds.js, product-tag-seeds.js, tag-seeds.js, index.js
*server.js


	
#GitHub Links
https://github.com/shamimimtiaz/my-e-commerce.git


#DEMO:01 (Demonstrated mysql, GET routes to return all categories, all products, and all tags being tested in Insomnia Core)
![DEMO1_Mar 6, 2021 8_57 PM](https://user-images.githubusercontent.com/75001492/110227402-369fd180-7ec6-11eb-9e58-de3859f2c515.gif)

#DEMO:02 (Demonstrated GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core)
![DEMO2_ Mar 6, 2021 9_09 PM](https://user-images.githubusercontent.com/75001492/110227462-bded4500-7ec6-11eb-899b-5d88fcde3601.gif)

#DEMO:03 (Demonstrated POST, PUT, and DELETE routes for categories being tested in Insomnia Core)
![DEMO3_ Mar 6, 2021 9_21 PM](https://user-images.githubusercontent.com/75001492/110227488-eaa15c80-7ec6-11eb-93cb-81937bfcbe5b.gif)

#DEMO:04 (POST, PUT, and DELETE routes for tags being tested in Insomnia Core)
![DEMO4_ Mar 6, 2021 9_31 PM](https://user-images.githubusercontent.com/75001492/110227510-1cb2be80-7ec7-11eb-926d-c31e55ce5237.gif)

#DEMO:05 (POST, PUT, and DELETE routes for products being tested in Insomnia Core)
![DEMO5_ Mar 6, 2021 9_44 PM](https://user-images.githubusercontent.com/75001492/110227548-774c1a80-7ec7-11eb-854b-e6e7da0a245f.gif)


#Questions and contact
If you have any questions, please e-mail me at km_si@ymail.com.


Copyright Shamim Imtiaz. All Rights Reserved.
