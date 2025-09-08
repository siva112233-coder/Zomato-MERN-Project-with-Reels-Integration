# 🍔 Zomato Reels-Style Food Feed

A **full-stack MERN project** that lets users explore food-partner videos in a vertical Reels-style feed (like Instagram). Users can like or save videos, and view food-partner profiles with all their reels.

## 🔹 Features

* **User & Food-Partner Authentication:** Secure registration and login for users and food-partners.
* **Reels-Style Video Feed:** Scroll through vertical food-item videos seamlessly.
* **Like & Save Functionality:** Users can like or save videos for later.
* **Food-Partner Profiles:** View partner info, address, profile picture, and all their uploaded reels.
* **Media Uploads:** Food-partners can upload images and videos via **ImageKit.io**.
* **Responsive UI:** Smooth vertical feed navigation built with React.
* **Backend APIs:** CRUD operations, secure token-based auth, and optimized database handling with MongoDB and Express.js.

## 🔹 Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Media Handling:** ImageKit.io
* **Authentication:** JWT tokens

## 🔹 Screenshots / Demo

> *(Optional: Add screenshots of feed, profile page, or demo GIF here)*

## 🔹 Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. **Install dependencies**

   ```bash
   npm install
   cd frontend
   npm install
   ```

3. **Set environment variables**
   Create a `.env` file in the backend folder with:

   ```
   MONGO_URI=<your-mongo-db-uri>
   JWT_SECRET=<your-jwt-secret>
   IMAGEKIT_PUBLIC_KEY=<your-imagekit-public-key>
   IMAGEKIT_PRIVATE_KEY=<your-imagekit-private-key>
   IMAGEKIT_URL_ENDPOINT=<your-imagekit-endpoint>
   ```

4. **Run the project**

   ```bash
   # Backend
   npm run dev

   # Frontend (in separate terminal)
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app.

## 🔹 Future Improvements

* Add search and filter for food items
* Enable comments on reels
* Implement real-time notifications for likes/saves
