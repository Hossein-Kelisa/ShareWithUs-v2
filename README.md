# ShareWithUs

**ShareWithUs** is a full-stack web application that enables people to share, borrow, and manage everyday items within their community. The platform encourages sustainable sharing by making it easy to lend unused items instead of purchasing new ones.

Originally developed as the final group project during the **HackYourFuture Web Development Program**, this repository is now independently maintained, deployed, and improved by **Hossein Kelisa**.

## 🌐 Live Demo

**Application:** https://sharewithus2.netlify.app/

**Repository:** https://github.com/Hossein-Kelisa/ShareWithUs-v2

---

## 📖 Project Overview

ShareWithUs provides a simple and secure way for community members to share resources.

Visitors can browse available items without creating an account, while registered users can upload items, borrow available items, manage their profile, and leave reviews.

The application follows a modern full-stack architecture using React, Node.js, Express, MongoDB Atlas, JWT authentication, Cloudinary for image storage, Render for backend hosting, and Netlify for frontend deployment.

---

## ✨ Features

### Public Features

* Browse all available items
* Search items
* Filter by category
* View item details
* Read reviews
* Responsive interface

### Authenticated Features

* User registration and login
* JWT authentication
* Share new items with images
* Upload images using Cloudinary
* Borrow available items
* View borrowed items
* View shared items
* Manage personal profile

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* React Router
* CSS
* Fetch API

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication

### Cloud Services

* Netlify
* Render
* Cloudinary

### Development Tools

* Git
* GitHub
* ESLint
* Prettier
* Jest

---

## 🏗️ Architecture

```
React (Netlify)
        │
        ▼
Netlify Redirects
        │
        ▼
Express API (Render)
        │
        ▼
MongoDB Atlas
        │
        ├──────────────► Cloudinary
        │                  (Image Storage)
        ▼
JWT Authentication
```

---

## 📂 Project Structure

```
ShareWithUs-v2
│
├── client
│   ├── src
│   ├── public
│   └── vite.config.js
│
├── server
│   ├── src
│   │   ├── controllers
│   │   ├── routes
│   │   ├── models
│   │   ├── db
│   │   └── util
│   └── package.json
│
└── README.md
```

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Hossein-Kelisa/ShareWithUs-v2.git
```

Install dependencies:

```bash
npm install
npm run setup
```

Create the required `.env` files inside both the `client` and `server` folders.

Start the development environment:

```bash
npm run dev
```

---

## ☁️ Deployment

### Frontend

* Hosted on **Netlify**

### Backend

* Hosted on **Render**

### Database

* MongoDB Atlas

### Image Storage

* Cloudinary

---

## 📸 Screenshots

Screenshots will be added soon.

---

## 🚀 Future Improvements

* Better loading experience while the backend wakes up on Render Free
* Improved health monitoring endpoint
* Email notifications
* Item reservation requests
* Real-time notifications
* Admin dashboard
* Dark mode
* Progressive Web App (PWA)

---

## 🙏 Acknowledgements

This project was originally created as the final team project of the **HackYourFuture Web Development Program**.

The current repository is independently maintained, deployed, and continuously improved by **Hossein Kelisa**.

---

## 👨‍💻 Author

**Hossein Kelisa**

GitHub: https://github.com/Hossein-Kelisa

LinkedIn: https://www.linkedin.com/in/hossein-kelisa/
