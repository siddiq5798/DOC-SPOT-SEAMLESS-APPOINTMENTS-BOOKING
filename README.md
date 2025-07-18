DocSpot-Seamless-Appointment-Booking-System
A full-stack web application to help users book doctor appointments online, with real-time scheduling, document uploads, admin approval, and doctor availability management.

Project Overview
DocSpot is a healthcare appointment management system designed to make the process of booking doctor visits quick, easy, and efficient for patients. The platform offers a seamless interface for users (patients), doctors, and admins with features like user authentication, appointment scheduling, admin approval, and medical document uploads.

Features
User Features
Registration & login with secure password handling
Apply for doctor profile (for doctors)
View available doctors and their details
Book appointments with time and date
Upload documents during appointment booking
View and manage appointment history
Doctor Features
Register via user account and apply to be a doctor
Manage upcoming appointments
Accept/reject appointment requests
Admin Features
Review and approve doctor applications
Oversee all appointments and platform activity
Tech Stack
Layer	Technology
Frontend	React.js, Bootstrap, Material UI
Backend	Node.js, Express.js
Database	MongoDB (with Mongoose)
Authentication	JWT, bcrypt
API Handling	Axios
Tools	Postman, MongoDB Compass, Nodemon
Folder Structure
doctorapp/ ├── client/ # React frontend │ ├── public/ │ ├── src/ │ │ ├── components/ │ │ ├── pages/ │ │ ├── App.js │ │ └── ... │ └── package.json │ ├── server/ # Express backend │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── config/ │ ├── server.js │ └── package.json

Installation & Setup Instructions
Prerequisites
Node.js (v18.x recommended)
MongoDB
VS Code or any preferred IDE
1. Clone the repository
git clone https://github.com/siddiq5798/DOC-SPOT-SEAMLESS-APPOINTMENTS-BOOKING cd doctorapp

2. Install backend dependencies
cd server npm install

3. Install frontend dependencies
cd ../client npm install --legacy-peer-deps

4. Configure .env
In the server/ folder, create a .env file with the following contents: PORT=5000 MONGO_URL=your_mongodb_connection_string JWT_SECRET=your_secret_key

5. Run the application
Start the backend server
cd server npx nodemon server.js

Start the frontend client
cd client npm start

Access the app at: http://localhost:3000

Screenshots
Add screenshots here after running the application, including:

Login/Register Page
Doctor Dashboard
Appointment Booking
Admin Panel
MongoDB Compass with data
Future Enhancements
Integrate video consultation
Enable payment gateway
Mobile app version
AI-based doctor recommendation
E-prescription generation
Feedback and rating system
