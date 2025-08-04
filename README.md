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

```
movie-sentiment-analyzer/
├── public/
│   └── data/
│       └── mini_imdb_reviews.csv        # Sample dataset
├── src/
│   ├── components/
│   │   ├── Header.tsx                   # App title/header
│   │   ├── ReviewInput.tsx              # Input form
│   │   ├── SentimentResult.tsx          # Display results
│   │   └── Features.tsx                 # Features list
│   ├── hooks/
│   │   └── useSentiment.ts              # Custom sentiment logic
│   ├── services/
│   │   └── sentimentService.ts          # Sentiment detection logic
│   ├── types/
│   │   └── index.ts                     # Type definitions
│   ├── App.tsx                          # Main component
│   ├── main.tsx                         # Entry point
│   └── index.css                        # Global styles
├── package.json
├── tailwind.config.js
└── README.md
```

🎯 How It Works

1. Input: User enters a movie review

2. Sentiment Analysis: ML logic processes the text

3. Movie Detection: Extracts movie title & fetches IMDb rating/poster

4. Display: Shows sentiment, rating, and animations


🎨 UI & Design

Glassmorphism UI with backdrop blur

Responsive layout for all screen sizes

Gradient backgrounds

Framer Motion animations

Modern typography with Inter font


🔧 Customization Tips

To add more movies to the demo database, edit:// src/services/sentimentService.ts
```
const movieDatabase: Record<string, MovieInfo> = {
  'your-movie': {
    title: 'Your Movie',
    poster: 'https://your-url.jpg',
    rating: 8.5,
    year: 2023
  }
}
```

To customize styling, edit:

src/index.css

tailwind.config.js

🧠 Machine Learning Notes

This demo uses a basic keyword-based approach. For production:

Use BERT / SVM / Logistic Regression

Train on a full IMDb or Rotten Tomatoes dataset

Serve model via Flask, FastAPI, or TensorFlow Serving

Include metrics (accuracy, F1-score, etc.)

🛰 Deployment

On Netlify

1.Build the project: npm run build

2.Deploy to Netlify with the dist folder

3.Configure environment variables if needed


On Vercel
1.Connect your GitHub repository to Vercel

2.Vercel will automatically detect the Vite configuration

3.Deploy with zero configuration


🤝 Contributing

1. Fork the repo

2. Create a branch: git checkout -b feature-name

3. Commit changes: git commit -m "Add feature"

4. Push: git push origin feature-name

5. Open a Pull Request


🙏 Acknowledgments

IMDb for poster and rating APIs

Tailwind CSS

Framer Motion

Lucide Icons





