# MERN Stack Developer Assignment

## Overview
This project is a **full-stack web application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. The application allows users to **search for and add friends**, manage their friend list, and receive **friend recommendations** based on mutual connections.

## Features
### **1. User Authentication**
- **Sign Up**: Users can create an account with a unique username and password.
- **Login**: Secure authentication system using JWT.
- **Session Management**: Maintain user sessions securely.

### **2. Home Page**
- Display a list of users.
- Search bar to find users.
- Friend list with an option to unfriend.

### **3. Add Friend Feature**
- **Search Users**: Find registered users.
- **Send Friend Requests**: Users can send and receive requests.
- **Accept/Reject Requests**: Manage friend requests easily.

### **4. Friend Recommendation System**
- **Mutual Friends**: Recommend friends based on common connections.
- **Dashboard Display**: Show recommendations to users.

## **Technology Stack**
### **Frontend**
- **React.js**: For building an interactive UI.
- **State Management**: Redux or Context API (if needed).
- **Bootstrap**: For styling and responsiveness.

### **Backend**
- **Node.js & Express.js**: For API and server-side logic.
- **JWT Authentication**: Secure user authentication.
- **RESTful APIs**: For efficient client-server communication.

### **Database**
- **MongoDB**: NoSQL database for storing user and friend data.

### **Version Control**
- **GitHub**: 
- **Branches & Commits**

## **Setup Instructions**
### **1. Clone the Repository**
```bash
  git clone <repository_url>
  cd <project_folder>
```
### **2. Install Dependencies**
```bash
  # Install frontend dependencies
  cd client
  npm install

  # Install backend dependencies
  cd ../server
  npm install
```
### **3. Configure Environment Variables**
- Create a `.env` file in the `server` directory.
- Add the following variables:
```env
  MONGO_URI=<your_mongodb_connection_string>
  JWT_SECRET=<your_jwt_secret>
  PORT=5000
```

### **4. Run the Application**
```bash
  # Start backend server
  cd server
  npm start

  # Start frontend server
  cd client
  npm start
```
### **4. Deployment LINK **

https://si-gn-zy-fr-endify.vercel.app/
---
**Note**: Focus on building a functional, optimized application rather than adding unnecessary complexity. The goal is to demonstrate your **proficiency in MERN stack development**. Good luck! 🚀

