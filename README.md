# Math-GPT

# 🧮 Text to Math Problem Solver & Data Search Assistant

Welcome to **Text to Math Problem Solver**, an interactive Streamlit app that leverages **LangChain**, **Groq’s Gemma 2 model**, and Wikipedia search to help you:

✅ **Solve complex math word problems with step-by-step explanations**  
✅ **Search and retrieve information from Wikipedia**  
✅ **Answer logic and reasoning questions with clarity**

---

## 🚀 Features

- 🧩 **Conversational Math Solver** – Converts text-based math problems into detailed, step-by-step solutions.
- 🔍 **Wikipedia Search** – Searches and summarizes topics from Wikipedia.
- 🧠 **Logic & Reasoning Answers** – Handles logical and reasoning-based questions.
- 💬 **Interactive Chat UI** – Clean, conversational interface built with Streamlit.
- ⚡ **Real-Time Responses** – Get instant feedback with dynamic updates.

---

## 🛠️ Technologies Used

- [Streamlit](https://streamlit.io/) – for the interactive web app.
- [LangChain](https://www.langchain.com/) – for chaining LLMs and tools.
- [Groq’s Gemma 2](https://groq.com/) – powerful language model for reasoning and calculations.
- Wikipedia API – for information retrieval.

---

## 📦 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME

Install dependencies
Make sure you have Python 3.8 or higher installed, then run:
pip install -r requirements.txt

Run the Streamlit app
streamlit run app.py

Replace app.py with the actual filename if it’s different.

Enter your Groq API key

When the app launches, enter your Groq API key in the sidebar to start using the app.

📝 How It Works
Three tools are created using LangChain:

🔹 Wikipedia Tool – uses WikipediaAPIWrapper to fetch information.

🔹 Math Calculator Tool – uses LLMMathChain to solve numeric and algebraic problems.

🔹 Reasoning Tool – powered by a custom prompt template to solve word-based and logical math problems.

These tools are combined in a zero-shot agent, which decides the best tool to use for each question.

Streamlit manages the chat interface, stores chat history with st.session_state, and updates responses dynamically.

🎨 Example Questions
I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes. Then I buy a dozen apples and 2 packs of blueberries. Each pack of blueberries contains 25 berries. How many total pieces of fruit do I have at the end?

What is the capital of France?

If a car travels at 60 km/h for 2 hours, how far does it go?





  
