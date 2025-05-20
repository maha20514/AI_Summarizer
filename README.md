# 🧠 AI Summarizer

AI Summarizer is a modern web application that leverages OpenAI's powerful language models to provide concise and intelligent summaries of lengthy articles, blog posts, or any text-based web content. It simplifies information consumption and enhances productivity for readers and researchers alike.

## 🔍 Features

* 🚀 Summarize long-form articles instantly using AI
* 🌐 Extract and summarize content from any valid URL
* 📜 Keep a searchable history of previously summarized links
* 🎨 Clean and responsive UI built with Next.js and Tailwind CSS
* ⚡ Powered by OpenAI GPT models for intelligent summarization

## 📷 Demo

Live demo: [https://ai-summarizer-app.vercel.app](#)

## 🛠️ Tech Stack

* Frontend: React + Next.js
* Styling: Tailwind CSS
* State Management: Redux Toolkit
* API Integration: OpenAI API
* Deployment: Vercel (or Netlify, if used)

## 🚀 Getting Started

### Prerequisites

* Node.js ≥ 18.x
* OpenAI API Key

### Installation

1. Clone the repository:

```bash
git clone https://github.com/maha20514/AI_Summarizer.git
cd AI_Summarizer
```

2. Install dependencies:

```bash
npm install
```

3. Create a .env.local file and add your OpenAI API key:

```env
NEXT_PUBLIC_OPENAI_API_KEY=your_openai_api_key_here
```

4. Run the development server:

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## 🧪 Usage

1. Paste any article or blog URL into the input field.
2. Click the "Summarize" button.
3. Wait for a brief moment while the AI processes the content.
4. View or copy your summary!

## 📁 Folder Structure

* components/: Reusable UI components
* app/: Next.js pages and routing
* redux/: State management logic
* utils/: Helper functions and constants
* public/: Static assets

## 🔐 Environment Variables

Make sure to include the following in your .env.local:

```env
NEXT_PUBLIC_OPENAI_API_KEY=your_openai_api_key
```

> Never expose your secret keys in public repositories.

## 🧠 How It Works

The app uses OpenAI’s GPT model to read and understand the content extracted from a given URL and then generates a short, contextually accurate summary of the main ideas.

