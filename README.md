#  Book Store Web Application

Welcome to Book Store Web Application built using the MERN (MongoDB, Express, React, Node.js) stack. This project allows users to browse, purchase, and read books online with features like user authentication, dark/light mode, and more.

## Features

- **Responsive Web Design**: The application is fully responsive, ensuring a seamless experience across all devices.
- **Paid and Free Books**: Users can browse both paid and free books. Access to paid books requires an account.
- **User Authentication**: Users must create an account and log in to access paid content.
- **Dark/Light Mode**: Users can toggle between dark and light modes for a personalized experience.
- **Data Storage**: User login details and book details are stored in MongoDB. Additionally, browser local storage is used for certain functionalities.

## Technologies Used

- **Frontend**: React.js, CSS (for styling)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (for storing user and book data), LocalStorage (for session management)
- **Authentication**: JWT (JSON Web Token) for secure user authentication

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MohitMalaviya/Book-Store-App
   cd Book Store App

   cd .\Backend
   npm install

   cd .\frontend
   npm install
   
   MONGO_URI=your_mongo_db_connection_string
   JWT_SECRET=your_jwt_secret_key

   cd .\backend
   npm run dev

   cd .\frontend
   npm start


   


   



