🚨 VeritsNet-AI

🔗 Live Demo:
👉 https://veritasnet-ai.netlify.app

🧠 Overview

ScamGuard AI is a real-time AI-powered digital safety platform designed to:

Detect scam messages using Machine Learning

Identify emergency or panic situations

Provide instant risk alerts

Protect user privacy with zero data storage

This project combines AI + Web + Security + Emergency Tech into one intelligent safety system.

🎯 Problem Statement

Digital fraud and emergency situations are increasing rapidly.

Users cannot easily detect scam messages in real-time.

In accidents or panic situations, people may not be able to manually seek help.

Many apps store sensitive user data, creating privacy risks.

💡 Our Solution

ScamGuard AI provides:

✅ Real-time scam message detection
✅ Risk probability scoring
✅ Emergency keyword detection
✅ Panic trigger system
✅ Firebase-based secure authentication
✅ Zero data retention architecture

🏗️ Architecture Overview
User
 ↓
Frontend (HTML, CSS, JS)
 ↓
Firebase Authentication
 ↓
Flask Backend API
 ↓
NLP Processing (TF-IDF)
 ↓
Machine Learning Model
 ↓
Risk Score Response
⚙️ Tech Stack
Frontend

HTML

CSS

JavaScript

Firebase Authentication

Backend

Python

Flask

REST API (JSON)

AI / ML

scikit-learn

TF-IDF Vectorization

Logistic Regression

Pickle (model storage)

🤖 AI Model Explanation

The scam detection engine uses:

TF-IDF (Term Frequency – Inverse Document Frequency)
Converts text into numerical features.

Logistic Regression Classifier
Predicts probability of scam vs safe.

Output Example:

SCAM – 94% Confidence
SAFE – 88% Confidence

The system provides probability-based decisions instead of binary judgments.

🚑 Emergency Detection Module

The emergency module detects:

Panic keywords (help, accident, emergency, bachao)

No-response timeout logic

User confirmation window to prevent false alarms

Future scope includes:

Voice-based panic detection

Sensor-based accident detection

Location-based alert system

🔐 Security & Privacy

Security is built by design:

Firebase handles authentication securely

Backend is stateless

No user messages are stored

No database logging of personal data

Model remains server-side

Production-ready for HTTPS deployment

Our strongest security feature is zero data retention.

📂 Project Structure
ScamGuard-AI/
│
├── backend/
├── frontend/
├── data/
└── README.md
🚀 How to Run Locally
Backend

Navigate to backend folder

Install dependencies:

pip install -r requirements.txt

Run server:

python app.py
Frontend

Open login.html in browser
Ensure Firebase configuration is added correctly.

📊 Key Features

Real-time scam analysis

Risk percentage scoring

Clean responsive UI

Secure login system

AI-based classification

Privacy-first architecture

🌍 Live Application

🔗 https://veritasnet-ai.netlify.app

🔮 Future Scope

Voice scam detection

Mobile app integration

Telecom API integration

Government cyber cell reporting system

On-device ML deployment

🏆 Why This Project Matters

ScamGuard AI is not just a project —
it is a real-time digital safety assistant designed to reduce fraud and increase emergency response awareness.

👨‍💻 Developed For Hackathon

Built with focus on:

AI practicality

Real-world impact

Security-first design

Scalable architecture
