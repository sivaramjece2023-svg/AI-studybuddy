📚 AI Learning Buddy
Because sometimes textbooks just don't speak your language.

Welcome! AI Learning Buddy is a personalized tutor built to help students (and curious minds) break down complex topics. Instead of a generic chatbot, this buddy adapts its explanations based on how much you already know.

🌟 Why I built this
I wanted to create a tool that doesn't just give answers, but actually teaches. Whether you're a beginner trying to understand "What is a variable?" or an advanced student diving into "Quantum Computing," this app adjusts its tone and depth to match your level.

🚀 Features
Adaptive Difficulty: Choose between Basic, Intermediate, and Advanced modes.

Contextual Memory: It remembers your previous questions so you can have a real conversation.

Powered by Gemini 2.5 Flash-Lite: Optimized for speed and high-volume learning sessions (no more "Quota Exceeded" errors halfway through a study session!).

Clean UI: A simple, distraction-free chat interface built with Streamlit.

🛠️ Quick Start (Get it running in 2 mins)
1. Clone this project

Bash

git clone https://github.com/your-username/AI-Learning-Buddy.git
cd AI-Learning-Buddy
2. Install the essentials I'm using the new Google GenAI SDK (version 2026), so make sure your libraries are up to date:

Bash

python -m pip install -U google-genai streamlit python-dotenv
3. The Secret Sauce (API Key) Create a file named .env in the root folder and drop your Gemini API key inside:

Plaintext

GEMINI_API_KEY=your_actual_key_here
4. Launch!

Bash

python -m streamlit run studybuddy.py
📂 Project Structure
studybuddy.py: The heart of the app (Streamlit UI + Gemini Logic).

.env: (Hidden) Where your API keys live safely.

requirements.txt: A list of the ingredients used to build this.

🧠 My Roadmap / Future Ideas
[ ] PDF Support: I want to make it so you can upload a textbook chapter and ask questions about it.

[ ] Voice Mode: Speak to your tutor directly.

[ ] Quiz Mode: Have the tutor test you at the end of a session.

🤝 Contributing
If you have a cool idea to make this a better tutor, feel free to fork this repo and submit a PR! I'm always looking to learn.

