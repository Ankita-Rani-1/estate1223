https://github.com/Ankita-Rani-1/estate1223/blob/main/images/Screenshot%202024-10-10%20222252.png?raw=true

https://github.com/Ankita-Rani-1/estate1223/blob/main/images/Screenshot%202024-10-10%20222409.png?raw=true


# Real Estate Web Application

Welcome to the Real Estate Web Application! This project is designed to provide a seamless experience for users looking to buy, sell, or rent properties. The application is built using modern web technologies and offers a range of features to make property management easy and efficient.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Contributing](#contributing)
8. [Future Enhancements](#future-enhancements)
9. [License](#license)

## Introduction
The Real Estate Web Application is a comprehensive platform that allows users to list properties, search for properties, and manage their listings. It is built with a focus on user experience and performance.

## Features
- **User Authentication**: Secure login and registration system using JWT.
- **Property Listings**: Add, edit, and delete property listings with ease.
- **Search Functionality**: Advanced search options to find the perfect property based on location, price, type, and more.
- **Responsive Design**: Optimized for both desktop and mobile devices to ensure a seamless user experience.
- **Interactive Maps**: View properties on an interactive map powered by Google Maps API.
- **Favorites**: Save favorite properties for easy access later.
- **Admin Dashboard**: Manage users and properties through an intuitive admin interface.
- **Notifications**: Receive email notifications for important updates and actions.

## Technologies Used
- **Frontend**: React, Redux, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **APIs**: Google Maps API, SendGrid API for email notifications
- **Deployment**: Docker, Kubernetes

## Installation
To get started with the project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Dharya17/real_estate_webapp.git
    cd real_estate_webapp
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up the database**:
    - Ensure you have MongoDB installed and running.
    - Create a `.env` file in the root directory and add your MongoDB connection string:
      ```
      MONGODB_URI=your_mongodb_connection_string
      ```

4. **Run the application**:
    ```bash
    npm start
    ```

## Usage
Once the application is up and running, you can access it at `http://localhost:3000`. Here are some of the main functionalities:

- **Register/Login**: Create a new account or log in with existing credentials.
- **Add Property**: List a new property by providing details such as location, price, and description.
- **Search Properties**: Use the search bar to find properties based on various criteria.
- **View Property Details**: Click on a property to view detailed information and images.
- **Save Favorites**: Save properties to your favorites list for quick access later.
- **Admin Dashboard**: Access the admin dashboard to manage users and properties.

## Project Structure
Here's an overview of the project's structure:

```
real_estate_webapp/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Auth/
│   │   ├── Property/
│   │   ├── ...
│   ├── pages/
│   │   ├── Home.js
│   │   ├── Login.js
│   │   ├── ...
│   ├── redux/
│   │   ├── actions/
│   │   ├── reducers/
│   │   └── store.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── .env
├── package.json
└── README.md
```

## Contributing
We welcome contributions to enhance the project! To contribute, follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make your changes**.
4. **Commit your changes**:
    ```bash
    git commit -m "Add your commit message"
    ```
5. **Push to the branch**:
    ```bash
    git push origin feature/your-feature-name
    ```
6. **Create a Pull Request**.


<img width="1512" alt="Screenshot 2024-09-13 at 9 45 56 PM" src="https://github.com/user-attachments/assets/5a1639fa-8f13-4f79-af63-21b86e56353d">



## Future Enhancements
- **Machine Learning Integration**: We have an `ml_algo` file that contains a machine learning algorithm for property price predictionand recommendation. This will be integrated into the application in the future to provide users with price estimates based on various factors.
- **User Reviews**: Allow users to leave reviews and ratings for properties.
- **Enhanced Search**: Implement more advanced search filters and sorting options.
- **Chat Support**: Integrate a chat system for real-time communication between buyers and sellers.
- **Payment Gateway**: Add a secure payment gateway for transactions.
