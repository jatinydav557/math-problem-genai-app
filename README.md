🔗 👉 **[Watch the Demo on YouTube](https://www.youtube.com/watch?v=Xqx2_xOhdn8&list=PLe-YIIlt-fbO3hXVoaPK56ikWRT0A9Gzr&index=8&ab_channel=Jatin)**

# 🧮 LangChain Math Solver & Wiki Research Assistant 🔍

This project is a **Text-to-Math Problem Solver** and a **Knowledge Assistant** that leverages LLMs and reliable external tools like **Wikipedia** to help users **solve numerical problems** and **learn about concepts** in one interface.

Built with ❤️ using **LangChain**, **Groq’s Gemma 2**, **Wikipedia**, and **Streamlit**.

---

## 🚀 What It Does

Whether you're stuck on a tricky math question or want a quick explanation of a topic — this tool has your back!

✅ Solve logic-based and arithmetic math problems  
✅ Use built-in calculator logic powered by `LLMMathChain`  
✅ Search Wikipedia directly inside the chat  
✅ Get step-by-step reasoning using prompts  
✅ Real-time interactive chat UI using Streamlit

---

## 🎯 Use-Cases

- 🧠 Students solving word-based math problems  
- 📝 Competitive exam aspirants needing instant help  
- 📚 Learners wanting definitions or Wikipedia-based research  
- 👨‍🏫 Teachers or tutors testing model reasoning capabilities

---

## ✨ Features

| Feature               | Description                                             |
|-----------------------|---------------------------------------------------------|
| 🧮 Math Solver         | Uses `LLMMathChain` to solve expressions, equations     |
| 🧠 Logical Reasoning   | Custom prompt chain for multi-step logical problems     |
| 🌐 Wiki Search Tool    | Integrated Wikipedia API for topic lookups             |
| 🦙 LLM Backbone        | Powered by `Gemma2-9b-it` via Groq’s blazing speed      |
| 🖥️ Chat UI             | Smooth and conversational interface via Streamlit       |

---

## 📁 Project Structure

```
.
├── app.py             # Main Streamlit App
├── .env               # Contains Groq API Key
├── requirements.txt   # All Python dependencies
└── README.md
```

---

## 🧪 Demo Scenario

> **Question**: What is the result if I have 5 mangoes and give 2 to my friend?  
> ✨ The app will use reasoning chain and calculator to answer:  
> **"You have 3 mangoes left."**

> **Question**: Tell me who invented the Pythagorean Theorem  
> 🔍 Wikipedia Tool will fetch a concise, factual answer instantly.

---

## ⚙️ Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/jatinydav557/math-problem-genai-app.git
cd math-problem-genai-app
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 4️⃣ Create `.env` File

```env
GROQ_API_KEY=your_groq_api_key_here
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

Then open the link shown in your terminal (usually http://localhost:8501).

---

## 📦 Dependencies

```
streamlit
langchain
langchain-groq
langchain-community
wikipedia
python-dotenv
numexpr
```

> ⚠️ `numexpr` is essential for accurate math evaluations.

---

## 🧑‍🎓 About Me

Hey, I'm **Jatin**, a final-year MCA student and GenAI developer building 20+ projects to land a top-tier role in **LLM Engineering, MLOps, or AI R&D**.

This app merges **reasoning, math, and factual knowledge** — empowering learners with an AI companion that explains as well as calculates.

---

## ✅ What's Next?

- [ ] Add LaTeX rendering for better math visualization  
- [ ] Enable speech input via Whisper API  
- [ ] Deploy to Hugging Face Spaces / Streamlit Cloud

---

## 🙋‍♂️ Let's Connect

- **💼 LinkedIn:** [linkedin.com/in/jatin557](https://www.linkedin.com/in/jatin557)
- **📦 GitHub:** [github.com/jatinydav557](https://github.com/jatinydav557)
- **📬 Email:** [jatinydav557@gmail.com](mailto:jatinydav557@gmail.com)
- **📱 Phone:** [+91-7340386035](tel:+917340386035)
- **🎥 YouTube:** [Watch My Other Projects](https://www.youtube.com/@jatinML/playlists)

---

> ⭐ If this project helped you, give it a star and share it with your community.

> _“Learning + LLMs = A future where anyone can be curious and capable.”_

