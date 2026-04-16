# 🧠 AI Resume Screening System 

## 📌 Overview

This project is an AI-powered Resume Screening System that evaluates candidates based on a given job description.
It uses **Natural Language Processing (NLP)** techniques to extract skills, match them with job requirements, assign a score, and generate explanations.

---

## 🚀 Features

* ✅ Skill Extraction from resumes
* ✅ Matching with job description
* ✅ Candidate Scoring (0–100)
* ✅ Explanation generation
* ✅ Debug case handling
* ✅ Hybrid approach (LLM + Rule-based scoring)

---

## 🏗️ Pipeline Architecture

```
Resume → Skill Extraction → Matching → Scoring → Explanation
```

---

## 🛠️ Tech Stack

* Python
* LangChain
* Hugging Face Transformers (FLAN-T5)
* Jupyter Notebook

---

## 📂 Project Structure

```
resume-screening/
│
├── notebook.ipynb
├── README.md
└── utils/ (optional)
```

---

## 📥 Installation

```bash
pip install transformers==4.41.2 langchain langchain-core langchain-community
```

---

## ▶️ How to Run

1. Open the notebook (`notebook.ipynb`)
2. Run all cells (top to bottom)
3. Execute:

```python
evaluate_candidate(strong_resume, job_description)
```

---

## 📊 Sample Output

### 🔹 Strong Candidate

* Score: 80–90
* High skill match

### 🔹 Average Candidate

* Score: 40–60
* Partial match

### 🔹 Weak Candidate

* Score: 0–20
* Low or no match

---

## 🧪 Debug Case

A test case is included to show incorrect predictions and system limitations.

---

## ⚠️ Limitations

* Free Hugging Face model may produce less accurate results
* LLM output may not always follow strict format
* No LangSmith tracing (API not used)

---

## 💡 Improvements (Future Scope)

* Use OpenAI GPT models for better accuracy
* Add LangSmith tracing
* Convert into web app (Streamlit)
* Improve extraction using fine-tuned models

---

## 🧠 Key Insight

This project demonstrates how to build a **production-style AI pipeline** using:

* Prompt engineering
* Modular LangChain components
* Hybrid scoring logic

---
