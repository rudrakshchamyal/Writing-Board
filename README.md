# Writing-Board 🎓✨

A full-stack web application designed for educators. This digital whiteboard allows teachers to handwrite text and complex mathematical equations, which are instantly processed by Google's Gemini AI, typeset using MathJax, and automatically plotted on an interactive Desmos graph.

## ✨ Features
* **Smart OCR:** Uses Google's `gemini-2.5-flash` multimodal AI to read messy handwriting and distinguish between regular English text and LaTeX math.
* **Auto-Graphing:** Automatically extracts LaTeX equations and plots them on an integrated Desmos Graphing Calculator.
* **Teacher-Optimized Workflow:** Features a toggleable "Auto-Convert" mode and a manual mode to prevent API rate-limiting during long explanations.
* **Native Night Mode:** The canvas flips colors natively, providing a dark chalkboard experience that secretly sends white-background images to the AI for maximum accuracy.
* **Full Stack:** Python/Flask backend communicating with a vanilla HTML/CSS/JS frontend.

## 🛠️ Tech Stack
* **Frontend:** HTML5 Canvas, CSS3, JavaScript (Vanilla)
* **Backend:** Python, Flask, Flask-CORS
* **APIs & Libraries:** Google Generative AI (Gemini), MathJax, Desmos API

## 🚀 How to Run Locally

### 1. Set up the Backend (Python)
Ensure you have Python installed. Then, install the required dependencies:
```bash
pip install flask flask-cors google-generativeai pillow

2. Add your API Key
You will need a free Google Gemini API key from Google AI Studio.
Open app.py and replace the placeholder string with your actual key:

genai.configure(api_key="YOUR_API_KEY_HERE")

3. Start the Server
Run the Flask server:
python app.py
The server will start running on http://127.0.0.1:5000.

4. Open the Frontend
Simply double-click index.html to open it in any modern web browser. Draw on the canvas and click "Convert"!

🧠 About this Project
I built this project as a hands-on way to learn full-stack development, API integration, and how to harness Large Language Models (LLMs) in software development. The code was written collaboratively using AI assistance, serving as an incredible learning journey into backend routing, CORS handling, canvas manipulation, and rate-limit management.

### Steps to paste it:
1. Go back to your GitHub repository.
2. Click the **pencil icon (✏️)** on the README.
3. Delete whatever mess is currently in that box.
4. Paste the text you just copied from the block above.
5. Click **Commit changes**. 

It should format beautifully this time!
