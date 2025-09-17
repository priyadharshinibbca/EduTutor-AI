# EduTutor AI: Personalized Learning with Generative AI and LMS Integration

EduTutor AI is an AI-powered personalized education platform that transforms the way students learn and educators evaluate progress. Built with IBM Watsonx and Granite foundation models, EduTutor AI integrates seamlessly with Google Classroom and leverages modular architecture to deliver personalized, adaptive, and data-driven learning experiences.



🚀 Features :

Personalized Learning Experience

AI-driven quiz generation based on course content.

Real-time student evaluation and instant feedback.

Adaptive learning paths aligned with academic levels.


Educator Dashboard & Performance Insights

Real-time performance tracking for individual students and classes.

Access to quiz history, scores, and progress insights.

Data-powered teaching recommendations via Pinecone vector database.


Diagnostic Testing & Adaptive Quizzing

Initial AI-driven diagnostic test to evaluate baseline knowledge.

Quizzes adapt dynamically based on student performance and learning needs.


Google Classroom Integration

Direct sync with Google Classroom courses, subjects, and class data.

Automatic topic-based quiz generation.

Ensures seamless curriculum alignment.




📌 Scenarios

1. Personalized Learning Experience

A student logs in using Google Classroom credentials. EduTutor AI analyzes course data, generates quizzes with Granite LLM, and provides instant AI-driven feedback—crafting a personalized learning journey.

2. Educator Dashboard & Performance Insights

Educators view live student performance via the dashboard, including quiz history, topic attempts, and insights from Pinecone. Teachers can tailor lessons to student needs.

3. Diagnostic Testing & Adaptive Quizzing

Students start with a Watsonx-powered diagnostic test. Quiz difficulty and content adapt in real-time, keeping learning engaging and challenging.

4. Google Classroom Integration

EduTutor AI automatically syncs student data, subjects, and class names from Google Classroom. Quizzes align directly with the curriculum for consistency.



🏗️ Tech Stack

AI Models: IBM Watsonx, Granite Foundation Models

Database: Pinecone Vector DB

LMS Integration: Google Classroom API

Backend: Python, FastAPI / Flask

Frontend: React + TailwindCSS

Deployment: Docker, Kubernetes (optional for scaling)




📂 Project Structure

EduTutor-AI/
├── backend/        # APIs, AI integration, database handlers
├── frontend/       # React-based UI
├── docs/           # Documentation & project scenarios
├── tests/          # Unit & integration tests
└── README.md       # Project overview


⚡ Getting Started

Prerequisites

Python 3.9+

Node.js 18+

Google Classroom API credentials

IBM Watsonx API access

Pinecone account & API key


Installation

1. Clone the repository

git clone https://github.com/yourusername/EduTutor-AI.git
cd EduTutor-AI


2. Backend Setup

cd backend
pip install -r requirements.txt


3. Frontend Setup

cd frontend
npm install
npm run dev


4. Environment Variables
Create a .env file in backend/ with:

WATSONX_API_KEY=your_key_here
PINECONE_API_KEY=your_key_here
GOOGLE_CLASSROOM_CLIENT_ID=your_client_id
GOOGLE_CLASSROOM_CLIENT_SECRET=your_secret


5. Run Application

# Start backend
uvicorn main:app --reload

# Start frontend
npm run dev



📊 Future Enhancements

Multi-language support for global education.

AI-powered student chat assistant for doubt-solving.

Integration with additional LMS platforms (Moodle, Canvas, Blackboard).

Advanced analytics for educators with predictive insights.




🤝 Contributing

Contributions are welcome! Please fork the repo, create a branch, and submit a pull request.



📜 License

This project is licensed under the MIT License.
