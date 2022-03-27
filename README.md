# E-Commerce Backend
  ![Github licence](http://img.shields.io/badge/license-ISC-blue.svg)  
  ## Description 
  I build the back end for an e-commerce site. I took a working Express.js API and configure it to use Sequelize to interact with a MySQL database.
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Questions](#questions)
  
  ## Installation 
  The application requires NodeJS and MySQL. Run ```npm instal``` and download all the dependencies. Connect to your MySQL and run ```source db/schema.sql``` to create the database and then quit out of MySQL.  In the server.js file look for ```sequelize.sync({ force: false })``` and change ```false``` to ```true```. In the command line run ```npm run seed``` then change ```force``` back to ```false```. Once that is all set you can run the app with ```npm start```.
  ## Usage 
  Walkthrough Video
  
  ## License 
  This project is license under [ISC](https://choosealicense.com/licenses/ISC/)

  
  ## Questions
  If you have any questions about this projects, please contact me directly at [c.vazquez1986@gmail.com](mailto:c.vazquez1986@gmail.com).  
  You can view more of my projects at [Clos86](https://github.com/Clos86).