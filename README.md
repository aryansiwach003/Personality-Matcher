# Game of Thrones Personality Matcher

A beginner-friendly NLP project that recommends similar Game of Thrones characters based on their dialogue patterns.
This project measures **dialogue similarity**.
Characters with similar amounts and types of dialogue are grouped together.

## 🔍 Project Overview
- Aggregates dialogue spoken by each character
- Converts text to numerical features using Bag-of-Words
- Applies t-SNE for dimensionality reduction
- Recommends similar characters based on embedding proximity


## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Thrones API

## 🚀 How to Run
```bash
pip install streamlit pandas numpy scikit-learn requests
streamlit run app.py
