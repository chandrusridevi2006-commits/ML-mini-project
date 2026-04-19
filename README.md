# 🤖 AI-Based Interview Performance Predictor

## 📌 Overview

This project focuses on predicting candidate performance in job interviews using Machine Learning techniques. The system analyzes attributes such as academic performance, technical skills, communication ability, and experience to determine whether a candidate is likely to be selected.

Multiple machine learning models are implemented and compared to identify the most accurate and reliable predictor.

---

## 🚀 Features

- Synthetic dataset generation for interview scenarios  
- Data preprocessing and feature scaling  
- Implementation of multiple ML models  
- Model comparison using accuracy and ROC curves  
- Feature importance analysis  
- Visualization of results:
  - Model accuracy comparison  
  - ROC curves  
  - Confusion matrix  
  - Feature importance chart  
  - CGPA distribution  
  - Test vs Cross-validation accuracy  

---

## 📂 Dataset

- **Name**: Interview Performance Dataset  
- **Type**: Tabular Data  
- **Source**: Synthetic (Generated using Python)  

### Features:
- CGPA  
- Technical Score  
- Communication Score  
- Problem Solving  
- Internships  
- Projects  
- Aptitude Score  
- Mock Interviews  
- Certifications  
- Confidence  

### Target Variable:
- Hired (1)  
- Not Hired (0)  

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧠 Machine Learning Models

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Gradient Boosting  

---

## 🔧 Model Workflow

1. Data Generation & Preprocessing  
2. Feature Scaling using StandardScaler  
3. Train-Test Split (80:20)  
4. Model Training  
5. Performance Evaluation  
6. Visualization and Analysis  

---

## 📊 Model Performance

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 0.98     |
| SVM                 | 0.96     |
| Gradient Boosting   | 0.90     |
| Random Forest       | 0.87     |
| KNN                 | 0.85     |
| Decision Tree       | 0.77     |

✔ Logistic Regression achieved the highest accuracy  
✔ Models show strong classification performance  

---

## 📈 Output Visualizations

The project generates the following outputs:

- Model Accuracy Comparison  
- ROC Curve Analysis  
- Confusion Matrix  
- Feature Importance (Random Forest)  
- CGPA Distribution by Outcome  
- Test vs Cross-validation Accuracy  

---
📁 Project Structure

AI-Interview-Predictor/
│
├── dataset/
├── output/
│ └── model_analysis.png
├── main.py
├── requirements.txt
└── README.md

---

## ▶️ How to Run the Project

### 1. Install dependencies

--- bash
pip install numpy pandas matplotlib seaborn scikit-learn
python main.py 

Results Summary
The model successfully predicts interview outcomes with high accuracy
Logistic Regression performed best among all models
Technical skills, communication, and CGPA are key influencing factors
Cross-validation confirms model stability and no overfitting
🔮 Future Improvements
Use real-world datasets
Integrate resume screening using NLP
Add video/audio-based interview analysis
Deploy as a web application (Flask / Streamlit)
Use deep learning models for enhanced performance

 ---
🤝 Contributing

Contributions are welcome! Feel free to fork this repository and improve the project.

📜 License

This project is for academic and educational purposes only.

👨‍💻 Author
  **Chandru Sridevi**
