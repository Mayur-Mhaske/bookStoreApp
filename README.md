#BookStoreApp
A full-stack web application for managing a bookstore, built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This app allows users to view, add, edit, and delete books in a virtual store.

Technologies Used:
MongoDB: NoSQL database used to store book information.
Express.js: Backend framework for handling API requests.
React.js: Frontend JavaScript library used to create dynamic user interfaces.
Node.js: JavaScript runtime to run the server-side logic.
Tailwind CSS: A utility-first CSS framework used for building custom user interfaces.
Features:
View a list of books.
Add new books to the bookstore.
Edit and update book information.
Delete books from the store.
Responsive design for mobile and desktop views.
Installation Instructions:
Clone the repository:

bash
Copy code
git clone https://github.com/Mayur-Mhaske/bookStoreApp.git
cd bookStoreApp
Install backend dependencies:

bash
Copy code
cd backend
npm install
Set up your .env file for MongoDB connection:

Create a .env file in the backend folder and add your MongoDB URI:
env
Copy code
MongoDBURI=mongodb://localhost:27017/bookStore
Run the backend server:

bash
Copy code
npm start
Install frontend dependencies:

bash
Copy code
cd frontend
npm install
Run the frontend:

bash
Copy code
npm start
Usage:
The application runs on http://localhost:3000 for the frontend and http://localhost:4000 for the backend.
You can add, edit, or delete books from the interface.
All changes are stored in MongoDB, and updates are reflected in real-time.
