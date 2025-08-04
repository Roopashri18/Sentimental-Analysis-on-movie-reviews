🎬 Movie Sentiment Analyzer
An interactive web application that analyzes the sentiment of movie reviews using machine learning. Built with React, TypeScript, and Tailwind CSS for a modern, responsive user experience.

✨ Features
AI-Powered Sentiment Analysis – Advanced ML algorithms to classify sentiment (Positive/Negative)
Instant Results – Real-time output with confidence scores
Movie Detection – Automatically identifies movie titles and fetches IMDb data
Beautiful UI – Glassmorphism, gradient backgrounds, and smooth animations
=Pre-Loaded Reviews – Sample data included for demo/testing

 🚀 Live Demo

🔗 [View Live App](https://sentiment-analysis-on-movies-review.netlify.app/)

 🛠 Tech Stack

| Area        | Tech Used                    |
|-------------|------------------------------|
| Frontend    | React 18 + TypeScript        |
| Build Tool  | Vite                         |
| Styling     | Tailwind CSS                 |
| Animations  | Framer Motion                |
| Icons       | Lucide React                 |
| Deployment  | Netlify / Vercel             |



📦 Installation

bash
1.Clone the repository
git clone https://github.com/yourusername/movie-sentiment-analyzer.git
cd movie-sentiment-analyzer

2,Install dependencies
npm install

3.Start development server
npm run dev

Open http://localhost:5173 or check the live deployment.

🏗 Project Structure

movie-sentiment-analyzer/
├── src/
│   ├── components/
│   │   ├── Header.tsx               # App header with title
│   │   ├── ReviewInput.tsx          # Review input form
│   │   ├── SentimentResult.tsx      # Results display
│   │   └── Features.tsx             # Features showcase
│   ├── hooks/
│   │   └── useSentiment.ts          # Custom hook for sentiment analysis
│   ├── services/
│   │   └── sentimentService.ts      # Sentiment analysis logic
│   ├── types/
│   │   └── index.ts                 # TypeScript type definitions
│   ├── App.tsx                      # Main application component
│   ├── main.tsx                     # React entry point
│   └── index.css                    # Global styles
├── package.json
├── tailwind.config.js
└── README.md

