
# 🚀 ResumePilot

ResumePilot is an AI-powered resume analysis and interview preparation platform that helps job seekers evaluate their resumes against a target job description and generate a personalized interview preparation strategy.

By leveraging Google's Gemini AI, ResumePilot provides actionable insights, identifies skill gaps, generates interview questions, and creates tailored resumes to improve a candidate's chances of success.

---

## ✨ Features

### 📄 Resume Analysis

* Upload your resume in PDF format
* Extract and analyze resume content
* Compare resume against a target job description

### 🎯 Job Match Scoring

* AI-generated compatibility score
* Evaluation based on skills, experience, and keywords
* Detailed feedback on strengths and weaknesses

### 💡 Skill Gap Analysis

* Identify missing skills required for the role
* Highlight areas for improvement
* Personalized recommendations

### 🎤 Interview Preparation

Generate role-specific interview questions:

* Technical Questions
* Behavioral Questions
* Scenario-Based Questions

### 📅 Preparation Roadmap

* Day-wise preparation plan
* Structured learning path
* Interview readiness guidance

### 📑 AI Resume Generation

* Generate an optimized resume tailored to the target role
* Download professionally formatted PDF resumes

### 🔐 Secure Authentication

* JWT-based authentication
* Protected routes and user sessions
* Secure user data management

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* SCSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JSON Web Tokens (JWT)

### AI Integration

* Google Gemini API

### PDF Generation

* Puppeteer

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/VishalVab01/ResumePilot.git

cd ResumePilot
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the server directory and add:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key
```

---

## ▶️ Running the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

Application will be available at:

```text
http://localhost:5173
```

---

## 📂 Project Structure

```text
ResumePilot/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── services/
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## 🔄 Workflow

1. User registers or logs in.
2. User uploads their resume.
3. User provides a target job description.
4. ResumePilot analyzes the resume using Gemini AI.
5. The system generates:

   * Match Score
   * Skill Gap Analysis
   * Technical Questions
   * Behavioral Questions
   * Preparation Roadmap
6. User can generate and download a tailored resume PDF.

---

## 🚀 Future Improvements

* ATS score simulation
* Multiple resume templates
* Cover letter generation
* Resume version management
* Interview answer evaluation
* Mock interview chatbot
* LinkedIn profile analysis
* Job recommendation engine

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📬 Contact

**Vishal Vaibhav**

GitHub: https://github.com/VishalVab01

If you found this project useful, consider giving it a ⭐ on GitHub.
