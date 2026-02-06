# Task 3 – Resume Screening and Candidate Ranking

## 📌 Objective
The objective of this project is to build a simple NLP-based resume screening system that helps identify suitable candidates for a given job role by matching required skills, ranking resumes, and identifying skill gaps.

---

## 📂 Dataset
- File Name: resumes.csv
- Description:
  The dataset contains resume text data for multiple candidates.
- Columns Used:
  - Resume_ID – Unique identifier for each resume
  - Resume_Text – Text content of the resume

---

## 🛠️ Tools and Technologies Used
- Python
- Pandas
- NLTK
- Jupyter Notebook
- VS Code

---

## 🔄 Steps Followed
1. Loaded the resume dataset from a CSV file
2. Created a clean text column to preserve original data
3. Performed text preprocessing:
   - Converted text to lowercase
   - Removed punctuation and numbers
   - Removed stopwords
4. Defined a job role and required skills
5. Extracted matching skills from each resume
6. Calculated a score based on matched skills
7. Identified missing skills for each resume
8. Ranked candidates based on their scores

---

## 📊 Output
- Each resume is assigned:
  - Matched skills
  - Missing skills
  - A score indicating suitability
- Candidates are ranked based on their score

---

## 📁 Files in This Repository
- task3_resume_screening.ipynb – Main notebook containing the implementation
- resumes.csv – Dataset containing resume information (1000 records)
- README.md – Project documentation

---

## ✅ Conclusion
This project demonstrates a beginner-friendly resume screening system using NLP techniques. It successfully matches resumes with job requirements, ranks candidates, and highlights missing skills, fulfilling all the requirements of Task 3.
# FUTURE_ML_03
