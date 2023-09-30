# Hi, I'm Nilesh Patil! 👋


## 🚀 About Me
I'm a full stack developer with 2+ yrs of using MERN Stack and Java & SpringBoot...


## 🛠 Skills
React, Nodejs, ExpressJs, MongoDB, Java, SpringBoot, Javascript, HTML, CSS...

---

# Employee Review System
  This is an Employee Review System project of Coding Ninjas made using Nodejs, Expressjs in backend. MongoDB is used for database and for frontend it uses EJS. Any user can create their account with role either admin or employee. Both Admin and Employee is given different task.
  Admin can add, remove or update any user's data. Employee can give their feedback on other employees.

  ## Environment Variables Backend

To run this project, you will need to add the following environment variables to your __.env__ file in __backend-nodejs__ folder

`JWT_SECRET` = jdhdhd-kjfjdhrhrerj-uurhr-jjge  
`REFRESH_TOKEN_SECRET` = fgkjddshfdjh773bdjsj84-jdjd774  
`SESSION_EXPIRY` = 60 * 15  
`REFRESH_TOKEN_EXPIRY` = 60 * 60 * 24 * 30  
`MONGO_DB_CONNECTION_STRING` = mongodb://localhost/social-media-dashboard  
`COOKIE_SECRET` = jhdshhds884hfhhs-ew6dhjd  
`WHITELISTED_DOMAINS` = http://localhost:3000  
`PORT` = 8080  

## Installation

Clone the project

```bash
  https://github.com/nil0412/SocialMediaDashBoard_MERN.git
```

Go to the project directory

```bash
  cd SocialMediaDashBoard_MERN
```


# Installation and Run 
  Follow these steps:
  - Get the code on your system.
  - Open terminal on your pc and navigate to the root directory of the project.
  - Run "npm install" command inside the terminal to install all the required dependencies.
  - Create a '.env' file inside root directory and define values for
      - PORT ( port on which your project will run )
      - MONGODB_URL ( URL of your mongoDB database for connecting to database )
      - SECRET_KEY ( secret key for express-session )
  - Run 'npm start' command inside terminal to run the code.
  - Open your web browser and serach for 'localhost:{PORT}/' to see the output.

# Features
  - Create account with your role as " Admin / Employee "
  - Login using your email and password.
  - Store your session-token in DB so that logged in user's session will be safe.
  - Store all the data of employee, reviews in database.
  - Admin:
      - View list of all the employee.
      - Add a new employee.
      - Update data of any employee ( Name, email, Role ).
      - See review given to an employee.
      - Assign task to any employee ( review task : Giving review to other employee )
      - Delete any employee.
  - Employee:
      - See all the reviews given to him by other employee.
      - Give his review for other employee as assigned from admin.
  
# Tools used:
  - Nodejs
  - Expressjs
  - MongoDB
  - EJS
  - Passport
  - Passport local
  - BootStrap
#   E m p l o y e e - R e v i e w - S y s t e m 


Install dependencies

```bash
  npm install
```
## Run Locally

Start the server

```bash
  npm start
```


## Features

- Login/Register User
- Create Post
- Like & RemoveLike on Posts
- Add Comments to Posts
- Edit own profile
- Seach other Users
- View Others Profile
- Add & Remove Friends


## Screenshots


## License

[MIT](https://choosealicense.com/licenses/mit/)


 
 
