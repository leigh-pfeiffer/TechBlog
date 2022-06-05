# The Tech Blog 
![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Description 
This project is a CMS-style blog where developers can publish their blog posts and comment on other developers post. This application follows the MVC paradigm in it's structure and uses Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication. 

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

## Installation 
The user should clone the repository from GitHub. This application requires Node.js, Express.js, Sequelize, mysql2, connection-session/express-session, and  Jest. If cloning the repo, run npm i to run all modules. To connect to the database run mysql -u root -p and enter password from .env file. Then source the schema.sql. To connect to the server run npm start. 

## Usage 
This application will allow users to sign up if they are not a member, then once they are logged in they are able to view their dashboard of posts to view, add, edit, and delete blog posts and comment on other developers post. <br>
Please view deployed live Heroku [URL](https://shrouded-eyrie-14601.herokuapp.com/).<br>
![](./assets/images/Capture.PNG)

## License 
This project is license under MIT

## Contributing 
Contributors should read the installation section. 

## Tests
The tests in this application verifies data formatting using Jest.  

## Questions
