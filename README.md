# Social Media Application

This project is a dynamic social media web application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application provides various features such as user registration, login, posting updates, commenting, liking posts, and managing user profiles.


## Preview

### Login Page
![Login-Page](https://github.com/Hemalmodi/Socia-Media-WebApp/assets/86019445/11a9a4b9-0698-404c-b32b-2124ea3fad48)

### Ragister Page
![Ragister-Page](https://github.com/Hemalmodi/Socia-Media-WebApp/assets/86019445/194b21a8-130e-432f-bf64-fb9b248d8645)

### Home Page
![Home-Page](https://github.com/Hemalmodi/Socia-Media-WebApp/assets/86019445/b43e6c2a-942b-418a-829d-f8658c181a12)

### Profile Page
![Profile-Page](https://github.com/Hemalmodi/Socia-Media-WebApp/assets/86019445/07309fc9-7a77-464f-9e66-ad7d578d110d)

### Light Mode
![Light-Mode](https://github.com/Hemalmodi/Socia-Media-WebApp/assets/86019445/e74dba8f-9f5d-4423-90c2-4168c4c21ea5)


## Features

- **User Registration and Login**: The application offers a user-friendly registration and login system allowing users to create accounts and securely log in.

- **Home Page**: The home page displays a feed of posts from various users. Users can scroll through the feed, view posts, and interact by liking and commenting.

- **Profile Page**: Each user has a dedicated profile page where they can view their own posts, profile information.

- **Post Updates**: Users can create and publish posts, which will appear in the home feed for others to see.

- **Comments and Likes**: Users can interact with posts by leaving comments and liking them.

- **Security**: The project ensures data security through various measures. It uses the bcrypt module for password hashing and encryption during user registration and login. JWT tokens are employed for authorization, managing user access to specific functionalities.

## Technologies Used

- **Front-end**: React.js is used to build the interactive user interface. It provides a seamless experience for users to interact with the application.

- **Back-end**: Node.js with Express.js is utilized to create a robust back-end server that handles API requests, manages data, and enforces security protocols.

- **Database**: MongoDB is used as the database to store user information, posts, comments, and other related data.

- **Authentication and Authorization**: Bcrypt module is employed for secure password hashing and validation. JSON Web Tokens (JWT) are used for user authorization.

## Installation and Setup

1. Clone the repository: `git clone https://github.com/Hemalmodi/social-media-app.git`

2. Navigate to the project directory: `cd social-media-app`

3. Install dependencies for both the server and client:
   ```sh
   cd server
   npm install
   cd ../client
   npm install
