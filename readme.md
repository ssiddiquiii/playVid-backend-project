# 🎥 PlayVid Backend

A complete backend for a video hosting platform (similar to YouTube) built with the MERN stack.

This project was built to learn and implement professional backend practices, including secure authentication, video handling, and complex database relationships.

---

## 🏗️ System Architecture

I designed the database to efficiently handle users, videos, subscriptions, and playlists.

![Database Schema](./public/assets/models.png)

*(The diagram above shows the relationships between Users, Videos, and Subscriptions.)*

---

## ⚙️ Tech Stack

* **Node.js & Express.js:** For building the API and handling requests.
* **MongoDB (Mongoose):** To store data with structured schemas.
* **Cloudinary:** To store and manage images and video files.
* **JWT & Bcrypt:** For secure user authentication (Login/Signup).
* **Multer:** For handling file uploads.

<!-- ## 🚀 Key Features

* **Authentication & Security:**
    * Secure user login/signup with Access & Refresh tokens.
    * Password encryption using Bcrypt.
    * Protected routes and role-based access.
* **Video Management:**
    * Upload, update, and delete video content.
    * Video publishing toggle (Public/Private).
    * Thumbnail and video file storage via Cloudinary.
* **User Engagement:**
    * Like, Dislike, and Comment functionality.
    * Subscribe/Unsubscribe features.
    * Playlists and Watch History tracking.
* **Advanced Features:**
    * **Aggregation Pipelines:** Complex database queries for watch history and user stats.
    * **Paginated APIs:** Efficient data loading for large lists. -->

<!-- ## 🛠️ Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file in the root directory.

**Note:** Do not share your actual secrets in this file or commit it to GitHub.

```env
PORT=8000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net
CORS_ORIGIN=*

# JWT Secrets
ACCESS_TOKEN_SECRET=<your-random-secret>
ACCESS_TOKEN_EXPIRY=1d
REFRESH_TOKEN_SECRET=<your-random-secret>
REFRESH_TOKEN_EXPIRY=10d

# Cloudinary Services
CLOUDINARY_CLOUD_NAME=<your-cloud-name>
CLOUDINARY_API_KEY=<your-api-key>
CLOUDINARY_API_SECRET=<your-api-secret> -->