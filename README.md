# AI Summarizer – AI-Powered Article Summarization Web App

AI Summarizer is a full-stack web application that extracts and summarizes online articles in real time using AI-powered APIs. The application allows users to submit a URL and instantly receive a concise, readable summary of the content.

🔗 **Live Demo:** https://ai-summarizer-two-zeta.vercel.app/
📦 **Repository:** https://github.com/maha20514/AI_Summarizer

---

## 🚀 Features

* Extracts article content directly from URLs
* Generates concise summaries using AI APIs
* Clean and responsive user interface
* Fast client-server communication for real-time results
* Error handling for invalid or unsupported URLs

---

## 🧱 Tech Stack

**Frontend**

* React
* Next.js
* Tailwind CSS

**Backend / APIs**

* Node.js
* RapidAPI Article Extractor
* OpenAI API for summarization

**Deployment**

* Vercel

---

## 🏗️ Architecture Overview

The application follows a client–server model:

1. The user submits an article URL through the frontend.
2. The backend retrieves the article content using an extraction API.
3. The content is processed and sent to an AI summarization service.
4. The summarized result is returned and displayed in the UI.

This architecture ensures modular API integration and allows the summarization engine to be replaced or upgraded easily.

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/maha20514/AI_Summarizer.git
cd AI_Summarizer
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key
RAPIDAPI_KEY=your_api_key
```

### 4. Run the development server

```bash
npm run dev
```

The app will be available at:

```
http://localhost:3000
```

---

## 🧪 Possible Improvements

* Add history of previously summarized articles
* Support multiple languages
* Implement caching to reduce API costs
* Add user authentication and saved summaries

---

## 👩‍💻 Author

**Maha Aledresi**
Backend / Full-Stack Developer

* Portfolio: https://maha-portfolio-six.vercel.app/
* LinkedIn: https://www.linkedin.com/in/maha-aledresi-32a043205/
