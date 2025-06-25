# 🤖 Resume Screening Assistant

An interactive machine learning project that classifies resumes into job categories:

- 📊 Data Science  
- 💻 Software Development  
- 🧑‍💼 Human Resources  
- 🎨 UI/UX Design  

This project uses:
- `TfidfVectorizer` for feature extraction
- `Naive Bayes` with Binary Relevance (Multi-label classification)
- `ipywidgets` for an interactive interface
- `matplotlib` for plotting confidence levels

---

## ▶️ Open in Google Colab

Click the button below to try the project instantly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/harika1827/resume-screening-assistant/blob/main/resume_classifier.ipynb)

---

## 🚀 How to Use

1. Paste your resume text into the input box  
2. Adjust the threshold using the slider (e.g., 0.4)  
3. Click the **"Classify Resume"** button  
4. View the predicted job categories and confidence scores  
5. See a chart of probabilities for each job type  

---

## 📦 Installation (for local use)

To run this on your local system:

```bash
git clone https://github.com/harika1827/resume-screening-assistant.git
cd resume-screening-assistant
pip install -r requirements.txt
