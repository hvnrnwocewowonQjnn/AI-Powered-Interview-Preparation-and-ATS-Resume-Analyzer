# 🚀 AI Interview Preparation & ATS Resume Analyzer

An AI-powered MERN Stack application that helps job seekers analyze resumes, identify skill gaps, generate AI interview questions, and create ATS-optimized resumes in PDF format using **Google Gemini AI**.

## ✨ Features

- 🔐 JWT Authentication & Protected Routes
- 📄 Resume Upload & Parsing
- 🤖 AI Skill Gap Detection
- 💬 AI Interview Question Generation
- 📑 ATS Resume Generation
- 📥 PDF Resume Download (Puppeteer)
- 📊 Interview Report History
- 🌐 Responsive React UI

---

## 🛠 Tech Stack

**Frontend**
- React.js
- React Router
- Axios
- Context API

**Backend**
- Node.js
- Express.js
- MongoDB
- JWT
- Multer
- Zod

**AI & Tools**
- Google Gemini API
- Puppeteer
- PDF Parsing

---

## 📂 Project Structure

```text
client/
server/
README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/AI-Interview-Preparation.git
cd AI-Interview-Preparation
```

### Backend

```bash
cd server
npm install
npm run dev
```

### Frontend

```bash
cd client
npm install
npm run dev
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
GEMINI_API_KEY=your_api_key
```

---

## 📌 Workflow

```text
Resume Upload
      │
      ▼
Resume Parsing
      │
      ▼
Gemini AI
      │
      ├── Skill Gap Analysis
      ├── Interview Questions
      └── ATS Resume Generation
      │
      ▼
Generate PDF
```

---

## 🚀 Future Improvements

- Company-specific Interview Questions
- Mock Interview
- Resume Score
- Multiple Resume Templates
- Docker Deployment

---

## 👨‍💻 Author

**Abhishek Prajapati**

⭐ If you like this project, don't forget to **Star** the repository!
