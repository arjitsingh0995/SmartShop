🛍️ SmartShop — AI-Powered E-commerce Platform

SmartShop is a modern, fully responsive e-commerce application featuring a unique AI Bargaining Agent. Built with React and powered by Google's Gemini API, it enables users to negotiate prices in real time with an intelligent virtual sales manager before completing a purchase.

✨ Key Features
🛒 Full-Featured Shopping Cart

Add items to the cart

Update quantities

View real-time price breakdowns

🤖 AI Bargaining Agent

Negotiates discounts dynamically

Follows a strict psychological sales strategy

Acts as a virtual sales manager inside the cart page

🔍 Search & Filter

Filter by category: Mobiles, Fashion, Electronics

Instant text-based search

🎨 Modern Earthy UI

Gen-Z inspired warm, earthy aesthetics

Primary palette: #5D4037 (Brown)

Clean, minimal, premium design

📱 Fully Responsive

Optimized for mobile, tablet, and desktop for a seamless shopping experience.

⚡ High Performance

Built with React 19, TypeScript, Tailwind CSS, and Vite for a fast, zero-runtime overhead UI.

🛠️ Tech Stack
Layer	Technology
Frontend	React (v19), TypeScript
Styling	Tailwind CSS
Icons	Lucide React
AI/LLM	Google Gemini API
Build Tool	Vite
🚀 Getting Started

Follow the steps below to run SmartShop locally on your machine.

Prerequisites

Node.js (v18+)

npm or yarn

A Google Gemini API Key

📦 Installation
# Clone the repository
git clone https://github.com/yourusername/smart-shop.git

# Navigate into the project folder
cd smart-shop

# Install dependencies
npm install
# or
yarn install

▶️ Running the Project
# Start development server
npm run dev
# or
yarn dev

🔑 Environment Setup

Create a .env file in the project root:

VITE_GEMINI_API_KEY=your_api_key_here

📂 Project Structure
smart-shop/
├── src/
│   ├── main.tsx        # Main React entry point & App Logic
│   ├── index.css       # Tailwind directives (if using local CSS)
│   └── vite-env.d.ts   # TypeScript definitions
├── index.html          # HTML entry point (Tailwind CDN included)
├── package.json        # Dependencies
├── tsconfig.json       # TypeScript config
└── README.md           # Project documentation

