# 🌸 Iris Flower Classification  
---
 
![ML](https://img.shields.io/badge/Machine%20Learning-ScikitLearn-orange)  ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  ![Build](https://img.shields.io/badge/Build-Passing-success)  ![Dataset](https://img.shields.io/badge/Dataset-Iris-blueviolet)  ![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🌟 Future Work
- Add more ML models (Random Forest, SVM, etc.)
- Deploy the model using **Streamlit** or **Flask**
- Create a web dashboard for predictions  

---

## 🙌 Acknowledgements
This project is inspired by the classic **Iris dataset** introduced by Ronald A. Fisher.  
Special thanks to the **scikit-learn** and **pandas** community for providing such powerful tools.  

---

## 📢 Final Note
If you like this project, don’t forget to ⭐ the repository and connect with me! 🚀  
I’m always open to collaboration and feedback.  

---

## 📌 Overview  
This project demonstrates **Machine Learning classification** using the famous **Iris dataset**.  
We build and compare three models:  

- 🔹 Logistic Regression  
- 🔹 Decision Tree  
- 🔹 K-Nearest Neighbors (KNN)  

The best-performing model is saved for future predictions.  

---

## 📊 Dataset  
- **Source**: Iris Dataset (150 samples)  
- **Features**:  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Target**: Species (Setosa 🌱, Versicolor 🌿, Virginica 🌸)  

---

## ⚙️ Installation  

- Clone the repository:  
````bash
git clone https://github.com/zain1234-coder/Iris-Flower-Classification.git
cd Iris-Flower-Classification
````

- Install dependencies:

````bash
pip install -r requirements.txt

````

---

## 🚀 How to Run

Run the main script:

````bash
python iris_project.py
````

This will:
✅ Load the dataset
✅ Train Logistic Regression, Decision Tree, and KNN
✅ Compare their performance
✅ Show evaluation metrics (accuracy, confusion matrix, classification report)
✅ Save the best model as **iris\_best\_model.joblib**

---

## 📈 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 100% ✅   |
| Decision Tree       | 100% ✅   |
| KNN                 | 100% ✅   |

📌 **Best Model:** Logistic Regression

Example Confusion Matrix:

````
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
````

All models achieved **perfect classification** on this dataset. 🎯

---

## 💾 Saved Model

The best model is stored as:

````bash
iris_best_model.joblib
````

You can load it later for predictions:

````python
import joblib

model = joblib.load("iris_best_model.joblib")
sample = [[5.1, 3.5, 1.4, 0.2]]
print("Predicted species:", model.predict(sample)[0])
````

---

## 📷 Visualizations

* 🔹 Count plot of species distribution
* 🔹 Pair plot of features
* 🔹 Heatmap of feature correlations
* 🔹 Confusion matrix for model performance

---

## 👨‍💻 Author

**Zain Ul Abideen**

* 🌐 GitHub: [zain1234-coder](https://github.com/zain1234-coder)
* 💼 Data Analyst | Web Developer | Machine Learning Enthusiast

--- 

## 🌟 Future Work
- Add more ML models (Email spam detec, Car price pred, etc.)
- Deploy the model using **Streamlit** or **Flask**
- Create a web dashboard for predictions  

---

## 🙌 Acknowledgements
This project is inspired by the classic **Iris dataset** introduced by Ronald A. Fisher.  
Special thanks to the **scikit-learn** and **pandas** community for providing such powerful tools.  

---

## 📢 Final Note
If you like this project, don’t forget to ⭐ the repository and connect with me! 🚀  
I’m always open to collaboration and feedback.  

---
