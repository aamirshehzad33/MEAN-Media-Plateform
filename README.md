## Techbook - A Social Media Platform 


Techbook is a MEAN stack social media platform designed for technology enthusiasts to connect, share, and engage in meaningful discussions. The application is built using MongoDB, Express.js, Angular, and Node.js, offering a seamless experience for users and businesses.


## Overview

Social media today plays an increasingly significant role in society, the information technology industry, and computer science. Many organizations seek ways to leverage social media to increase profits and brand awareness. However, users often face frustration due to irrelevant content, while businesses waste resources on ineffective advertising.

Techbook aims to solve this problem by targeting a specific user base—tech enthusiasts. This platform fosters a focused and engaging online community where users and businesses interested in technology can interact efficiently.

## Features

### 🌍 Application Features:

🎨 Single-page web application with a responsive navbar

🔄 Full CRUD capabilities with a RESTful API

🛡️ Secure MongoDB database with restrictions and validation

🔒 Encrypted passwords for enhanced security

📱 Fully responsive UI adapting to all screen sizes

🔍 Data and posts fetched from Reddit API

📜 Server logging system for tracking activities

### 👥 User Features:

🔑 Register/Login accounts

✅ Stay logged in using local storage

🔓 Log out securely

📷 Update profile info and upload profile image

➕ Follow/Unfollow other users

🔔 Subscribe/Unsubscribe to posts

📌 View saved posts

✍️ Create new posts

💬 Comment on posts

## Tech Stack

### Frontend:

Angular 6

TypeScript

Bootstrap

Angular CLI

### Backend:

Node.js

Express.js

MongoDB

JSON Web Token (JWT)

bcrypt for password encryption

## ScreenShots


### Register Page
Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/zL0xXo8.png" height=300>|<img height = 300 src = "https://imgur.com/DRw9UDk.png">

### Login Page
Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/5971dv6.png" height=300>|<img height = 300 src = "https://imgur.com/GmdtAyY.png">


### Homepage

Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/iu7wpzq.png" height=300>|<img height = 300 src = "https://imgur.com/EcjDWP2.png">


### Profile Page
Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/P0jQXTr.png" height=300>|<img height = 300 src = "https://imgur.com/NAcxvo1.png">


### Settings Page
Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/YWCvPvT.png" height=300>|<img height = 300 src = "https://imgur.com/PeI6lTm.png">


### Friends Page
Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/qPBaLZb.png" height=300>|<img height = 300 src = "https://imgur.com/YjpegMl.png">

### About Page
Web view          |  Mobile view
:-------------------------:|:-------------------------:
<img src = "https://imgur.com/dlZsXbL.png" height=300>|<img height = 300 src = "https://imgur.com/k8M3u58.png">


## Installation & Setup

### Clone the Repository

git clone https://github.com/your-username/media-plateform.git
cd media-plateform

### Backend Setup

cd server
npm install

### Create a .env file in the server directory and add:

MONGO_URI=your-mongodb-url
JWT_SECRET=your-jwt-secret

### Start the backend:

npm start

### Frontend Setup

cd client
npm install

### Configure API base URL in /client/src/environments/environment.ts.

### Start the frontend:

ng serve

## License

This project is open-source and available under the MIT License.
