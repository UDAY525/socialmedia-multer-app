# FullStack Social Media App

This project is a complete full-stack responsive social media application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). The app features user authentication, likes, dark mode, and more, with a clean and modern UI designed using Material-UI (MUI).

## Features

- **User Authentication:** Secure sign-up and login functionality using JWT.
- **Post Interactions:** Users can like and comment on posts.
- **Dark Mode:** Toggle between light and dark themes.
- **Responsive Design:** Fully responsive layout for all screen sizes.
- **Backend with MongoDB:** Data persistence using MongoDB.
- **Material-UI:** Styled with Material-UI for a polished look.

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/UDAY525/socialmedia-multer-app.git
cd socialmedia-multer-app
```

### 2. Set Up

1. Navigate to the backend directory:
```bash
cd backend
```
2. Create a .env file and add the following environment variables:
```
MONGO_URL=<your-mongodb-connection-string>
PORT=<your-desired-port-number>
JWT_SECRET=<your-jwt-secret>
```
3. Install the required dependencies:
```
npm install
```
4. Navigate to the backend directory:
```bash
cd frontend
```
5. Install dependecies
```bash
npm install
```

### 3. Running the Application

1. Start the Backend server
```bash
cd backend
npm run start
```
2. Start the Frontend server
```bash
cd frontend
npm start
```