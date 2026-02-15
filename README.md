# QA Master -- Testing Learning Platform

QA Master is a React-based Single Page Application (SPA) designed as a
structured 40-day learning program for Software Testing. It combines
static curriculum content with AI-generated lessons and quizzes, along
with gamified progress tracking.

------------------------------------------------------------------------

## 🚀 Features

-   40-Day Structured Curriculum
    -   Manual Testing (Days 1--10)
    -   Java Essentials (Days 11--15)
    -   Selenium WebDriver (Days 16--25)
    -   TestNG (Days 26--30)
    -   Cucumber BDD (Days 31--35)
    -   Framework Design (Days 36--40)
-   AI-Powered Lesson Generator
-   Dynamic AI Quizzes with Instant Feedback
-   Assignment-Based Learning
-   Responsive Sidebar Navigation
-   Dark Mode UI using Tailwind CSS

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Frontend: React 18
-   Styling: Tailwind CSS (Dark Theme)
-   Icons: Custom SVG (Lucide-style)
-   AI Integration: Google Gemini API

------------------------------------------------------------------------

## 📦 Installation & Setup

### 1. Clone the Repository

git clone https://github.com/your-username/qa-master.git cd qa-master

### 2. Install Dependencies

npm install

### 3. Add Your Gemini API Key

IMPORTANT:

Due to security restrictions, my API key cannot be shared or used
directly.

To enable AI features:

1.  Open the project folder
2.  Navigate to: /src/addKey.js
3.  Add your Google Gemini API key:

export const API_KEY = "YOUR_GEMINI_API_KEY_HERE";

4.  Save the file

Without adding your own API key, AI-generated lessons and quizzes will
not work.

### 4. Run the Application

npm start

The app will run at: http://localhost:3000

------------------------------------------------------------------------

## 🔐 API Key Disclaimer

-   The repository does NOT include an active Gemini API key.
-   You must provide your own API key.
-   Never commit your API key to a public repository.
-   Use environment variables for production deployment.

------------------------------------------------------------------------

## 🎯 Future Enhancements

-   User Authentication
-   Persistent Database Storage
-   Admin Dashboard
-   Leaderboard & Gamification Improvements
-   Deployment Support (Vercel / Netlify)

------------------------------------------------------------------------

## 📄 License

This project is for educational purposes.
