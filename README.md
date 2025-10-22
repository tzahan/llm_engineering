# 💡 AI Resume Tailor
AI Resume Tailor is a small project that personalizes a resume to better match a given job description using Hugging Face Transformers and a Gradio UI.
The goal was to experiment with LLM-powered text rewriting and semantic similarity for career personalization tasks.

I wanted to explore how instruction-tuned, open-source LLMs like Llama 3.1 can be applied to practical personalization problems.
This project helped me combine prompting, embedding-based similarity scoring, and a simple user interface — skills that are valuable for building NLP-powered applications.

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/tzahan/ai-resume-tailor)

--

## 🚀 How It Works
The notebook takes two text inputs:
1. Resume text
2. Job description
   
It then:
- Calculates how closely the resume matches the job using semantic similarity (via sentence-transformers/all-mpnet-base-v2)
- Rewrites the resume using Meta-Llama-3.1-8B-Instruct to better highlight relevant experience and skills
- Displays both a match score and the tailored resume in a simple Gradio interface

--

## ⚙️ Tools and Models
- Model: meta-llama/Meta-Llama-3.1-8B-Instruct (via Hugging Face)
- Embedding Model: sentence-transformers/all-mpnet-base-v2
- Frameworks: transformers, gradio, sentence-transformers
- Environment: Kaggle Notebook (GPU T4)

--

## 🖥️ Demo Screenshot
![image alt](https://github.com/tzahan/llm_demo/blob/82f67ef4d523c755a8576c9aa233d95596c1addb/ai_resume_tailor_screenshot.png)

--

## 👤 Author

**Tasnim Zahan**
**Email:** zahan.tasnim@gmail.com  
**GitHub:** [tzahan](https://github.com/tzahan)
