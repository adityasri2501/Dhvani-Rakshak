An intelligent system to verify newspaper titles using AI-driven similarity analysis, built for regulatory compliance and digital governance.

🚀 Overview

Dhvani Rakshak is an AI-powered web application designed to assist regulatory authorities in verifying proposed newspaper titles before approval.

It automates the verification process defined under the Press and Registration of Periodicals Act, 2023, ensuring that newly submitted titles are:

Not misleading

Not phonetically or semantically similar to existing publications

Compliant with naming rules and language policies

This system significantly reduces manual effort, prevents duplication, and increases transparency in media regulation.

🧠 Key Features

🔍 AI-Based Similarity Detection

Phonetic matching (Soundex / phoneme logic)

Semantic similarity using NLP

String similarity scoring

📜 Rule-Based Validation

Enforces PRGI rules for title approval

Checks language, region, and naming conflicts

⚡ Real-Time Verification

Instant feedback for title approval or rejection

Confidence score & explanation for each decision

🧩 Modular Architecture

Frontend + Backend separation

Easily extendable for government-scale deployment

🏗️ System Architecture
Frontend (HTML/CSS/JS)
        |
        ▼
Flask API (Backend)
        |
        ├── Title Normalization
        ├── Phonetic Matching Engine
        ├── Semantic Similarity Engine
        ├── Rule-Based Validator
        |
        ▼
Firestore / Data Store

🛠️ Tech Stack
Frontend

HTML5, CSS3, JavaScript

Firebase Hosting

Backend

Python (Flask)

NLP & Text Similarity Engines

Rule-based Decision System

Cloud & Tools

Firebase Hosting

Google Cloud (for future deployment)

Git & GitHub

📂 Project Structure
dhvani-rakshak/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── app.js
│
├── core/
│   ├── decision_engine.py
│   ├── semantic_similarity.py
│   ├── phonetic.py
│   ├── rule_engine.py
│   └── ...
│
├── api/
│   └── app.py
│
├── rules/
│   └── *.json
│
├── firebase.json
├── .gitignore
└── README.md

⚙️ Local Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/adityasri2501/Dhvani-Rakshak.git
cd Dhvani-Rakshak

2️⃣ Install backend dependencies
pip install -r requirements.txt

3️⃣ Run backend server
python api/app.py

4️⃣ Open frontend

Open frontend/index.html in browser
or deploy via Firebase Hosting.

🌐 Live Demo

🔗 https://prgi-title-verification.web.app
 (example placeholder)

📜 Legal Context

This system is designed in alignment with:

Press and Registration of Periodicals Act, 2023

Guidelines issued by Registrar of Newspapers for India (RNI/PRGI)

It assists human reviewers and does not replace statutory decision-making.

🧠 Future Enhancements

Multilingual semantic expansion

AI confidence explanation graphs

Admin dashboard for officials

Integration with government data APIs

OCR-based document ingestion
