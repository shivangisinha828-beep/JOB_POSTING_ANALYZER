# JOB_POSTING_ANALYZER
Analyzed 2000+ job postings using Bag-of-Words NLP and K-Means clustering (no sklearn) | Python, Pandas, Matplotlib | Based on Data Science from Scratch(Book written by Joel Grus)
# 📊 Job Posting Analyzer

> End-to-end data science project analyzing 2000+ LinkedIn job postings to extract in-demand skills and cluster jobs by skill profiles — built **entirely from scratch** using concepts from *Data Science from Scratch* by Joel Grus (O'Reilly).

🌐 **[Live Website](https://shivangisinha828-beep.github.io/JOB_POSTING_ANALYZER)** · 📓 **[Open in Colab](https://colab.research.google.com/github/shivangisinha828-beep/JOB_POSTING_ANALYZER/blob/main/NOTEBOOK/JOBPOSTINGANALYZER.ipynb)** · 📦 **[Dataset](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)**

---

## 🚀 What This Project Does

- Extracts **40+ tech & soft skills** from 2000+ job descriptions using NLP (Bag of Words)
- Identifies the **top 20 most in-demand skills** in today's job market
- Clusters jobs into 5 groups using **K-Means implemented from scratch** (no scikit-learn!)
- Recommends the best job cluster based on **your personal skill set**
- Visualizes insights through **6 charts** including heatmaps, word clouds, and elbow plots

---

## 📸 Output Visualizations

| Top 20 Skills | Word Cloud |
|---|---|
| ![Top Skills](OUTPUT/Top%20Skills%20from%20Job%20Posting%20Analyzer.png) | ![Word Cloud](OUTPUT/Job%20Posting%20Analyzer%20Wordcloud.png) |

| Cluster Distribution | Skill Heatmap |
|---|---|
| ![Clusters](OUTPUT/Clusters%20Pie%20from%20Job%20Posting%20Analyzer.png) | ![Heatmap](OUTPUT/Skill%20Heatmap%20from%20Job%20Posting%20Analyzer.png) |

| Elbow Method | Category Breakdown |
|---|---|
| ![Elbow](OUTPUT/Job%20Posting%20Analyzer%20Elbow.png) | ![Stacked](OUTPUT/Job%20Posting%20Analyzer%20Stacked.png) |

---

## 🧠 Concepts from *Data Science from Scratch*

| Feature | Chapter | Concept |
|---|---|---|
| Counter, defaultdict | Ch. 1–2 | Python data structures |
| Vector math & distance | Ch. 4 | Linear algebra from scratch |
| Data loading & cleaning | Ch. 10 | Working with data |
| Bag of Words / NLP | Ch. 13, 21 | Text tokenization & frequency |
| K-Means clustering | Ch. 19 | Unsupervised learning from scratch |
| Matplotlib charts | Ch. 3 | Data visualization |

> ✅ No scikit-learn. No PyTorch. No shortcuts. Every algorithm is hand-coded.

---

## 🗺️ Project Pipeline

```
Raw Kaggle Data
      ↓
  Data Cleaning          ← Ch. 10
      ↓
 Skill Extraction        ← Ch. 13, 21  (Bag of Words NLP)
      ↓
Word Frequency Analysis  ← Ch. 1       (Counter, defaultdict)
      ↓
K-Means Clustering       ← Ch. 19      (From scratch!)
      ↓
Visualizations + Job Recommender
```

---

## 🛠️ How to Run

### Option 1 — Google Colab (Recommended)
Click the badge to open directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shivangisinha828-beep/JOB_POSTING_ANALYZER/blob/main/NOTEBOOK/JOBPOSTINGANALYZER.ipynb)

### Option 2 — Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/shivangisinha828-beep/JOB_POSTING_ANALYZER.git
cd JOB_POSTING_ANALYZER

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your Kaggle credentials
#    Place kaggle.json in ~/.kaggle/

# 4. Open the notebook
jupyter notebook NOTEBOOK/JOBPOSTINGANALYZER.ipynb
```

---

## 📦 Dataset

- **Source:** [LinkedIn Job Postings — Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)
- **Size used:** 2,000 job postings
- **Note:** Dataset is not included in this repo. Download via Kaggle API as shown in the notebook.

---

## 🔍 Key Results

- **Python** is the most in-demand skill across all job categories
- **5 distinct job clusters** were discovered: ML/AI, Data Analyst, Cloud/Data Engineer, Data Scientist, Business & Strategy
- **SQL** appears in 4 out of 5 clusters — making it the most universally valuable skill
- Average job posting mentions **2.7 trackable skills**

---

## 📁 Repo Structure

```
JOB_POSTING_ANALYZER/
│
├── NOTEBOOK/
│   └── JOBPOSTINGANALYZER.ipynb   ← full analysis notebook
│
├── OUTPUT/
│   ├── Top Skills from Job Posting Analyzer.png
│   ├── Job Posting Analyzer Wordcloud.png
│   ├── Clusters Pie from Job Posting Analyzer.png
│   ├── Skill Heatmap from Job Posting Analyzer.png
│   ├── Job Posting Analyzer Elbow.png
│   └── Job Posting Analyzer Stacked.png
│
├── index.html                     ← project website
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🧰 Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading only |
| Matplotlib + Seaborn | Visualizations |
| WordCloud | Text visualization |
| Google Colab | Notebook environment |
| Kaggle API | Dataset source |
| ❌ No scikit-learn | Everything from scratch |

---

## 📚 Reference

**Book:** [Data Science from Scratch](https://www.oreilly.com/library/view/data-science-from/9781492041122/) by Joel Grus (O'Reilly, 2nd Edition)

---

## 👤 Author

**Shivangi Sinha**
📚 Currently reading: *Data Science from Scratch* — Joel Grus
🔗 [GitHub](https://github.com/shivangisinha828-beep)

---

## 📄 License

This project is licensed under the MIT License.
