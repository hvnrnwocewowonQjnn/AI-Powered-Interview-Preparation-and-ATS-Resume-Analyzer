# 🚀 AI Interview Preparation & ATS Resume Analyzer

An AI-powered Full Stack web application that helps job seekers improve their resumes and interview readiness. The platform analyzes uploaded resumes against job descriptions, identifies missing skills, generates AI-powered interview questions, and creates ATS-optimized resumes in PDF format.

Built using the **MERN Stack**, **Google Gemini AI**, and **Puppeteer**, this project demonstrates end-to-end full-stack development, secure authentication, AI integration, and document generation.

---

## 📌 Features

### 🔐 Authentication & Security
- User Registration & Login
- JWT Authentication
- Protected Routes
- Token Blacklisting (Secure Logout)
- Cookie-based Authentication

### 📄 Resume Analysis
- Upload Resume (PDF)
- Resume Parsing
- Skill Extraction
- Job Description Analysis
- AI-Based Skill Gap Detection

### 🤖 AI Features
- AI-Powered Interview Question Generation
- Personalized Interview Preparation
- Resume Improvement Suggestions
- ATS Resume Analysis
- AI Resume Optimization

### 📊 Report Management
- Save Interview Reports
- View Previous Reports
- Report History
- Dashboard with Recent Reports

### 📑 Resume Generation
- ATS Optimized Resume
- Dynamic PDF Generation
- Download Resume
- Professional Resume Formatting

### 🌐 Frontend
- Responsive UI
- React Context API
- Custom Hooks
- Protected Routing
- Clean Dashboard

---

# 🛠 Tech Stack

## Frontend

- React.js
- React Router
- Axios
- Context API
- CSS

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Multer
- JWT Authentication
- Zod Validation
- Cookie Parser

## AI

- Google Gemini API

## PDF Generation

- Puppeteer

## Deployment Ready

- MongoDB Atlas
- Vercel / Netlify (Frontend)
- Render / Railway (Backend)

---

# 📂 Project Structure

```
AI-Interview-Preparation/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── utils/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── services/
│   ├── config/
│   └── uploads/
│
├── README.md
└── package.json
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/AI-Interview-Preparation.git
```

```bash
cd AI-Interview-Preparation
```

---

## Backend Setup

```bash
cd server

npm install
```

Create a `.env` file inside the server directory.

```env
PORT=5000

MONGO_URI=YourMongoDBConnectionString

JWT_SECRET=YourJWTSecret

GEMINI_API_KEY=YourGeminiAPIKey

CLIENT_URL=http://localhost:5173
```

Run Backend

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd client

npm install

npm run dev
```

---

# 🔄 Application Workflow

```text
User Login/Register
        │
        ▼
Upload Resume (PDF)
        │
        ▼
Resume Parsing
        │
        ▼
Skill Extraction
        │
        ▼
Upload Job Description
        │
        ▼
Gemini AI Analysis
        │
        ├───────────────► Skill Gap Detection
        │
        ├───────────────► Interview Questions
        │
        ├───────────────► Resume Suggestions
        │
        ▼
ATS Optimized Resume
        │
        ▼
Generate PDF using Puppeteer
        │
        ▼
Download Resume
```

---

# 📸 Features Preview

- User Authentication
- Dashboard
- Resume Upload
- Skill Gap Analysis
- AI Interview Questions
- ATS Resume Generator
- PDF Download
- Previous Reports

> Add screenshots here after deployment.

---

# 🔐 Authentication Flow

- Register User
- Login
- JWT Token Generation
- Cookie Storage
- Protected Routes
- Token Blacklisting
- Secure Logout

---

# 🤖 AI Workflow

```
Resume
      │
      ▼
Resume Parsing
      │
      ▼
Gemini AI
      │
      ├────────► Skill Extraction
      ├────────► Missing Skills
      ├────────► Interview Questions
      ├────────► Resume Suggestions
      ▼
Structured JSON Response
```

---

# 📄 API Endpoints

## Authentication

| Method | Endpoint | Description |
|----------|----------|------------|
| POST | /api/auth/register | Register User |
| POST | /api/auth/login | Login User |
| POST | /api/auth/logout | Logout User |
| GET | /api/auth/me | Current User |

---

## Interview

| Method | Endpoint | Description |
|----------|----------|------------|
| POST | /api/interview/generate | Generate Interview Report |
| GET | /api/interview | Get All Reports |
| GET | /api/interview/:id | Get Report By ID |

---

## Resume

| Method | Endpoint | Description |
|----------|----------|------------|
| POST | /api/resume/generate | Generate ATS Resume PDF |

---

# 🎯 Skills Demonstrated

- Full Stack Development
- REST API Development
- MERN Stack
- Authentication
- Authorization
- JWT
- Token Blacklisting
- MongoDB
- Express.js
- React.js
- Node.js
- AI Integration
- Google Gemini API
- Prompt Engineering
- Resume Parsing
- File Upload Handling
- PDF Generation
- Puppeteer
- Context API
- Custom Hooks
- State Management
- Secure Backend Development

---

# 🚀 Future Improvements

- OpenAI Integration
- Resume Score Visualization
- Multiple Resume Templates
- Mock Interview with Voice
- Speech-to-Text Interview
- AI Career Recommendation
- Company-specific Interview Questions
- Resume Version History
- Admin Dashboard
- Email Notifications
- Docker Support
- CI/CD Pipeline

---

# 📈 Learning Outcomes

This project helped strengthen my understanding of:

- MERN Stack Development
- Secure Authentication
- JWT & Token Blacklisting
- AI Integration using Gemini
- Prompt Engineering
- Resume Parsing
- PDF Generation with Puppeteer
- REST API Design
- State Management
- Production-Level Project Structure

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Abhishek Prajapati**

- GitHub: https://github.com/your-github
- LinkedIn: https://linkedin.com/in/your-linkedin

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
