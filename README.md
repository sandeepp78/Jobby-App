Jobby App – Job Search Platform
A responsive and functional job search application built using React.js. This project simulates a real-world job portal, allowing users to authenticate securely, explore job listings, filter by employment type and salary, and view detailed job information.

Developed as part of my Java Full Stack Development training at Nxtwave, this project demonstrates practical skills in building scalable React applications, managing authentication, routing, and integrating with RESTful APIs.

Live Demo
https://sandeep07.ccbp.tech/

Key Features

Secure login using JWT Authentication

Protected routes with React Router

Job search with real-time filters

Detailed job descriptions with required skills and company info

Login session persisted using localStorage

Integration with external RESTful APIs for dynamic job data

Tech Stack

React.js
JavaScript
CSS, Bootstrap
React Router
JWT Authentication
REST APIs
Local Storage

Component Structure

Header – Navigation bar visible on authenticated pages
LoginForm – Handles user login with validation
Home – Displays introductory content after login
Jobs – Lists jobs with search and filter options
JobDetails – Provides detailed view of selected job
ProtectedRoute – Restricts access to unauthenticated users
NotFound – Custom 404 page for unmatched routes

Getting Started

Clone the repository
git clone https://github.com/sandeepp78/Jobby-App.git

Navigate into the project directory
cd Jobby-App

Install dependencies
npm install

Start the development server
npm start

The app will run at http://localhost:3000/

Credits

Developed during the Full Stack Development program at Nxtwave Disruptive Technologies.
