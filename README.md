🧠 BrainByte – Personal AI Tutor

📖 About the Project

BrainByte is an AI-powered Personal Tutor designed to provide a personalized learning experience for students.

Unlike normal AI tools that simply answer questions or generate learning content, BrainByte uses the student's profile and performance to identify concepts where the student needs improvement.

The system follows an adaptive learning cycle:

Assess → Learn → Practice → Analyze → Improve → Review

The goal is to make the AI behave more like a personal tutor that understands the student's learning progress.

🎯 Problem Statement

Students often study the same material regardless of their individual strengths and weaknesses.

A student may understand one concept very well but struggle with another concept. Traditional learning systems may not automatically identify these weaknesses.

General AI tools can explain a topic, but the student usually has to decide what to ask, what to study next, and how to track their progress.

BrainByte solves this problem by creating a personalized learning cycle based on the student's previous performance.

💡 Our Solution

BrainByte combines student information, diagnostic performance, AI-generated lessons, quizzes, and performance analysis.

Learning Flow

Student Profile
↓
Diagnostic Test
↓
Performance Analysis
↓
Personalized AI Lesson
↓
Adaptive Quiz
↓
Score & Feedback
↓
Weak Topic Detection
↓
Review / Retest
↓
Progress Update

✨ Key Features

👤 Student Profile – Collects student level, subject, topic and learning goal.

📝 Diagnostic Test – Checks the student's existing knowledge.

🤖 AI Personal Tutor – Generates learning content according to student needs.

🎯 Personalized Learning – Uses performance and weak concepts to personalize explanations.

🧩 Adaptive Quiz – Provides practice according to the student's learning level.

❌ Mistake Analysis – Identifies incorrect answers and areas needing improvement.

📊 Progress Tracking – Tracks scores and learning progress.

🔍 Weak Topic Detection – Finds concepts where the student needs more practice.

🔄 Review & Retest – Helps students revise weak areas and check improvement.

💡 Recommendations – Suggests the next learning activity.

🤖 AI Component

The AI component is the core of BrainByte's personalized learning system.

Student information and performance are converted into a personalized prompt. The prompt is sent to the OpenAI API, which generates learning content according to the student's needs.

AI Flow

Student Data
→ Personalized Prompt
→ OpenAI API
→ AI-Generated Lesson

The prompt can use:

Subject

Topic

Learning level

Learning goal

Diagnostic performance

Weak concepts

Previous quiz performance

🛠️ Technology Stack

Technology

Purpose

Python

Core programming and application logic

Streamlit

Web application and user interface

OpenAI API

AI-powered personalized learning

Pandas

Data handling and performance analysis

SQLite

Student and performance data storage

Git & GitHub

Version control and collaboration

🏗️ Project Structure

AI-Tutor/
│
├── .devcontainer/
│
├── data/
│
├── modules/
│   ├── Tutor.py
│   ├── personalization.py
│   ├── quiz_generator.py
│   ├── recommendation.py
│   └── scoring.py
│
├── pages/
│
├── app.py
├── requirements.txt
├── README.md
├── Sprints.md
├── FINAL PRESENTATION.pptx
└── .gitignore

👩‍💻 Manveet Kaur – Individual Contribution

Role: Member 2 – AI Tutor & Personalization

My main contribution focused on the AI Tutor and personalization part of BrainByte.

Contributions

Designed the personalized AI Tutor flow.

Created prompts based on the student's topic and learning level.

Worked on OpenAI API integration for AI-generated learning content.

Used student performance and weak concepts for personalization.

Worked on the AI Tutor interface and learning workflow.

My AI Flow

Student Data → Personalized Prompt → OpenAI API → AI-Generated Lesson

🚀 Installation & Setup

1. Clone the Repository

git clone <your-github-repository-link>
cd AI-Tutor

2. Install Dependencies

pip install -r requirements.txt

3. Configure OpenAI API Key

Keep the API key secure. Use Streamlit secrets or an environment variable.

Do not upload API keys to GitHub.

4. Run the Application

streamlit run app.py

The application will open in the browser.

📋 Development Plan

BrainByte was planned using a 10-sprint development cycle:

Project Setup

Student Profile

Diagnostic Test

AI Personal Tutor

Adaptive Quiz System

Mistake Analysis

Database & Performance Tracking

Weak Topic Detection

Progress Dashboard & Learning Path

Integration, Testing & Finalization

See Sprints.md for the detailed sprint plan.

🔄 Adaptive Learning Cycle

BrainByte continuously uses learning results to guide the next activity:

Assess → Learn → Practice → Analyze → Improve → Review

This makes the system different from a simple question-answer chatbot because the student's learning context is considered throughout the learning process.

🔮 Future Improvements

🎙️ Voice-based AI Tutor

📚 Support for more subjects and topics

📊 Advanced progress analytics

🧠 Smarter learning recommendations

🔄 More adaptive practice and revision

📱 Improved accessibility and user experience

🔐 Security

API keys should never be committed to GitHub.

Sensitive information should be stored using environment variables or Streamlit secrets.

.gitignore should be used for files containing secrets or local configuration.

📌 Project Status

BrainByte is an internship group project developed as part of the BCA 3rd Semester Internship at Hindu College.

The project focuses on combining AI with adaptive learning to provide students with a more personalized learning experience.

📞 Project Links

GitHub Repository: Add your final repository link here.

Live Demo: Add the deployed Streamlit application link here if available.

🙏 Thank You

BrainByte – Personal AI Tutor

Making learning more personalized, adaptive and student-focused
