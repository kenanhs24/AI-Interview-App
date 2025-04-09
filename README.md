# AI-Interview-App
# AI-Interview-Power
AI Interview Practice App

AI Interview Practice is a web application designed to simulate realistic technical interviews using AI. It supports multiple roles, frameworks, and programming languages. The app allows users to input their desired job role and receive interview questions and answers in real-time, with transcript history and voice support.

🚀 Features

🎯 Mock Interview Simulation
Start a mock interview session tailored to specific roles (e.g., SDET, Developer, QA, PM, etc.).
🧠 AI-Generated Questions and Answers
Uses an AI backend to generate 3–5 technical questions and answers per session.
💬 Live Transcript Panel
Displays a complete transcript of the mock interview—both questions and AI answers.
🎙️ Speech Recognition (Voice Input)
Ask questions via voice input using built-in speech-to-text.
🔊 Text-to-Speech for Questions
Interview questions can be played back using text-to-speech.
🌐 No Page Reloads
Built with modern JavaScript to support dynamic interactions without full page reloads.
🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Java Spring Boot
AI Integration: Google Gemini API (Option 2)
Voice Features: Web Speech API
📦 Setup Instructions

Clone the Repository
git clone https://github.com/your-username/ai-interview-practice.git
cd ai-interview-practice
Backend Setup (Spring Boot)
Open the project in IntelliJ IDEA
Configure the application.properties or application.yml for your API key
Run the Spring Boot application
Frontend Setup
Open index.html in any browser (or serve via a local HTTP server)
Ensure the backend is running and accessible
Usage
Select job role, language, and framework
Click “Start Mock Interview”
View questions and answers in the transcript area
Use “Interview Me” for voice-based interaction
📌 Notes

Ensure your browser supports the Web Speech API for voice features
The app is in active development. Contributions and feedback are welcome!
📄 License

MIT License

To get a free Gemini API key (for Google's Gemini AI), follow these simple steps:

✅ Steps to Get a Free Gemini API Key
Go to Google AI Studio
Visit: https://makersuite.google.com/
Sign in with your Google Account
Use your Gmail or Google Workspace account.
Accept Terms & Conditions
If it’s your first time, you’ll be asked to agree to terms of use and enable the API.
Create a New Project (if needed)
Open Google Cloud Console
Click on the project dropdown > New Project
Give it a name, then click Create
Enable Gemini API
In the same Cloud Console, go to Gemini API page
Click Enable
Get Your API Key
Go to Credentials page
Click Create Credentials > API Key
Copy the generated key.
💡 Notes:
Quota: Google offers free usage with daily limits (varies by model).
Free Tier (as of now):
gemini-pro: 60 requests/minute for free.
gemini-pro-vision: Limited number of requests.
No credit card needed for API key (unless you want paid quota).
