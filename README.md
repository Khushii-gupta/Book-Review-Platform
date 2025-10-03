# Book-Review-Platform
A web application that allows users to explore, add, and review books. Users can sign up, log in, add books, write reviews, and rate books. The platform makes it easy to share opinions, discover new reads, and track reading preferences.

Features:

1. User authentication (sign up, login, logout)
2. Add, edit, and delete books
3. Write and view reviews with ratings
4. Search and browse books by title, author, or genre
5. Responsive design for desktop and mobile

Tech Stack:

1. Frontend: React, HTML, CSS, JavaScript
2. Backend: Node.js/Express (or Django)
3. Database: MongoDB/MySQL/PostgreSQL
4. Authentication: JWT or sessions

Objective:
To create a community-driven platform for book lovers to share and discover books easily.

Setup Instructions for Book Review Platform:
Prerequisites:

1. Make sure you have the following installed on your system:
2. Node.js & npm 
3. MongoDB (local installation or Atlas cloud)
4. Git (optional, if cloning from GitHub)

1. Clone the Project
git clone <project-repo-url>
cd book-review-platform

2. Backend Setup

(i) Navigate to the backend folder:
    cd backend

(ii) Install dependencies:
      npm install

(iii) Configure environment variables: Create a .env file in the backend folder with the following:
      PORT=5000
      MONGO_URI=<your-mongodb-connection-string>
      JWT_SECRET=<your-secret-key>

(iv) Start the backend server:
      npm start
(The backend API will run on http://localhost:5000.)


3. Frontend Setup

(i) Navigate to the frontend folder:
    cd ../frontend

(ii) Install dependencies:
     npm install

(iii) Configure API URL (if needed): Check src/config.js or .env in the frontend and set the backend API URL:
     REACT_APP_API_URL=http://localhost:5000/api

(iv) Start the frontend server:
    npm start
  (The frontend will run on http://localhost:3000.)

4. Testing the Project

Open http://localhost:3000 in your browser.
Sign up as a new user.
Add books, write reviews, and browse existing books.
