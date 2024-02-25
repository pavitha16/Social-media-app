FullStack Social Media App

Build a COMPLETE Fullstack Responsive MERN App with Auth, Likes, Dark Mode | React,MongoDB, MUI , Search , Posts ,Views , Comments, User profiles, image uploads etc


Features
1) Authentication: Users can sign up, log in, and log out securely.
2) Likes: Users can like posts and view the total number of likes on each post.
3) Dark Mode: Users can toggle between light and dark mode for better user experience.
4) Responsive Design: The application is designed to be fully responsive, providing a seamless experience across various devices and screen sizes.
5) Post Creation: Authenticated users can create posts with images and descriptions.
6) Like Posts: Users can like/unlike posts.

Technologies Used
1) MongoDB: A NoSQL database used to store user information and posts.
2) Express.js: A web application framework for Node.js used for building the backend API.
3) React.js: A JavaScript library used for building the user interface.
4) Node.js: A JavaScript runtime used for building the backend server.
5) Material-UI: A popular React UI framework for building responsive and customizable components.

--Install server dependencies:
npm install

--Navigate to the client directory:
cd client

--Set up environment variables:
Create a .env file in the project root.

--Add the following environment variables:
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

--Start the server:
npm start

--Start the client:
cd client
npm start

Deployment 
To deploy this application, you can follow these general steps:
1) Set up a MongoDB database. You can use services like MongoDB Atlas for this purpose.
2) Update the MongoDB URI in the .env file with your database connection string.
3) Set up environment variables for your production environment, including MONGODB_URI and JWT_SECRET.

--Build the React client for production:
cd client
npm run build
1) Deployed backend Node.js server to a hosting provider in Heroku 
2) Deployed  frontend React application to a static hosting service in Netlify
3) Database: MongoDB can be hosted on MongoDB Atlas 

Tested deployed application to ensure everything works as expected.
