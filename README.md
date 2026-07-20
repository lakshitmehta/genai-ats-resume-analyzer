# GenAI-Powered ATS Resume Analyzer & Interview Preparation Platform

An AI-powered full-stack web application that analyzes resumes against job descriptions, generates personalized interview preparation plans, identifies skill gaps, and creates ATS-optimized resumes using Google's Gemini AI.

## Features

- Secure user authentication with JWT
- Upload resume (PDF/DOCX)
- AI-powered resume analysis
- Job description matching
- Personalized interview preparation strategy
- Technical interview questions
- Behavioral interview questions
- Personalized preparation roadmap
- Resume match score and skill gap analysis
- AI-generated ATS-friendly resume
- Download generated resume as PDF
- View previous interview reports

## Tech Stack

### Frontend
- React
- Vite
- React Router
- Axios
- Sass

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- Google Gemini AI
- Puppeteer
- Zod

---

## Application Preview

### Login

![Login](assets/screenshots/login.png)

---

### Dashboard

![Dashboard](assets/screenshots/dashboard.png)

---

### Technical Interview Questions

![Technical Questions](assets/screenshots/technical-questions.png)

---

### Behavioral Interview Questions

![Behavioral Questions](assets/screenshots/behavioral-questions.png)

---

### AI-Generated Preparation Roadmap

![Roadmap](assets/screenshots/roadmap.png)

---

### AI-Generated ATS Resume

![Generated Resume](assets/screenshots/generated-resume.png)

## Project Structure

```
genai-ats-resume-analyzer/
│
├── Backend/
│   ├── src/
│   ├── server.js
│   └── package.json
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── assets/
    └── screenshots/
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/lakshitmehta/genai-ats-resume-analyzer.git
```

### Backend

```bash
cd Backend
npm install
npm run dev
```

### Frontend

```bash
cd Frontend
npm install
npm run dev
```

---

## Environment Variables

Create a `.env` file inside the `Backend` directory.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_API_KEY=your_gemini_api_key
```

> **Note:** Never commit your `.env` file or API keys to GitHub.

---

## Future Improvements

- Resume keyword optimization
- Multi-language resume generation
- Interview analytics dashboard
- AI mock interview with voice interaction
- Email interview reports
- Docker support

---

## Acknowledgements

This project was developed by following and learning from a public tutorial by **Ankur**. The repository has been independently configured, documented, and organized for learning and portfolio purposes.