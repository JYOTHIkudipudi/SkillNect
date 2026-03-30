#  SkillNect – AI Career Development Platform

🔗 Live Demo: https://skillnect.vercel.app/  
📂 GitHub Repository: https://github.com/JYOTHIkudipudi/SkillNect/

---

## 📌 Overview
SkillNect is a full-stack web application designed to help students and job seekers enhance their career preparation. It provides tools for resume building, interview preparation, and structured learning roadmaps in one platform.

---

## 🔥 Features

### 📝 Resume Builder
- Input personal details, education, projects, and skills  
- Generates a professional resume in PDF format  

### 🎯 Interview Preparation
- Paste Resume and/or Job Description  
- Generates relevant interview questions and guidance  

### 🛤️ Career Roadmap
- Enter a role (e.g., Java Developer)  
- Displays structured roadmap with modules and topics  
- Recommends learning resources and videos  

### 👤 Profile Dashboard
- Stores user information  
- Saves selected roadmaps and courses  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Tailwind CSS  

### Backend
- Node.js  
- Express.js  

### Database
- Neon PostgreSQL  

### Deployment
- Frontend: Vercel  
- Backend: Render  

---

## ⚙️ System Flow

### Example 1: Resume Builder
User Input → Frontend Form → Backend API → PDF Generation → Download  

### Example 2: Interview Preparation
Resume/JD Input → Backend Processing → Skill Extraction → Question Generation → Output  

---

## 📂 Project Structure
SkillNect/
│
├── frontend/ # React frontend
├── backend/ # Node.js + Express APIs
├── ai-module/ # AI-related logic (if used)
│
├── README.md
└── .gitignore


---

## ▶️ How to Run Locally

```bash
git clone https://github.com/JYOTHIkudipudi/SkillNect.git
cd SkillNect
npm install
npm run dev
