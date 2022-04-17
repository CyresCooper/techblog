# techblog

## Description

Tech Blog is a social media application created for the tech community to connect and share information. It creates an environment for people who are passionate about technolgy to come together. While in Tech Blog, users not only can see the latest news related to the tech world, but they can also see registered users posts, comments and how helpful a post is.
Tech users can also create an account to be able to post their own articles, talk about deals, tricks or basically anything they find interesting. Registered users can also mark another user's post as helpful or unhelpful and even add comments to it.

A working Express.js API was configured to use Sequelize to interact with a MySQL database created using models and associations. It handles user authentication and provides password encryption. To create the visual structure of this application handlebars were used. Additionally, RESTful CRUD operations were tested using Insomnia
## Installation

1. Clone the repository from GitHub. 
2. Run `npm i`  To install the neccesary dependencies:
   - dotenv: to use environment variables to store sensitive data, like your MySQL username, password, and database name.
   - express, mysql2 and sequelize: to connect to the database.
   - bcrypt: to handle password encryyption
   - connect-session-sequelize and express-session: to create and manage user sessions
   - express-handlebars and handlebars: to render web pages from templates.
3. Run `mysql -u root -p` and enter your mysql password to connect to the database
4. Use the schema.sql file in the db folder to create your database using MySQL shell commands
5. Run `npm run seed` to seed data to the database
6. Run `npm start` to connect to the server 

## Usage  
Once the application is connected to the server, the user will be able to get, create, edit and delete posts. Create an account and log into it. Mark other user's post as helpful or unhelpful. Add comments to posts and see the latests news in the tech community

## Links

Deployed application:https://protected-dawn-43308.herokuapp.com/

