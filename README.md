🥗 MacroSnap — AI Nutrition Buddy

MacroSnap is an AI-powered nutrition chatbot built with Streamlit, Google Gemini, and Twilio WhatsApp. It lets users enter their name and WhatsApp number once, then chat with an AI nutrition buddy to estimate calories and macronutrients from either text descriptions or photos of meals.

After logging meals, users can generate a concise nutrition summary and send it directly to their WhatsApp number with a single click.

✨ Features

💬 Chat with an AI nutrition assistant

📸 Analyze meal photos using Gemini's vision capabilities

🍽️ Estimate calories, protein, carbohydrates, and fat

🧠 Maintain conversation context for follow-up questions

📊 Generate a running nutrition summary

📱 Send the final summary directly to WhatsApp using Twilio

🔐 Keep API keys and credentials securely in Streamlit secrets

☁️ Deploy easily with Streamlit Community Cloud

🛠️ Tech Stack

Python

Streamlit — web interface

Google Gemini — AI chat and image analysis

Twilio — WhatsApp messaging

GitHub — source control and deployment

📁 Project Structure
macrosnap/
├── app.py
├── prompts.py
├── requirements.txt
├── .gitignore
└── .streamlit/
    └── secrets.toml.example

🚀 Getting Started

Clone the repository.

Create and activate a Python virtual environment.

Install the dependencies with pip install -r requirements.txt.

Create .streamlit/secrets.toml using the provided example.

Add your Gemini API key and Twilio credentials.

Run the application:

streamlit run app.py


The app will be available locally at http://localhost:8501.

🔑 Required Services

Before running MacroSnap, you'll need:

A Google AI Studio account and Gemini API key

A Twilio account with WhatsApp Sandbox access

A Twilio WhatsApp Content Template for sending the nutrition summary

⚠️ Disclaimer

MacroSnap provides AI-generated estimates, not medically verified nutritional information. Calorie and macronutrient values can vary depending on ingredients, portion sizes, preparation methods, and image quality. The project is intended for educational and demonstration purposes.

🎯 Project Goal

MacroSnap demonstrates how AI vision, conversational AI, and WhatsApp messaging can be combined into a practical end-to-end application without training a custom machine-learning model.

Built with ❤️ using Python, Streamlit, Gemini, and Twilio.
