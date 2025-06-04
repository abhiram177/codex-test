# Gemini Chatbot Example

This simple project demonstrates a web-based chatbot using Google's Gemini API.

## Setup

1. Install dependencies:
   ```bash
   pip install flask google-generativeai python-dotenv
   ```
2. Create a `.env` file with your API key. This file is already listed in
   `.gitignore` so the key remains private:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
3. Run the application:
   ```bash
   python main.py
   ```
4. Open `http://localhost:5000` in your browser to chat with Gemini.

## Files
- `main.py` – Flask server using `gemini-2.0-flash` model.
- `templates/index.html` – basic chat UI.
- `static/styles.css` – minimal styling.
- `static/app.js` – handles sending messages to the server.
