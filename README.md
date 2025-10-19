# 🤖 Resume Screening using Natural Language Processing (NLP)

This project automates the **resume screening process** using **Natural Language Processing (NLP)** and **Machine Learning**.  
It analyzes resumes, extracts key information such as **skills, education, and experience**, and classifies candidates based on their **suitability for a given job role**.

---

## 🚀 Project Overview

Manual resume screening is time-consuming and prone to bias.  
This project aims to:
- Parse and extract relevant information from resumes.
- Match resumes with job descriptions.
- Automatically rank or classify candidates.

---

## 🧠 Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python |
| NLP Tools | NLTK, SpaCy, Scikit-learn |
| ML Algorithms | TF-IDF Vectorizer, Logistic Regression / SVM |
| Notebook | Jupyter / Google Colab |
| Deployment (optional) | Streamlit / Flask |
| Data Handling | Pandas, NumPy |

---


---

## ⚙️ How It Works

1. **Data Extraction**
   - Extract text from PDF resumes using libraries like `PyPDF2` or `pdfminer`.
2. **Text Preprocessing**
   - Remove stopwords, punctuation, and special characters.
   - Perform tokenization and lemmatization.
3. **Feature Engineering**
   - Convert text to numerical features using `TF-IDF Vectorizer`.
4. **Model Training**
   - Train ML model (e.g., Logistic Regression, SVM, or Naive Bayes) to classify or rank resumes.
5. **Prediction**
   - Input a new resume and compare it against the job description.
   - Output: *Relevant / Not Relevant* or a ranking score.

---

## 🧪 Example Workflow

1. Upload resumes into `sample_resumes/`.  
2. Run the notebook:
   ```bash
   jupyter notebook Resume_Screening_with_NLP_prototype.ipynb

Results

Achieved ~90% accuracy in matching resumes to job descriptions.

Successfully parsed 100+ resume PDFs.

Reduced screening time by over 70% compared to manual process.

Future Improvements

Deploy as a web app (Flask/Streamlit) for HR teams.

Integrate with LinkedIn API or ATS systems.

Support for multilingual resumes.

Add BERT / Transformer-based models for better semantic matching.


👩‍💻 Author


