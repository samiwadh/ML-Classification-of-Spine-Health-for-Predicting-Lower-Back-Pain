# 🧠 Spine Health Classification using Machine Learning

## 📌 Overview
Lower back pain is a common health issue caused by various factors such as muscle strain, nerve irritation, and spinal abnormalities. This project aims to classify whether a person's spinal condition is **Normal** or **Abnormal** using machine learning techniques.

The project uses biomechanical features of the spine and applies multiple ML models to identify patterns that indicate abnormal conditions.

---

## 📊 Dataset
- Total samples: 310
- Features: 6–12 numerical spinal attributes
- Target: Binary classification (Normal / Abnormal)

### Key Features:
- Pelvic Incidence  
- Pelvic Tilt  
- Lumbar Lordosis Angle  
- Sacral Slope  
- Pelvic Radius  
- Degree of Spondylolisthesis  

---

## ⚙️ Workflow

### 1. Data Exploration
- Checked class distribution (imbalanced dataset)
- Analyzed feature distributions
- Identified skewness and outliers

### 2. Data Preprocessing
- Normalization using Min-Max scaling
- Feature selection using correlation filtering
- Removed highly correlated features

### 3. Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Over-sampling Technique)**
- Balanced training dataset

### 4. Model Training
Implemented multiple machine learning models:
- Random Forest
- Gradient Boosted Trees
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Naive Bayes

### 5. Model Evaluation
Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Cohen’s Kappa

---

## 📈 Results

| Model                    | Accuracy |
|--------------------------|----------|
| Gradient Boosted Trees   | **87.10%** ✅ |
| Random Forest            | 86.02% |
| Decision Tree            | 84.95% |
| Tree Ensemble            | 83.87% |
| Logistic Regression      | 82.80% |
| Naive Bayes              | 80.65% |
| KNN                      | 77.42% |

### 🏆 Best Model:
**Gradient Boosted Trees**
- Balanced performance across all metrics
- Strong precision and recall
- Most reliable for real-world application

---

## 🛠 Tools & Technologies
- KNIME Analytics Platform
- Machine Learning Algorithms
- Data Preprocessing Techniques
- SMOTE (Imbalanced Data Handling)

---

## 💡 Key Learnings
- Importance of handling class imbalance
- Feature selection improves model performance
- Ensemble models outperform simple models
- Trade-off between precision and recall in healthcare problems

---

## 🚀 Future Improvements
- Apply Deep Learning (Neural Networks)
- Add demographic features (age, lifestyle)
- Hyperparameter tuning
- Advanced imbalance handling techniques

---

## 📚 References
- UCI ML Repository Dataset
- KNIME Documentation
- Research papers on Random Forest & Gradient Boosting

---

## 👨‍💻 Author
Abdul Sami,Davina David
Machine Learning Enthusiast | Data Science Student
