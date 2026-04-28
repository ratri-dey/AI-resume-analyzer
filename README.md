#📦 AI Resume Analyzer (GenAI Project)

An AI-powered resume screening system that compares resumes with job descriptions using NLP, Machine Learning, and Generative AI. It provides ATS-style scoring, skill gap analysis, and AI-driven improvement suggestions through an interactive web app.

#📌 Key Features:

✅ Resume vs Job Description matching using Sentence-BERT embeddings
📈 ATS Score generation using cosine similarity
🤖 AI-powered feedback using Groq LLM (Llama-3)
🧠 Skill gap detection (missing vs required skills)
💬 Chat assistant for resume improvement guidance
📄 PDF upload and real-time analysis via Streamlit UI

#🛠️ Tools Used:

Python (Core logic & backend)
Streamlit (Web application UI)
SentenceTransformers (Semantic similarity)
Scikit-learn (Cosine similarity)
Groq API (LLM - Llama 3)
PDFMiner (Resume text extraction)
Regex (Text processing)

#🧠 Insights Delivered:

ATS compatibility score for resume screening
Skill mismatch identification between resume and job description
AI-generated suggestions to improve resume quality
Personalized feedback through chat-based assistant
Highlighted areas of improvement for better job matching

#📂 Project Workflow:

Upload Resume (PDF format)
Enter Job Description
Extract and process resume text
Generate ATS similarity score
Analyze skills gap and AI feedback
Chat with AI for resume improvement suggestions
Download final report

#🚀 How to Run:

pip install -r requirements.txt
streamlit run app.py

#🔑 Environment Variables:

Create a .env file and add:
GROQ_API_KEY=your_api_key_here

#👨‍💻 Future Enhancements:

Resume ranking system for multiple candidates
AI-based resume rewriting tool
Job recommendation engine
PDF formatted AI feedback report
