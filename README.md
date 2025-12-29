# Chatbot-GenAI

A simple AI chatbot using **Google Gemini API** integrated with **Python Flask**. This project demonstrates building a chatbot capable of handling user queries, processing responses, and deploying via a web interface.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Key Concepts](#key-concepts)
- [To-Do / Homework](#to-do--homework)

---

## Overview
Gemini AI Chatbot is built to interact with users through a web application. The client sends messages through a browser, which are processed by the Gemini API on the server-side. Responses are then sent back and displayed in the chat interface.

The system is stateless, meaning no memory is stored between sessions. The chatbot can be extended with advanced features like prompt chaining and embedding-based retrieval.

---

## Features
- Web-based chat interface
- Communication with Gemini AI API
- Stateless design (no persistent memory)
- Supports POST requests for chat endpoints
- Uses Flask for server-side application
- JSON responses for frontend integration

---

## Technologies
- Python 3.x
- Flask (`Flask`, `request`, `jsonify`, `render_template`)
- Gemini AI API
- HTML/CSS/JavaScript for frontend
- Virtual environment (`miniconda` or `anaconda`)
- Optional: NLP libraries for preprocessing and embedding

---

## Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Gemini-Chatbot.git
   cd Gemini-Chatbot
2. **Create virtual environment**
   ```bash
   -conda create -p venv python==3.11
   -conda info --envs
   -conda activate tf
4. **Install dependencies**
   ```bash
   -pip install flask requests
# Add any other required packages
4. **Set up Gemini API**
   - Create a new API key in Google AI Studio
   - Add your API key to the project configuration
## Usage
1. **Run the Flask App:**
   ```bash
   -python app.py
3. **Open the browser and go to**
   ```bash
   -http://localhost:8000
5. **Type your message and interact with the chatbot
   
## Key Concepts

### Flask App
- Creates a web application instance using Flask.
- Handles routing and request/response cycles.
### Routes
- `/` → Returns the `index.html` page.
- `/chat` → Accepts `POST` requests with user messages and returns AI-generated responses.
### Request & JSON
- `request.json["message"]` → Retrieves the user's input message.
- `jsonify()` → Sends the AI-generated response back in JSON format.
### Gemini AI Client
- Generates intelligent responses from the AI model based on user input.
### NLP Preprocessing (Optional)
- Tokenization
- Normalization
- Stemming
- Lemmatization
### Embeddings & Cosine Similarity
- Used for semantic search or **RAG (Retrieval-Augmented Generation)**.
- Helps find relevant information or generate context-aware responses.

## License
This project is open-source. Feel free to use and modify it for learning purposes.

You can copy all of this directly into a file named `README.md` in your project.  

If you want, I can also make a **version with example `app.py` code and HTML integration** ready to run, so someone can start the chatbot immediately.  

Do you want me to do that?

## 
**Done by:** Gude Gopi Krishna



