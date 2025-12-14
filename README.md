📸 MERN Instagram Clone

A full-stack Instagram-like social media application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).
This project replicates the core functionality of Instagram including authentication, posting photos, liking, commenting, and following users.

🚀 Live Demo: https://insta-clone-mern.vercel.app

⭐ Features

🔐 User authentication & authorization using JWT

📸 Upload & post photos with captions

❤️ Like & comment on posts

👥 Follow / Unfollow users

👤 Edit profile + upload profile image

📱 Fully responsive UI (mobile + desktop)

☁ Image upload using Cloudinary

🔮 Upcoming Features

💬 Messaging / Chat system

🎥 Reels / Short videos

🛠️ Tech Stack
Frontend

React.js

React Router DOM

Redux Toolkit

Axios

TailwindCSS

react-icons

react-hot-toast

Backend

Node.js

Express.js

MongoDB + Mongoose

JWT Authentication

bcryptjs

express-fileupload

cloudinary

cookie-parser

cors

dotenv

📦 Backend Dependencies Breakdown
Package	Purpose
express	Handles routing & server setup
mongoose	ODM to interact with MongoDB
bcryptjs	Hashing passwords securely
jsonwebtoken	Token-based authentication
express-fileupload	Handling image uploads
cors	Enable cross-origin requests
cookie-parser	Parse cookies for auth
dotenv	Manage environment variables
cloudinary	Upload/store images in cloud
body-parser	Parse request body data
🎨 Frontend Dependencies Breakdown
Package	Purpose
react	Component-based UI
react-router-dom	Navigation & routing
axios	API calls
redux-toolkit	Global state management
react-redux	Connect React with Redux store
react-hot-toast	Toast notifications
react-icons	Icon components
tailwindcss	Utility-first styling
⚙️ How to Run the Project Locally
🗄️ 1. Clone the Repository
git clone https://github.com/your-username/InstaClone.git
cd InstaClone

🛠️ 2. Setup Backend
cd backend
npm install

Create a .env file inside backend:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

Run the backend
npm run dev


Backend runs on: http://localhost:5000

🎨 3. Setup Frontend
cd ../frontend
npm install

Create a .env file inside frontend:
VITE_API_URL=http://localhost:5000

Run the frontend
npm run dev


Frontend runs on: http://localhost:5173

📁 Project Structure
/
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── utils
│   └── server.js
│
└── frontend
    ├── src
    │   ├── components
    │   ├── pages
    │   ├── redux
    │   ├── hooks
    │   └── App.jsx

🤝 Contributing

Feel free to fork this repository, create a feature branch, and submit a pull request.
