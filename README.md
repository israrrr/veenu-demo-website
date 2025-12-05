# veenu-demo-website
VEENU | Premium Highway Dining Experience 🍛✨

<!-- Tip: Upload a screenshot of the Hero section to your repo and link it here -->

View Live Demo <!-- Add your Netlify/Vercel/GitHub Pages link here -->

📖 About The Project

VEENU is an immersive, consumer-facing website designed for a premium highway restaurant located on the Indore Bypass.

Originally conceptualized as a branding case study, this project was evolved into a fully functional, high-performance landing page. It focuses on translating the physical ambiance of the restaurant into a digital experience through fluid motion, cinematic storytelling, and AI-driven interactivity.

✨ Key Features

🎨 Immersive UI/UX

Cinematic Hero Section: Video-dominant background with parallax depth.

Premium Scroll Experience: Implemented Lenis Smooth Scroll for a weighted, luxurious feel.

Theatrical Reveals: Custom "Curtain" preloader and scroll-triggered element reveals using GSAP.

Interactive Menu: Hover-responsive grids showcasing signature dishes.

🤖 AI Concierge (Powered by Gemini)

Virtual Sommelier: Integrated a floating chat widget powered by the Google Gemini API.

Context-Aware: The AI is trained on Veenu's specific menu (Curries, Chai, Desserts).

Personalized Recommendations: Users can describe their mood (e.g., "I want something spicy" or "Comfort food"), and the AI curates a 3-course meal plan.

🛠 Technical Highlights

Responsive Design: Fully fluid layout using Tailwind CSS.

Performance Optimized: Lazy loading strategies and optimized asset handling.

Glassmorphism: Dynamic navbar that adapts to scroll position.

🧰 Tech Stack

HTML5

Tailwind CSS (CDN)

Vanilla JS (ES6+)

GSAP & ScrollTrigger

Google Gemini API

Lenis (Smooth Scrolling)

🚀 Getting Started

To run this project locally, follow these steps:

Prerequisites

You will need a Google Gemini API Key. Get one for free at Google AI Studio.

Installation

Clone the repository

git clone [https://github.com/your-username/veenu-website.git](https://github.com/your-username/veenu-website.git)


Navigate to the project folder

cd veenu-website


Add your API Key

Open veenu-official.html (or index.html) in your code editor.

Locate the JavaScript section near the bottom.

Find the line: const apiKey = "";

Paste your Gemini API key inside the quotes.

Run the project

Simply open the HTML file in your browser, or use the "Live Server" extension in VS Code.

📂 Project Structure

├── assets/
│   ├── interior.mp4        # Hero background video
│   ├── israr3.JPG          # Founder image
│   ├── pattern01.png       # Texture overlay
│   └── vcr-exterior.png    # Menu images
├── index.html              # Main application file
└── README.md               # Project documentation


📸 Screenshots

Hero Section

AI Concierge





<!-- Tip: Take screenshots of your site and link them here -->

⚠️ Note on Security

This project uses a client-side API key injection for demonstration purposes. In a production environment, API calls should be routed through a backend server to keep the API key hidden from the frontend.

👤 Author

Israr Ahmed

Portfolio: LinkTree

Email: i.israr.ahmed08@gmail.com

If you liked this project, please give it a ⭐!
