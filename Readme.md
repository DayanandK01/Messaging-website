# Messaging Website

## Description

The **Messaging Website** is a real-time web application that allows users to send and receive messages instantly. It is built using React for the frontend, Node.js for the backend, and WebSockets for real-time communication. The app includes features such as user authentication, messaging, and dynamic chat updates.

This project is ideal for learning full-stack development and creating web applications with a modern tech stack.

## Features

- User registration and authentication
- Real-time messaging with WebSockets
- Responsive and intuitive UI built with React
- Message history for each user
- Lightweight and fast for easy scalability

## Prerequisites

Before you begin, make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [npm](https://www.npmjs.com/)

## Installation

Follow these steps to set up the project on your local machine.

## 1. Clone the Repository

Clone the repository to your local machine using Git:

```bash
git  clone URL
```
## 2. Install Dependencies
  ##  Backend
   ```bash
    npm install
   ```
   ## Frontend
   ```bash
    npm install
   ```

## 3. Setup Environment Variables

inside .env file
```bash
   PORT=5001<br>
   MONGODB_URL=your-database-url<br>
   JWT_SECRET=your-jwt-secret-key<br>
   CLOUDINARY_CLOUD_NAME = your_cloud_name  (create your account in cloudinary.io site)<br>
   CLOUDINARY_API_KEY = your_api_key (given in api section of settings)<br>
   CLOUDINARY_API_SECRET = your_api_secret  ( found in the same place)<br>
   NOVE_ENV = development<br>
```

## 4. Start backend application
```bash
    npm run start --prefix backend (should start on port 5001 and connect to mongoDB database using MONGODB_URL which is located with in .env file)
```
## 5. Start frontend application
```bash
    npm run dev --prefix frontend ( frontend will start on http://localhost:given_port )
```

## Usage
Register a new account or log in if you already have one.
Start sending and receiving messages in real-time.
Enjoy a fully functional messaging experience.


## Note :
This website is not build by me from strach. I am learning backend development so i referenced a yuotube video from "As a programmer" youtube channel to build this project.
All credit goes to "Aa a programme" youtube channel.




