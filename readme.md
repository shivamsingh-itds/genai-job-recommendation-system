# 🚀 GenAI Job Recommendation System

An AI-powered job recommendation platform that matches candidates with relevant job opportunities using Large Language Models (LLMs), semantic search, and resume analysis. The system extracts skills from resumes, understands user preferences, and recommends the most suitable jobs with AI-generated explanations.

---

## 📌 Overview

Finding the right job among thousands of listings can be challenging. This project leverages Generative AI and Natural Language Processing (NLP) to intelligently analyze resumes and recommend jobs based on skills, experience, education, and career interests.

Instead of relying on simple keyword matching, the system understands the semantic meaning of resumes and job descriptions to deliver more relevant recommendations.

---

## ✨ Features

- 📄 Resume Upload (PDF/DOCX)
- 🤖 AI-powered Resume Analysis
- 🧠 Skill Extraction using LLM
- 🔍 Semantic Job Matching
- 💼 Personalized Job Recommendations
- 📊 Similarity Score for Each Job
- 💬 AI-generated Recommendation Explanation
- 🌐 Interactive Web Interface
- ⚡ Fast Response with Vector Search
- 📁 Support for Multiple Job Listings

---

## 🏗️ System Architecture

```
                Resume Upload
                      │
                      ▼
            Resume Text Extraction
                      │
                      ▼
             LLM Skill Extraction
                      │
                      ▼
        Text Embedding Generation
                      │
                      ▼
      Vector Database (Semantic Search)
                      │
                      ▼
         Retrieve Relevant Jobs
                      │
                      ▼
      LLM Recommendation & Explanation
                      │
                      ▼
              User Dashboard
```

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Generative AI
- Grok API
- Prompt Engineering

### NLP
- Sentence Transformers
- HuggingFace Transformers

### Vector Database
- FAISS

### Machine Learning
- Scikit-learn

### Backend
- FastAPI

### Frontend
- Streamlit

### Data Processing
- Pandas
- NumPy

### Resume Processing
- PyMuPDF
- python-docx

### Others
- Git
- GitHub

---

## 📂 Project Structure

```
genai-job-recommendation-system/

│── data/
│── models/
│── vector_db/
│── prompts/
│── utils/
│── app.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/shivamsingh-itds/genai-job-recommendation-system.git

cd genai-job-recommendation-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

For Streamlit

```bash
streamlit run app.py
```

or

For FastAPI

```bash
uvicorn app:app --reload
```

---

## 📈 Workflow

1. Upload Resume
2. Extract Resume Text
3. Clean & Process Text
4. Extract Skills using LLM
5. Convert Resume into Embeddings
6. Search Similar Jobs using FAISS
7. Rank Jobs by Similarity
8. Generate AI Explanation
9. Display Personalized Recommendations

---

## 📊 Example Output

```
Recommended Jobs

✔ AI Engineer
Match Score: 95%

Reason:
Your resume demonstrates strong experience in Python,
LLMs, LangChain, RAG, and Vector Databases which closely
align with the job requirements.

------------------------------------

✔ Machine Learning Engineer
Match Score: 92%

------------------------------------

✔ Data Scientist
Match Score: 88%
```

---

## 🚀 Future Improvements

- LinkedIn Job Integration
- Indeed API Support
- Multi-language Resume Support
- ATS Score Analysis
- Cover Letter Generation
- Interview Question Generator
- Resume Improvement Suggestions
- User Authentication
- Docker Deployment
- Cloud Deployment (AWS/GCP/Azure)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Shivam Singh**

- GitHub: https://github.com/shivamsingh-itds
- LinkedIn: *(Add your LinkedIn profile here)*

---

⭐ If you found this project helpful, consider giving it a **Star**.