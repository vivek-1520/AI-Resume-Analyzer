# AI Resume Analyzer & Job Matcher

A full-stack web application that helps job seekers improve their resumes. Users upload a PDF resume and get AI-based feedback, match it against a job description, and practice with generated interview questions.

## Problem Statement
Freshers often apply with one generic resume and rarely learn why they are rejected by ATS systems or recruiters. This project gives instant, structured feedback to close that gap.

## Planned Features
- User registration and login (JWT authentication)
- PDF resume upload and text extraction
- AI resume analysis: score, strengths, weaknesses, suggestions
- Job description matching: match percentage, matched and missing skills
- Interview question generation
- Saved analyses and a dashboard

## Tech Stack
| Layer | Technology |
|---|---|
| Frontend | React, JavaScript |
| Backend | Node.js, Express (REST API) |
| Database | MySQL (mysql2) |
| Auth | bcrypt, JWT |
| File handling | Multer, PDF parser |
| AI | Google Gemini API |
| Tools | VS Code, Postman, Git/GitHub |

## Architecture
See [architecture-diagram.png](architecture-diagram.png) and the full planning document `Week1_Project_Planning_Architecture.docx`.

## Planned Folder Structure
```
AI-Resume-Analyzer/
├── frontend/
├── backend/
│   ├── config/  controllers/  routes/
│   ├── middleware/  services/  uploads/
├── database/schema.sql
└── README.md
```

## Roadmap
1. Week 1: Planning and architecture design
2. Week 2: Setup, database, authentication
3. Week 3: Resume upload and AI analysis
4. Week 4: Job matching and interview questions
5. Week 5: React frontend and dashboard
6. Week 6: Testing, documentation, deployment

## Status
In development (planning phase complete).

## Author
Vivek Kumar
