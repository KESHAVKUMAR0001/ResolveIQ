# ResolveIQ — Support Ticket Classification & Prioritization System

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=flat-square&logo=scikit-learn)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?style=flat-square&logo=streamlit)

ResolveIQ is an intelligent ticket categorization and priority triage engine designed for customer support and IT helpdesks. It automatically classifies incoming support tickets into departments and assigns urgency levels to optimize response times.

---
## 🚀 Features
- **Automated Categorization**: Uses TF-IDF and Logistic Regression for ticket routing.
- **Urgency Scoring**: Detects issue severity (High, Medium, Low) based on rule heuristics.
- **Interactive Dashboard**: Streamlit interface to train models, visualize metrics, and test tickets.
- **Model Persistence**: Saved vectorizers and classifiers for zero-latency inference.
---
## 📂 Project Structure
```
ResolveIQ/
├── app.py              # Streamlit dashboard
├── main.py             # CLI runner & model evaluation
├── requirements.txt    # Project dependencies
├── data/               # Datasets, models, and evaluation assets
└── src/                # Preprocessor, feature extractor, classifier & evaluator
```
---
## 🛠️ Quickstart

### 1. Install Dependencies
```bash
pip install -r requirements.txt
python -c "import nltk; nltk.download('stopwords'); nltk.download('wordnet')"
```

### 2. Run CLI Pipeline
```bash
python main.py
```

### 3. Launch Web App
```bash
streamlit run app.py
```
---
## 👤 Author
**Keshav Kumar**  
GitHub: [@KESHAVKUMAR0001](https://github.com/KESHAVKUMAR0001)
