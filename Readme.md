# 🚀 GenAI – Full Stack Gen AI Job Preparation Web App

A complete **Full Stack + Generative AI powered web application** designed to help users prepare for jobs — from **authentication and resume processing** to **AI-driven interview preparation**.

This project simulates a real-world product where users can:

- Upload resumes 📄
- Analyze job descriptions 🎯
- Detect skill gaps 📊
- Generate AI-based interview questions 🤖
- Create ATS-optimized resumes 🧠

---

## 🧠 Key Features

- 🔐 Secure Authentication using JWT
- 🚫 Token Blacklisting for enhanced security
- 📄 Resume Upload & Parsing
- 🧠 AI-Powered Skill Extraction
- 📊 Skill Gap Detection (Resume vs Job Description)
- 🤖 AI Interview Question Generation
- 📝 ATS-Optimized Resume Generation
- 📑 Dynamic PDF Creation using Puppeteer
- 🏗 Real-world scalable project structure

---

## 🛠 Tech Stack

### Frontend

- React.js

### Backend

- Node.js
- Express.js

### Authentication

- JSON Web Tokens (JWT)
- Token Blacklisting

### AI Integration

- Gemini API (Google GenAI)

### PDF Generation

- Puppeteer

---

## 📂 Project Structure

```
GenAI/
 ├── frontend/     # React Application
 ├── backend/      # Node.js + Express Server
 ├── .gitignore
 └── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/genai.git
cd genai
```

---

### 2️⃣ Setup Backend

```
cd backend
npm install
```

Create a `.env` file inside `backend/`:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
GOOGLE_GENAI_API_KEY=your_api_key
```

Run backend:

```
npm start
```

---

### 3️⃣ Setup Frontend

```
cd ../frontend
npm install
npm run dev
```

---

## 🔐 Authentication Flow

- User registers/logs in
- JWT token is generated
- Token stored on client-side
- Token blacklisting used during logout for security

---

## 🤖 AI Workflow

1. Resume uploaded
2. Text extracted and parsed
3. Skills identified using AI
4. Job description analyzed
5. Skill gap detected
6. AI generates:
   - Interview questions
   - Resume improvements

---

## 📑 PDF Generation

- Puppeteer is used to:
  - Generate ATS-friendly resumes
  - Export structured reports as PDFs

---

## 📄 License

This project is licensed under the MIT License.

---
