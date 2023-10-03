# Hi, I'm Nilesh Patil! 👋


## 🚀 About Me
I'm a full stack developer with 2+ yrs of using MERN Stack and Java & SpringBoot...
## 🛠 Skills
React, Nodejs, ExpressJs, MongoDB, Java, SpringBoot, Javascript, HTML, CSS...

---

# Employee Review System
  - This is an Employee Review System project made using Nodejs, Expressjs in backend. MongoDB is used for database and for frontend it uses EJS. 
  - Any user can create their account with role either admin or employee. Both Admin and Employee is given different task.
  - Admin can add, remove or update any user's data. Employee can give their feedback on other employees.

## Environment Variables

To run this project, you will need to add the following environment variables to your __.env__ file in __backend-nodejs__ folder

`MONGODB_URL` = mongodb://localhost/Employee-Review-System  
`SECRET_KEY` = jhdshhds884hfhhs-ew6dhjd  
`PORT` = 8080   

## Installation

Clone the project

```bash
  git clone https://github.com/nil0412/Employee-Review-System.git
```

Go to the project directory

```bash
  cd Employee-Review-System
```

Install dependencies

```bash
  npm install
```
## Run Locally

Start the server

```bash
  npm start
```
 - Open your web browser and serach for 'localhost:{PORT}/' to see the output.


## Features
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
  


## Tools used:
  - Nodejs
  - Expressjs
  - MongoDB
  - EJS
  - Passport
  - Passport local
  - BootStrap

## Screenshots




## License

[MIT](https://choosealicense.com/licenses/mit/)

