# 🌍 Wanderlust

> **A full-stack travel listing platform inspired by Airbnb, built with the MERN stack.**

Wanderlust enables users to explore, create, edit, and manage travel destinations through a clean and responsive interface. The application features secure user authentication, image uploads, reviews, and complete CRUD functionality.

---

## 🚀 Live Demo

🌐 **Production-ready app deployed on Render**

🔗 **Live Site:** https://wanderlust-1tpg.onrender.com/listings

---

# ✨ Features

### 🏡 Destination Listings

* Browse travel destinations
* View detailed listing information
* Responsive listing cards
* Search-friendly interface

### 🔐 Secure Authentication

* User registration and login
* Passport.js authentication
* Session-based authentication
* Protected routes

### ✍️ CRUD Operations

Authenticated users can:

* Create listings
* Edit listings
* Delete listings
* Manage their own properties

### ⭐ Review System

* Add reviews
* Delete reviews
* Rating support
* User-specific permissions

### 🖼 Image Uploads

* Cloudinary image storage
* Optimized image delivery
* Default image fallback

### 📱 Responsive UI

* Mobile-friendly layout
* Bootstrap components
* Clean user experience

---

# 🏗 System Architecture

```text
User
   │
   ▼
Express Server
   │
Passport Authentication
   │
Route Controllers
   │
MongoDB Database
   │
Cloudinary Image Storage
```

---

# 🛠 Tech Stack

## Frontend

* HTML5
* CSS3
* Bootstrap
* EJS Templates

## Backend

* Node.js
* Express.js

## Database

* MongoDB
* Mongoose

## Authentication

* Passport.js
* Express Session
* Connect Flash

## Cloud Services

* Cloudinary
* Render

---

# 📂 Project Structure

```text
Wanderlust
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── views/
├── public/
├── utils/
├── app.js
└── package.json
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Wanderlust.git
cd Wanderlust
```

## Install Dependencies

```bash
npm install
```

## Configure Environment Variables

Create a `.env` file:

```env
ATLASDB_URL=your_mongodb_connection_string

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret

SECRET=session_secret
```

## Run the Application

```bash
npm start
```

Visit:

```text
http://localhost:8080
```

---

# 📸 Screenshots

> Add screenshots of:

* Home Page
* Listing Details
* Login Page
* Add Listing
* Edit Listing
* Review Section

---

# 🔑 Key Concepts Demonstrated

* MVC Architecture
* RESTful Routing
* Authentication & Authorization
* Session Management
* CRUD Operations
* Middleware
* File Uploads
* Image Hosting with Cloudinary
* MongoDB Relationships
* Server-side Rendering with EJS

---

# 💡 Future Improvements

* Google Maps integration
* Booking functionality
* Wishlist feature
* Advanced search & filters
* User profiles
* Payment gateway integration

---

# 👨‍💻 Author

**Mohit Kumar**

Computer Engineering Student
Army Institute of Technology, Pune

GitHub: **https://github.com/Mohit-Kumar005**

---

⭐ If you found this project interesting, consider giving it a star!

Production-ready app deployed via **Render**  
🔗 [Live Site](https://wanderlust-1tpg.onrender.com/listings)
