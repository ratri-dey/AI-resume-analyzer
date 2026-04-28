# 🧠 AI Resume Analyzer (GenAI Project)

An AI-powered resume screening system that compares resumes with job descriptions using NLP, Machine Learning, and Generative AI. It provides ATS-style scoring, skill gap analysis, and AI-driven feedback through an interactive web app.

---

## 📌 Key Features

✔ Resume vs Job Description matching using Sentence-BERT  
✔ ATS Score generation using cosine similarity  
✔ AI feedback using Groq LLM (Llama-3)  
✔ Skill gap detection (missing vs required skills)  
✔ Chat assistant for resume improvement  
✔ PDF upload + real-time analysis (Streamlit UI)

---

## 🛠️ Tools & Technologies

Python | Streamlit | SentenceTransformers | Scikit-learn | Groq API | PDFMiner | Regex

---

## 🧠 Key Insights

- ATS compatibility score for resume screening  
- Skill mismatch detection between resume & job description  
- AI-generated improvement suggestions  
- Personalized resume feedback through chat assistant  

---

## 📂 Workflow

1. Upload Resume (PDF)  
2. Enter Job Description  
3. Extract text from resume  
4. Generate ATS similarity score  
5. AI analysis + skill gap detection  
6. Chat with AI for improvements  
7. Download final report  

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
