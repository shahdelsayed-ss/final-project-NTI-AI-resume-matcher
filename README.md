# final-project-NTI-AI-resume-matcher

#  AI CV Matcher

An AI-powered Resume Matching System that compares a candidate's CV with job descriptions and calculates the matching score. The project also identifies missing skills and provides personalized recommendations to improve the resume.

---

##  Project Overview

This project helps job seekers evaluate how well their resume matches a specific job description using Natural Language Processing (NLP) and Sentence Transformers.

The system:
- Extracts text from resumes.
- Computes semantic similarity between resumes and job descriptions.
- Calculates a CV Match Score.
- Identifies missing skills.
- Generates learning recommendations for missing skills.

---

##  Features

-  Resume Analysis
-  Job Description Matching
-  Match Score Calculation
-  Semantic Search using Sentence Transformers
-  Missing Skills Detection
-  Personalized Learning Recommendations

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Sentence Transformers
- Hugging Face
- PyPDF2
- Google Colab
-Streamlit
---

##  Dataset

The project uses:

- Job postings dataset
- Resume (CV) PDF
- Skills extracted from job descriptions

---

##  Workflow

1. Load job dataset.
2. Extract text from the uploaded CV.
3. Generate embeddings using Sentence Transformers.
4. Compute cosine similarity.
5. Rank jobs by similarity score.
6. Extract missing skills.
7. Recommend learning resources for each missing skill.

---

##  Model

Embedding Model:

```
all-MiniLM-L6-v2
```

Similarity Metric:

- Cosine Similarity

---

##  Output

The application provides:

-  Best Matching Jobs
-  Match Score (%)
-  Missing Skills
-  Learning Recommendations

Example:

| Job Title | Match Score |
|-----------|------------:|
| Data Engineer | 62.68% |
| Data Analyst | 58.41% |

Example Missing Skills:

- ETL
- Cloud Technologies
- Data Warehousing
- Docker
- Git

---

##  Project Structure

```
AI-CV-Matcher/
│
├── app.py
├── matcher.ipynb
├── requirements.txt
├── recommendation.py
├── data/
│   ├── all_job_post.csv
│   └── sample_cv.pdf
├── README.md
└── images/


##  Future Improvements

- Support DOCX resumes
- ATS compatibility analysis
- Resume optimization suggestions
- Multiple language support
- Integration with LinkedIn Jobs
- LLM-powered resume feedback


##  Author

**Shahd**

AI Student | Data Analytics | Machine Learning
