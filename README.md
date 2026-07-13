# Resume Builder

A full-stack resume builder application that allows users to create, edit, and download professional resumes. Built with React, Node.js, Express, and MongoDB.

## Features
- Create and edit resumes
- Multiple resume templates
- Real-time preview
- PDF download functionality
- User authentication
- Cloud storage
- Responsive design
- Intuitive user interface

## Technologies
- **Frontend:** React, JavaScript, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Other:** JWT authentication, PDF generation

## Installation

```bash
git clone https://github.com/Amit-Mondal-007/resume-builder.git
cd resume-builder

# Backend setup
cd backend
npm install
npm start

# Frontend setup (in new terminal)
cd frontend
npm install
npm start
```

## Features in Detail

### Frontend
- Component-based React architecture
- Form validation
- Real-time preview
- Responsive layout

### Backend
- User authentication with JWT
- MongoDB database
- RESTful API
- File upload handling

## Environment Variables

Create `.env` files in both frontend and backend:

**Backend:**
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/resume-builder
JWT_SECRET=your-secret-key
```

**Frontend:**
```
REACT_APP_API_URL=http://localhost:5000
```

## Usage

1. Register/Login
2. Create new resume
3. Fill in your information
4. Preview in real-time
5. Download as PDF

---

Professional resume builder for modern job seekers!
