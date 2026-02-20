# 💼 Job Portal – Full-Stack Recruitment Solution

## 📌 Project Overview
The Job Portal is a full-stack recruitment platform designed to streamline the entire hiring process in one unified system.

The platform allows employers to post jobs, manage applications, shortlist candidates, and conduct interviews, while job seekers can browse jobs, apply, track applications, and attend interviews — all within a single environment.

The system is built using the MERN stack and focuses on security, scalability, and real-world recruitment workflow automation.

---

## 🎯 Objective
Traditional hiring platforms often separate job posting, application tracking, and interviews into different tools.  

This project aims to solve that problem by creating a complete recruitment ecosystem where the entire hiring lifecycle is handled inside one platform.

---

## 🚀 Key Features

### 👨‍💻 Job Seekers
- Browse and search jobs
- Apply for jobs
- Track application status
- Upload resume and manage profile
- Attend video interviews

### 🧑‍💼 Employers
- Post and manage job listings
- Review applications
- Shortlist candidates
- Schedule interviews
- Conduct video interviews

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- JWT (JSON Web Tokens)
- Role-Based Access Control

### Third-Party Integrations
- Agora SDK (Video Interviews)
- Cloudinary (Media Uploads)

---

## 🔐 Authentication Flow
1. User logs in
2. Server validates credentials
3. JWT token is generated containing user role and ID
4. Token stored in localStorage
5. Protected API routes validated using middleware

---

## 👥 User Roles

### Job Seekers
- Search and apply for jobs
- Upload resume
- Track applications
- Attend interviews

### Employers
- Post jobs
- Manage applications
- Shortlist candidates
- Conduct interviews

---

## 🗂️ Database Design

### User Schema
- _id
- email
- password
- role
- profile (skills, experience, company details)

### Job Schema
- _id
- title
- description
- requirements
- employer (User ID)

### Application Schema
- _id
- job (Job ID)
- candidate (User ID)
- status
- createdAt

---

## ⚙️ Recruitment Workflow
1. Employer posts a job  
2. Job seeker applies  
3. Employer reviews applications  
4. Candidate shortlisted  
5. Interview scheduled  
6. Video interview conducted  
7. Hiring decision made  

---

## 🎥 Video Interview Integration
- Agora SDK used for real-time video communication
- Unique meeting rooms generated
- Secure token-based access
- Seamless interview experience within platform

---

## ☁️ File Upload System
- Media uploads handled via Cloudinary
- Secure URLs stored in database
- Automatic media optimization

---

## 🔎 Job Filtering System
- Filter jobs by role, location, and salary
- Optimized MongoDB queries
- Pagination support for performance

---

## 🔔 Notification System
- Application status updates
- Interview scheduling updates
- Real-time interaction between users

---

## 🛡️ Security Features
- JWT authentication
- Middleware-based route protection
- Role-based authorization
- Secure API access

---

## ▶️ How to Run the Project

1. Clone the repository:
git clone
https://github.com/Payoja05/job-portal-system.git


3. Install dependencies:


npm install


3. Configure MongoDB connection.

4. Setup environment variables.

5. Start backend:


npm run server


6. Start frontend:


npm start


---

## 📈 Learning Outcomes
- Full-stack MERN development
- JWT authentication and security
- Role-based access control
- MongoDB schema relationships
- Third-party API integration
- Real-time communication systems

---

## 📌 Project Status
This project was built as a full-stack learning project focused on real-world recruitment workflows and scalable system design.

---

## 🔮 Future Improvements
- WebSocket real-time notifications
- AI-based candidate matching
- Resume parsing using NLP
- Analytics dashboard
- Email automation system

---

## 👩‍💻 Author
Electrical Engineering student transitioning into Software Development with focus on full-stack development and scalable applications.
