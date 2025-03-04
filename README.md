# spark


Table of Contents
Features

Setup Instructions

Demo Credentials

Live Demo

API Endpoints

Technologies Used



Features
The key features of  project.

User Authentication: Register and login with JWT-based authentication.

CRUD Operations: Create, read, update, and delete user data.

RESTful API: Well-structured API endpoints for easy integration.

Database Integration: MongoDB for storing and managing data.

Environment Variables: Secure configuration using .env.


Setup Instructions
git clone https://github.com/Sumeet00007-max/spark.git
cd spark

Set up environment variables:
MONGO_URI=mongodb+srv://Cuvette:1234@cluster0.xqlur.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
PORT=3000


Run the application:
bash
npm run dev

Access the application:

Open your browser or API testing tool (e.g., Postman) and navigate to http://localhost:3000.


Demo Credentials
For testing purposes, you can use the following demo credentials:

Email: mahi@gmail.com

Password: Mahi@7781s



Live Demo
The application is hosted and available for live testing. Click the link below to access the live demo:
spark-lake-theta.vercel.app

API Endpoints
The API endpoints my project supports.

Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login and get JWT token
GET	/api/users	Get all users
GET	/api/users/:id	Get a user by ID
PUT	/api/users/:id	Update a user by ID
DELETE	/api/users/:id	Delete a user by ID


Technologies Used
Backend: Node.js, Express.js

Database: MongoDB, Mongoose

Authentication: JSON Web Tokens (JWT)

Environment Management: dotenv


Contact
If you have any questions or feedback, feel free to reach out:

Sumeet N

Email:sumeetnagare90@gmail.com
