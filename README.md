# 🤖 TDS Virtual TA – AI Query Answering Assistant

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Web_Framework-lightgrey?logo=flask)](https://flask.palletsprojects.com/)
[![Deploy to Vercel](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)](https://vercel.com/)
[![Promptfoo Tested](https://img.shields.io/badge/Tested_with-Promptfoo-orange?logo=openai)](https://promptfoo.dev/)

> A virtual teaching assistant that responds to course-related questions and links helpful resources, built for IITM B.Sc. Tools in Data Science.

---

## 🔍 About the Project

**TDS Virtual TA** is a backend service that mimics a teaching assistant (TA) by answering questions related to the _Tools in Data Science_ (TDS) course. It supports natural language queries and optionally image input, returning answers and reference links.

This project was built and deployed by **Anish Sharma**  
🎓 _22BCY10018, B.Tech Cyber Security @ VIT Bhopal_  
📘 _B.Sc. Data Science @ IIT Madras_  
🔗 [GitHub Profile](https://github.com/iitanish)

---

## 🌐 Live Endpoint

> **Public API:**  
> `https://tds-project-1-m4e2gimuv-anish-sharmas-projects-38542d60.vercel.app/query`

### Example Request (POST)

```json
{
  "question": "What is the exam date for TDS Sep 2025?"
}
```
