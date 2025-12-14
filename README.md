# 📸 MERN Instagram Clone

A full-stack Instagram-like social media application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js).  
This project replicates the core functionality of Instagram including authentication, posting photos, liking, commenting, and following users.

---

## 🚀 Live Demo  
https://insta-clone-mern.vercel.app

---

## ⭐ Features

- 🔐 User authentication & authorization using **JWT**
- 📸 Upload & post photos with captions
- ❤️ Like & comment on posts
- 👥 Follow / Unfollow users
- 👤 Edit profile + upload profile image
- 📱 Fully responsive UI (mobile + desktop)
- ☁ Image upload using **Cloudinary**

---

## 🔮 Upcoming Features

- 💬 Messaging / Chat system  
- 🎥 Reels / Short videos  

---

# 🛠️ Tech Stack

## **Frontend**
- React.js  
- React Router DOM  
- Redux Toolkit  
- Axios  
- TailwindCSS  
- react-icons  
- react-hot-toast  

## **Backend**
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- bcryptjs  
- express-fileupload  
- cloudinary  
- cookie-parser  
- cors  
- dotenv  

---

# 📦 Backend Dependencies Breakdown

| Package              | Purpose                                               |
|----------------------|-------------------------------------------------------|
| express              | Server + routing                                      |
| mongoose             | ODM for MongoDB                                       |
| bcryptjs             | Password hashing                                      |
| jsonwebtoken         | JWT authentication                                   |
| express-fileupload   | Handling image uploads                                |
| cors                 | Enable cross-origin requests                          |
| cookie-parser        | Parse cookies                                         |
| dotenv               | Environment variables                                 |
| cloudinary           | Image upload & management                             |
| body-parser          | Parse request bodies                                  |

---

# 🎨 Frontend Dependencies Breakdown

| Package            | Purpose                                 |
|--------------------|-------------------------------------------|
| react              | Component-based UI                        |
| react-router-dom   | Routing & navigation                      |
| axios              | API communication                         |
| redux-toolkit      | Global state management                   |
| react-redux        | Redux bindings for React                 |
| react-hot-toast    | Toast notifications                       |
| react-icons        | Icons                                     |
| tailwindcss        | Styling                                   |

---

# ⚙️ How to Run the Project Locally
## 🗄️ 1. Clone the Repository
git clone https://github.com/your-username/InstaClone.git
cd InstaClone

---

## 🛠️ 2. Backend Setup
cd backend
npm install

### Create a `.env` file inside backend:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

### Run the backend:
npm run dev



## 🎨 3. Frontend Setup
cd ../frontend
npm install

### Run the frontend:
npm run dev



