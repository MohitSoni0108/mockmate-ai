# MockMate AI 🎯

An AI-powered mock interview preparation platform that helps candidates practice for job interviews with intelligent feedback.

## 🚀 Features
- Upload your resume and job description
- Get AI-generated interview questions tailored to your profile
- Receive detailed feedback and skill gap analysis
- Get a day-wise interview preparation plan
- Generate an ATS-friendly resume using AI
- Secure user authentication with JWT

## 🛠️ Tech Stack
**Frontend:** React, Vite, SCSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB Atlas  
**AI:** Google Gemini API  
**Auth:** JWT + bcrypt  

## ⚙️ Setup Instructions

### Backend
```bash
cd Backend
npm install
# Create .env file with:
# PORT=3000
# MONGO_URI=your_mongodb_uri
# JWT_SECRET=your_jwt_secret
# GOOGLE_GENAI_API_KEY=your_gemini_key
node server.js
```

### Frontend
```bash
cd Frontend
npm install
# Create .env file with:
# VITE_BACKEND_URL=http://localhost:3000
npm run dev
```

## 👨‍💻 Author
Mohit Soni
