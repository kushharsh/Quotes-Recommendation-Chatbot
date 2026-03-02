InspoBot: Quotes Recommendation System
InspoBot is a functional web application designed to provide motivational and success-related quotes. It features a custom-trained logic engine built with the Rasa framework and a modern web interface that allows for a smooth user experience.

📌 Project Overview
The goal of this project was to build a chatbot capable of understanding user moods and providing relevant quotes in real-time. This project covers the full development lifecycle:

Data Collection: Designing intents for motivation and success.

Model Building: Training the NLU (Natural Language Understanding) pipeline.

UI/UX Design: Creating a professional "Landing Page to Chatbot" interface.

Integration: Connecting the Rasa "Brain" to a web browser via REST API.

🛠️ Tech Stack
Logic Engine: Rasa Open Source (Python 3.10.11).

Front-End: HTML5, CSS3 (Glassmorphism design with animations).

Integration: REST API via Rasa Webhooks.

Version Control: Git & GitHub.

📂 Repository Structure
/data: Training examples for user intents (NLU).

domain.yml: Defines the bot's universe, including intents and responses.

config.yml: Settings for the NLU processing pipeline.

index.html: The professional landing page and interactive chat widget.

⚙️ Setup & Installation
1. Local Environment
Ensure you have Python 3.10.11 and Git installed. Clone this repository and activate the virtual environment:

PowerShell
.\venv\Scripts\activate
2. Running the Engine
The chatbot logic must be active to process messages. Start the Rasa server in your terminal:

PowerShell
rasa run --enable-api --cors "*"
3. Using the Web Interface
Once the server is "up and running," open index.html in your browser.

Click the "Need a Quote?" button.

Type a message like "I want to succeed" or "Give me some motivation".

The bot will process the intent and display a relevant quote.