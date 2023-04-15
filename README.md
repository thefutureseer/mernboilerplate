### mernboilerplate  

# Full-Stack MERN Boilerplate  
This is a basic boilerplate code for building a full-stack web application using the MERN stack  
(MongoDB, Express.js, React.js, Node.js). This boilerplate code provides a basic file structure  
and pre-configured setup for creating a scalable, maintainable, and efficient web application.  
  
## Getting Started  
Prerequisites
Node.js
npm
MongoDB
Installation
Clone this repository:
git clone <link above>  
Install dependencies:
npm install
Configure the environment variables by creating a .env file in the root directory and adding the following variables:

DATABASE_URL=mongodb://localhost:27017/<database>
SECRET_KEY=my-secret-key
Start the development server:

npm run dev
Open your web browser and navigate to http://localhost:3000 to view the web application.  
### File Structure
The file structure of this boilerplate code is organized as follows:  

my-app/  
├── app/  
│   ├── controllers/  
│   │   ├── authController.js  
│   │   └── userController.js  
│   ├── models/  
│   │   ├── User.js  
│   │   └── index.js  
│   ├── routes/  
│   │   ├── authRoutes.js  
│   │   └── userRoutes.js  
│   └── app.js  
├── client/  
│   ├── public/  
│   │   ├── index.html  
│   │   └── favicon.ico  
│   ├── src/  
│   │   ├── components/  
│   │   ├── pages/  
│   │   ├── App.js  
│   │   ├── index.js  
│   │   └── index.css  
│   ├── package.json  
│   └── README.md  
├── config.js  
├── package.json  
└── README.md  
### Built With  
MongoDB - NoSQL database
Express.js - Server framework
React.js - Front-end library
Node.js - JavaScript runtime
npm - Package manager  

### License
This project is licensed under the MIT License - see the LICENSE file for details.
