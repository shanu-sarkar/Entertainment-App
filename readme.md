# Entertainment App
## Welcome to our Entertainment App project! This repository contains both the frontend and backend code for our application. The frontend is built using React with Vite and Tailwind CSS, while the backend is built with Node.js using Express, Axios, Crocs, JWT for authentication, Mongoose for MongoDB database interaction, and Nodemon for automatic server restarts during development.

## Features

- **User Authentication**: Utilizes JWT for secure login and registration, ensuring user data protection.
- **Media Exploration**: Allows users to discover trending movies and TV shows, with detailed views available for each media item.
- **Bookmarks**: Enables users to bookmark their favorite media, creating a personalized list of favorites accessible at any time.
- **Detailed Media Information**: Provides in-depth details about movies and TV shows, including cast, genres, ratings, and more.

# File Structure
# Frontend :-
- frontend/
- │
- ├── public/
- │   ├── index.html
- │   └── ...
- │
- ├── src/
- │   ├── components/
- │   │   ├── ...
- │   │   └── ...
- │   ├── pages/
- │   │   ├── ...
- │   │   └── ...
- │   ├── App.js
- │   └── index.js
- │
- ├── .gitignore
- ├── package.json
- ├── README.md
- └── ...

# Backend:-
- backend/
- │
- ├── controllers/
- │   ├── ...
- │   └── ...
- │
- ├── models/
- │   ├── ...
- │   └── ...
- │
- ├── routes/
- │   ├── ...
- │   └── ...
- │
- ├── utils/
- │   ├── ...
- │   └── ...
- │
- ├── .gitignore
- ├── package.json
- ├── README.md
- └── server.js

# Technologies Used :-
- Frontend:-
  - Vite
  - Npm
  - HTML
  - CSS
  - Tailwind CSS
  - React.js
  - React Query
  - Javascript
  - Context API
  - React hook form
  - React Loader Spinner

- Backend:-
  - Node.js
  - Express
  - Crocs
  - JWT
  - MongoDB
  - Mongoose
  - dotenv
  - cookie-parser
  - bcrypt

# Deployment:-
- Frontent:-https://entertainment-app-shnau.vercel.app/
- Backend:-https://entertainment-app-backendshanu.vercel.app/

# Getting Started
- To get started with the development of this project, follow these steps:

1. Clone this repository:-
- git clone https://github.com/your-username/entertainment-app.git

2. Install dependencies for both frontend and backend:-
- cd frontend
- npm install

- cd ../backend
- npm install

3. Start the development servers:-
- cd frontend
- npm run dev

- `cd ../backend`
- `npm run dev`

4. Access the application at:-
  - http://localhost:5173 for the frontend and
  - http://localhost:8000 for the backend.
    
5. **Configure Environment Variables**: Create a `.env` file based on the provided `.env.example` file. Provide your MongoDB URI and TMDB API key in the `.env` file.
   ```bash
    MONGODB_URL= "your mongodb url"
    SECRET_TOKEN= "your secret token for user authentication"
    TMDB_TOKEN= "your tmdb access token for tmdb media data"
   ```
# Contributing:-
- We welcome contributions from the community! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

# License:-
- This project is licensed under the MIT License.

# The deployment process flow consists of 6 steps:-

1. Install Vercel CLI: If you haven't already, install the Vercel CLI globally by running:-
- npm install -g vercel

2.Login to Vercel: Log in to your Vercel account using the CLI:-
  - vercel login

.3 Deploy: Navigate to your frontend directory and deploy your application using the 'vercel' command:-
 - cd frontend
 - vercel
  
 4. Follow Prompts: Follow the prompts in the CLI to set up your deployment. You might be asked to provide your project name, and Vercel will handle the deployment process for you.
  
 5. Access Your Deployment: Once the deployment process is complete, Vercel will provide you with a URL where your application is hosted.
    
 6. Custom Domain (Optional): If you have a custom domain, you can set it up through the Vercel dashboard or CLI.

- Remember to configure your backend deployment separately if you're hosting it on a different platform like Heroku or Vercel Functions. If you're using Vercel Functions for your backend, you can follow similar - steps to deploy it using the Vercel CLI.

- Feel free to ask if you need further assistance!

### Backend

- **Controllers**: Contains logic for handling API requests, such as `DetailMediaController.js` for fetching detailed media information.
- **Models**: Defines the schema for database collections, including Users and Bookmarks.
- **Routes**: API routes for handling requests to different endpoints.
- **Middleware**: Includes middleware for authentication and error handling.
- **Utils**: Helper functions for interacting with external APIs (`fetchDataUtils.js`) and customizing media response data (`customizeMediaResponse.js`).

# Thank You ❤️
