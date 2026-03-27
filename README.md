# 📊 An Automated Employer Record Matching Framework

## 📌 Overview
This project presents an automated framework for matching registered employer records by comparing string-based similarity methods and semantic similarity models. The goal is to improve data quality by identifying duplicate or similar records and enabling accurate record linkage and merging.

---

## 🎯 Objectives
1. To identify duplicate and inconsistent employer records 
2. To evaluate and select the best-performing matching model or algorithm 
3. To determine the optimal similarity threshold for the selected model 
4. To merge matched employer records accurately by aggregating employee counts across months 
5. To develop a scalable and replicable data standardisation framework 

---

## 🛠️ Tools & Technologies
- Python  
- Pandas & NumPy  
- Scikit-learn  
- NLP / Semantic similarity models (e.g., Sentence Transformers)  
- String similarity techniques (e.g., Fuzzy,Levenshtein distance, Jaccard similarity)
- Jupyter Notebook 
  
---

## ⚙️ Methodology

### 1. Data Preprocessing
- Data cleaning and normalization  
- Handling missing values  
- Standardizing text fields such as employer names  

### 2. String-Based Similarity Methods
- Levenshtein Distance  
- Jaro-Winkler Similarity  
- Jaccard Similarity
- fuzzy similarity  

### 3. Semantic Similarity Models
- Sentence embeddings using transformer-based models  
- Cosine similarity for semantic comparison  

### 4. Record Matching
- Pairwise comparison of employer records  
- Threshold-based matching  
- Deduplication and merging logic  

### 5. Evaluation
- Comparison of matching performance across methods  
- Metrics such as precision, recall, and F1-score 
- Analysis of false positives and false negatives  

---

## 📈 Key Results & Insights
- String-based methods perform well for exact or near-exact matches  
- Semantic models handle variations in naming more effectively  
- Hybrid approaches can improve overall matching accuracy  
- There is a trade-off between computational cost and performance  

---

## 📂 Project Structure
📁 project-folder/
- data/                  # Dataset files
- notebooks/             # Jupyter notebooks / analysis
- src/                   # Source code
- results/               # Output results and evaluation
- README.md              # Project documentation

---

## 🚀 Future Improvements
- Develop a hybrid matching approach combining string and semantic methods  
- Improve scalability for large datasets  
- Build a user interface or API for real-time matching  
- Integrate with database systems for production deployment  

---

## 👩‍💻 Author
Pavitra Palaniappan  

---

## 📌 Disclaimer
This project is developed for academic and portfolio purposes. No confidential or proprietary data is included.
