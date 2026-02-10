📌 Auto Webpage Title Saver

A simple Chrome Extension that automatically captures the titles of webpages you visit and saves them into a text file.

🚀 Project Overview

Auto Webpage Title Saver is a browser automation project that records webpage titles whenever a page is opened or refreshed. The titles are automatically saved into a titles.txt file in the Downloads folder.

This project demonstrates basic browser automation using Chrome Extensions and JavaScript.

🎯 Features

✅ Automatically detects webpage titles
✅ Saves titles to a text file
✅ Works in the background
✅ No manual input required
✅ Lightweight and fast

🛠️ Technologies Used

JavaScript

Chrome Extension API (Manifest V3)

Browser automation concepts

📂 Project Structure
AutoTitleSaver/
│── manifest.json
│── background.js
│── README.md

⚙️ Installation Guide
Step 1: Download Project

Download or clone this repository.

git clone <your-repo-link>

Step 2: Open Chrome Extensions

Open Chrome and go to:

chrome://extensions

Step 3: Enable Developer Mode

Turn on Developer Mode (top-right corner).

Step 4: Load Extension

Click Load unpacked and select the project folder.

▶️ How to Use

Install the extension

Open any website

The title is automatically saved

Check titles.txt in Downloads folder

📄 Example Output
Google
YouTube
Wikipedia
Amazon
GitHub

💡 Use Cases

Track browsing history

Research data collection

Productivity monitoring

Learning browser automation

⭐ Learning Outcomes

This project helps learn:

Chrome Extension development

Event-driven programming

File handling in browser

Automation concepts

🔮 Future Improvements

Save URL with title

Add date & time stamps

Export to CSV

Create dashboard UI

Cloud storage support


🤖 Python Web Chatbot (Flask)

A simple rule-based web chatbot built using Python and Flask with a floating chat widget UI.
This chatbot can answer general questions, basic knowledge queries, and greetings using a JSON knowledge base.

🚀 Features

✅ Floating chat button on webpage
✅ Rule-based responses
✅ JSON-based Q&A knowledge base
✅ Date and time responses
✅ Simple and clean UI
✅ Easy to expand and customize
✅ Beginner-friendly project

🛠️ Tech Stack

Python

Flask

HTML

CSS

JavaScript

JSON

📁 Project Structure
chatbot/
│
├── app.py
├── qa.json
├── templates/
│   └── index.html
└── static/
    ├── style.css
    └── script.js

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/chatbot.git
cd chatbot

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv .venv
.\.venv\Scripts\activate

3️⃣ Install Dependencies
pip install flask

4️⃣ Run the Application
python app.py

5️⃣ Open in Browser
http://127.0.0.1:5000


Click the 💬 button to start chatting!

💬 Example Questions

hello

how are you

what is AI

capital of India

tell me a joke

time / date

🧠 How It Works

User sends a message from the web UI

Flask backend receives it

Bot checks Q&A in qa.json

If matched → returns answer

Otherwise → default response

🎯 Use Cases

College mini project

Flask learning project

Beginner AI chatbot demo

Web development practice

🔮 Future Improvements

AI API integration (Gemini / ChatGPT)

Voice input support

Database storage

User authentication

Better UI/UX design
