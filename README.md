📚 AI Learning Buddy  
 Because sometimes textbooks just don’t speak your language.

AI Learning Buddy is a *personalized AI tutor* designed to help students and curious minds truly *understand* complex topics — not just memorize answers.  
Unlike generic chatbots, this buddy *adapts its explanations* based on your knowledge level.

---

 🌟 Why I Built This

I wanted to create a tool that **teaches like a human tutor**, not just responds like a search engine.

- A beginner can ask: *“What is a variable?”*
- An advanced learner can explore: *“How does Quantum Computing work?”*

The AI automatically adjusts its *tone, depth, and complexity* so learning feels natural and stress-free.

---

 🚀 Features

- 🧠 Adaptive Difficulty  
  Choose between **Basic**, **Intermediate**, and **Advanced** modes.

- 💬 Contextual Memory
  Remembers your previous questions for a continuous, meaningful conversation.

- ⚡Powered by Gemini 2.5 Flash-Lite 
  Optimized for **speed** and **high-volume learning**  
  (No more *“Quota Exceeded”* errors mid-study session!)

- 🎨 Clean & Minimal UI
  Built with **Streamlit** for a distraction-free learning experience.

---

 🛠️ Quick Start (Run it in 2 Minutes)

1️⃣ Clone the Repository:

git clone https://github.com/your-username/AI-Learning-Buddy.git

cd AI-Learning-Buddy

2️⃣ Install Dependencies:
This project uses the Google GenAI SDK (2026). Make sure everything is up to date:

python -m pip install -U google-genai streamlit python-dotenv

3️⃣ Add Your API Key (The Secret Sauce 🔑):
Create a .env file in the root directory and add 
your Gemini API key:

GEMINI_API_KEY=your_actual_key_here

4️⃣ Launch the App 🚀:
python -m streamlit run studybuddy.py

Your AI Learning Buddy will open in your browser 🎉

📂 Project Structure:
AI-Learning-Buddy/
│
├── studybuddy.py        # Main Streamlit app + Gemini logic
├── .env                 # API keys (hidden, not committed)
├── requirements.txt     # Project dependencies
└── README.md            # Project documentation

🧠 Roadmap / Future Ideas:
 >>📄 PDF Support:
Upload textbook chapters and ask questions directly.

 >>🎙️ Voice Mode:
Talk to your AI tutor instead of typing.

 >>📝 Quiz Mode:
Test your understanding at the end of a study session.

🤝 Contributing:
Have an idea to make this tutor even better?
Feel free to fork the repo, experiment, and submit a pull request.

Learning is better when we build together 🚀


⭐ Show Some Love-:)

If you find this project helpful, consider giving it a ⭐ on GitHub — it really helps!



