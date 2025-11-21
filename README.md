Learning Management System (LMS)
A modern, full-stack Learning Management System that empowers educators to create and sell courses while providing students with an intuitive learning experience powered by AI-enhanced search.

✨ Features
For Students

🔍 AI-Powered Search - Find courses using natural language queries powered by Google Gemini AI
📚 Course Enrollment - Browse and enroll in courses across multiple categories and difficulty levels
🎥 Video Learning - Stream course lectures with a custom video player
⭐ Review System - Rate and review courses to help other students
👤 Personal Dashboard - Track enrolled courses and manage your profile
🔐 Secure Authentication - JWT-based auth with Google OAuth integration

For Educators

📝 Course Creation - Build comprehensive courses with multiple lectures
💰 Monetization - Set prices and sell courses through integrated payment processing
📊 Course Management - Full CRUD operations for courses and lectures
🖼️ Media Upload - Upload thumbnails and videos with Cloudinary integration
📈 Student Analytics - Track enrollments and course performance

Technical Highlights

⚡ Fast and responsive UI with React 19 and Vite
🎨 Beautiful design with Tailwind CSS
🔄 Real-time state management with Redux Toolkit
💳 Secure payments via Razorpay
☁️ Cloud storage with Cloudinary
🤖 AI-enhanced search capabilities

🏗️ Architecture
Backend Stack

Runtime: Node.js
Framework: Express.js
Database: MongoDB with Mongoose ODM
Authentication: JWT + bcryptjs
Payment: Razorpay
AI: Google Generative AI (Gemini)
Storage: Cloudinary
Email: Nodemailer

Frontend Stack

Framework: React 19
Build Tool: Vite
State Management: Redux Toolkit
Routing: React Router
Styling: Tailwind CSS
HTTP Client: Axios
Auth: Firebase

📋 Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v16 or higher)
MongoDB (local or Atlas account)
npm or yarn package manager

🚀 Getting Started
1. Clone the Repository
```
git clone https://github.com/yourusername/lms-platform.git
cd lms-platform
```
2. Backend Setup
```
cd backend
npm install
```
Create a .env file in the backend directory:

env
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CORS_ORIGIN=http://localhost:5173
```

# Cloudinary
```
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
```

# Razorpay
```
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

# Google Gemini AI
```
GEMINI_API_KEY=your_gemini_api_key
```

# Email (Nodemailer)
```
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your_email@gmail.com
EMAIL_PASSWORD=your_email_password
```
Start the backend server:
```
npm start
```
The server will run on http://localhost:5000

3. Frontend Setup
```
cd frontend
npm install
```
Create a .env file in the frontend directory:

env
```
VITE_API_URL=http://localhost:5000/api
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
Start the development server:
```


npm run dev
The app will run on http://localhost:5173


