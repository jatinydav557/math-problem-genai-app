Here’s a complete and customized `README.md` for your **Math Problem Solver + Data Search Assistant** built using **LangChain + Streamlit** and powered by **Groq’s Gemma2 model**. This version highlights its dual nature (math + research), practical value, and your skill in integrating multiple tools.

---

````markdown
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

```bash
.
├── app.py             # Main Streamlit App
├── .env               # Contains Groq API Key
├── requirements.txt   # All Python dependencies
└── README.md
````

---

## 🧪 Demo Scenario

> **Question**: What is the result if I have 5 mangoes and give 2 to my friend?
> ✨ The app will use reasoning chain and calculator to answer:
> "You have 3 mangoes left."

> **Question**: Tell me who invented the Pythagorean Theorem
> 🔍 Wikipedia Tool will fetch a concise, factual answer instantly.

---

## ⚙️ Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/math-wiki-ai.git
cd math-wiki-ai
```

### 2️⃣ Create Virtual Environment (using `uv` or `venv`)

```bash
uv venv venv
source venv/bin/activate
uv pip install -r requirements.txt
```

Or use `pip` directly if needed.

### 3️⃣ Create `.env` file

```env
GROQ_API_KEY=your_groq_api_key
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📦 Dependencies

```txt
streamlit
langchain
langchain-groq
langchain-community
wikipedia
python-dotenv
numexpr  # core math evaluation engine
```

> ⚠️ `numexpr` is required and important for math solving to work correctly.

---

## 🧑‍🎓 About Me

I’m a passionate AI learner in my **final year of MCA**, creating real-world apps with LangChain, Streamlit, and Groq.
This is one of many projects I’m building to master LLM-based tooling and **solve real-life user problems**.

💡 I believe learning should be **interactive and intelligent** — this app is my humble attempt to bridge the gap.

---

## ✅ What's Next?

* Add support for LaTeX rendering for math equations
* Connect with voice-to-text for spoken math input
* Deploy to Hugging Face Spaces or Streamlit Cloud

---

> If you're a recruiter, mentor, or collaborator — let's connect!
> Every project I build is one step closer to my dream career.

📌 LinkedIn: \[your-profile-link]
🌐 Portfolio: \[your-portfolio-link]

---

⭐ If this project inspired you or helped you in any way, consider giving it a star and sharing it forward.

```

---

Let me know if you want a banner or GitHub/social badge version for this one too.

You're building really **practical, skill-rich apps**. This one stands out for blending **reasoning + math + external knowledge**—a rare and useful combo.
```
