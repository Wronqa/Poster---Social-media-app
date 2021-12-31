# Poster - Social media app

Poster is a fully functional social media aplication.


## Features 
 - Sharing posts (with emoticons also)
 - Sharing photos
 - Commenting posts
 - Liking posts
 - Realtime searching for users
 - Deleting posts
 - Following/Unfollowing users
 - Viewing timeline posts
 - Profile pages
   - Changing profile picture
   - Changing cover photo
   - Editing personal information (city, relatioship status)
   - Changing password
- Followings list
   - View all followings
- Responsive layout



The application uses JWT authentication system (access token and refresh token). Tokens are stored in HttpOnly secure cookies.   



## Technologies

- Frontend

   - HTML, SASS, Java Script 
   - React.js (Hooks) + Redux Toolkit
   - MUI
   
   
   
    NPM's
    - Axios 0.24.0
    - Dotenv 10.0.0
    - emoji-picker-react 3.4.8
    - react-cookie 4.1.1
    - react-device-detect 2.1.2
    - react-redux 7.2.6
    - react-router-dom 6.0.2
    - sass 1.43.4
    - timeago.js 4.0.2
    - redux 4.1.2
  
- Backend
   - Node.js + Express.js
   - MongoDB
   - JWT
   - Cloudinary API

    NPM's
    - bcrypt 5.0.1
    - cloudinary 1.27.1
    - cookie-parser 1.4.6
    - dotenv 10.0.0
    - express 4.17.1
    - express-validator 6.13.0
    - helmet 4.6.0
    - jsonwebtoken 8.5.1
    - jwt-decode 3.1.2
    - mongoose 6.0.12
    - morgan 1.10.0
    - multer 1.4.4
    - multer-storage-cloudinary 4.0.0
    - uniqid 5.4.0

 ## Installation
 
 #### 1. Install [Node.js](https://nodejs.org/en/) and [GIT](https://git-scm.com/) 
 #### 2. Clone the repo
 #### 3. Create **.env** file in api and client directory a fill it based on the following examples
 
 Client
  ```bash
REACT_APP_CLOUDINARY_NAME = 
```

Api 
  ```bash
DATABASE_URL = 

SALT_ROUNDS = 

JWT_SECRET_KEY = 
JWT_REFRESH_SECRET_KEY = 
JWT_ACCESS_TOKEN_EXPIRES_TIME = 
JWT_REFRESH_TOKEN_EXPIRES_TIME = 


CLOUDINARY_NAME = 
CLOUDINARY_API_KEY = 
CLOUDINARY_API_SECRET = 
```
 
 #### 4. Enter the client directory and type 
 ```bash
npm install
```
#### 5. Enter the api directory and install all depedencies
 ```bash
npm install
```
#### 6. Start the application

Client
 ```bash
npm start
```

Api
 ```bash
node index
```

## Some screenshots

### Registration form
[url=https://postimg.cc/z3WLhxgg][img]https://i.postimg.cc/z3WLhxgg/login.png[/img][/url]




   
