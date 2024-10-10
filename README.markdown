

# Welcome to the Real Estate Web Application!
This project aims to offer a smooth and efficient platform for users to buy, sell, or rent properties. Built with modern web technologies, the application provides a user-friendly experience, enabling easy management of property listings. It includes various features to simplify the process for both property owners and potential buyers or renters. Whether you're listing a property or searching for one, the platform ensures seamless navigation and access to essential tools, making property transactions hassle-free and streamlined.

## Contents
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
The Real Estate Web Platform offers a comprehensive solution for users to list, browse, and manage properties. With an emphasis on performance and ease of use, it’s built to handle property transactions effectively.


## Key Features
- *Secure User Authentication*: Incorporates JWT to manage user logins and registrations securely.
- *Property Listings*: Easily add, update, or remove property details with a few clicks.
- *Advanced Search*: Users can find properties based on criteria like location, pricing, and type.
- *Mobile-Responsive*: Works smoothly across devices, including mobile and desktop.
- *Interactive Map Integration*: Visualize properties on a dynamic map using Google Maps API.
- *Favorites*: Allows users to save properties to revisit later.
- *Admin Controls*: Admins can manage listings and user accounts with a dedicated dashboard.
- *Notification System*: Stay informed with email alerts for crucial updates and actions.

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

## How To Usage
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

# Step-by-Step Guide with Images:

## step 1:
<img width="1512" alt="Screenshot 2024-09-13 at 9 45 56 PM" src="https://github.com/Ankita-Rani-1/estate1223/blob/main/images/Screenshot%202024-10-10%20222252.png?raw=true">

## step 2:
<img width="1512" alt="Screenshot 2024-09-13 at 9 45 56 PM" src="https://github.com/Ankita-Rani-1/estate1223/blob/main/images/Screenshot%202024-10-10%20222409.png?raw=true">

## step 3:
<img width="1512" src="https://github.com/Ankita-Rani-1/estate1223/blob/main/images/Screenshot%202024-10-10%20222539.png?raw=true">

## step 4:
<img width="1512" src="https://github.com/Ankita-Rani-1/estate1223/blob/main/images/Screenshot%202024-10-10%20222722.png?raw=true">




## Planned Enhancements
- **Machine Learning Integration**: We have an `ml_algo` file that contains a machine learning algorithm for property price predictionand recommendation. This will be integrated into the application in the future to provide users with price estimates based on various factors.
- **User Reviews**: Allow users to leave reviews and ratings for properties.
- **Enhanced Search**: Implement more advanced search filters and sorting options.
- **Chat Support**: Integrate a chat system for real-time communication between buyers and sellers.
- **Payment Gateway**: Add a secure payment gateway for transactions.
