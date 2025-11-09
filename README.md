# YelpCamp  
A full-stack web application for listing, reviewing and managing campgrounds — built using Node.js, Express, MongoDB, EJS (or your templating engine), and other web technologies.

## 🌲 Overview  
YelpCamp allows users to browse campgrounds, leave reviews, upload images, register/login, and perform CRUD operations on campgrounds and reviews. This project demonstrates user authentication, database relationships, and deployment considerations.

## 🛠️ Built With  
- [Node.js](https://nodejs.org) + [Express](https://expressjs.com)  
- [MongoDB](https://www.mongodb.com) (via Mongoose)  
- EJS (Embedded JavaScript Templates)  
- CSS / Bootstrap (or custom)  
- Other utilities: e.g., `cloudinary` for image uploads, middleware for authentication  

## 🚀 Getting Started  
### Prerequisites  
- Node.js & npm  
- MongoDB (local or cloud)  
- (Optional) Cloudinary account for image uploads
  
### Installation  
1. Clone the repo: git clone https://github.com/margaretajibola/YelpCamp.git
2. Navigate into the directory: cd YelpCamp
3. Install dependencies: npm install
4. Create a `.env` file with (for example):  
DB_URL=<your MongoDB connection string>
CLOUDINARY_CLOUD_NAME=<your cloud name>
CLOUDINARY_KEY=<your key>
CLOUDINARY_SECRET=<your secret>
SECRET=<a session secret>
5. Start the application: npm start
6. Visit `http://localhost:3000` in your browser (or the port you used).

### Usage  
- Register as a new user or login  
- Create a new campground, upload an image  
- Edit/delete your campgrounds  
- Add reviews to campgrounds, and delete your own reviews  

## 🧩 Features  
- User authentication and sessions  
- CRUD operations on campgrounds and reviews  
- Image uploads (using Cloudinary)  
- Data relationships (users ↔ campgrounds, users ↔ reviews)    
- Responsive design  

## 📌 Notes  
- Ensure your database credentials are secure and not committed to GitHub.  
- If you deploy to production (e.g., Heroku, Vercel), set environment variables accordingly.  
