🌿 AI Agri Assistant
An intelligent, full-stack web application designed to be a modern farmer's digital companion. AI Agri Assistant leverages the power of AI and real-time data to provide crucial insights, from crop disease detection to market price analysis, helping farmers make informed decisions and improve productivity. 

✨ Core Features
This platform is packed with features designed to assist farmers at every stage of their work:

🤖 AI-Powered Crop Guide: Upload an image of a plant leaf and get an instant analysis of its health, potential diseases, and a complete guide covering soil, water, fertilizer, and pest control.

🌦️ Real-time Weather Hub: Get current weather, hourly/daily forecasts, and air quality data for any location. It also includes access to historical weather data for the past 7 days.

📈 Dynamic Market Prices: Fetches real-time vegetable prices from government APIs (data.gov.in) and uses an AI fallback for estimations, ensuring farmers always have price information.

🌱 Intelligent Crop Planner: Receive a detailed, customized farming plan based on crop type, land area, and location, complete with cost-profit analysis and a step-by-step timeline.

🛒 Buy/Sell Marketplace: A dedicated platform for farmers to sell their produce directly and for buyers to purchase fresh goods.

📰 Agri News Feed: Stay updated with the latest news and developments in the agricultural sector from India and around the world.

💵 Agri Loan Assistance: A streamlined portal for farmers to check loan eligibility and apply by submitting necessary documents.

💬 Conversational AI Assistant: A helpful chatbot, powered by Google's Gemini, ready to answer any questions about the application's features.

🛠️ Technology Stack
The application is built using a modern, robust set of technologies:

Backend: Python with Flask

Frontend: HTML5, CSS3, JavaScript

Database: Google Firebase (Firestore)

Authentication & User Management: Google Firebase (Authentication)

Image Storage: Cloudinary

AI & Machine Learning: Google Gemini Pro & Gemini Flash

External APIs:

OpenWeatherMap API

NewsAPI

Google Custom Search Engine (CSE) API

Data.gov.in API

Deployment: The application is structured for easy deployment on platforms like Vercel or any WSGI server.

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Python 3.8+ and Pip

Node.js (for potential frontend tooling)

A Firebase project with Firestore and Authentication enabled.

A Cloudinary account.

Installation & Setup
Clone the Repository:

Bash

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Set up Python Backend:

Create and activate a virtual environment:

Bash

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required packages from requirements.txt:

Bash

pip install -r requirements.txt
Configure Environment Variables:

Create a .env file in the root directory.

Copy the contents from the provided .env file and fill in your unique API keys and credentials for each service.

Firebase Credentials:

From your Firebase project settings, generate a new private key for the Service Account.

Rename the downloaded JSON file to serviceAccountKey.json and place it in the project's root directory.

Run the Flask Application:

Bash

python app.py
The application will be running on http://127.0.0.1:5000.
