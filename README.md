## **Project Overview**  
This project aims to predict the likelihood of heart disease using machine learning techniques. By analyzing medical attributes such as age, cholesterol levels, and blood pressure, the model helps in early detection and decision-making.  

## **Dataset**  
The dataset consists of multiple health-related parameters, including:  
- **age**: Age of the patient  
- **sex**: Gender (1 = male, 0 = female)  
- **cp**: Chest pain type (categorical)  
- **trestbps**: Resting blood pressure  
- **chol**: Serum cholesterol level  
- **fbs**: Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)  
- **restecg**: Resting electrocardiographic results  
- **thalach**: Maximum heart rate achieved  
- **exang**: Exercise-induced angina (1 = yes, 0 = no)  
- **oldpeak**: ST depression induced by exercise relative to rest  
- **slope**: Slope of the peak exercise ST segment  
- **ca**: Number of major vessels colored by fluoroscopy  
- **thal**: Thalassemia (categorical)  
- **target**: Presence of heart disease (1 = yes, 0 = no)  

## **Technologies Used**  
- **Python**  
- **Pandas, NumPy** for data manipulation  
- **Matplotlib, Seaborn** for visualization  
- **Scikit-learn** for machine learning models  
- **Google Colab** for implementation  

## **Modeling Approach**  
Three machine learning models were implemented:  
1. **Logistic Regression** – A simple, interpretable model for classification.  
2. **Decision Tree** – A tree-based model prone to overfitting.  
3. **Random Forest** – An ensemble method providing high accuracy.  

The models were evaluated based on:  
- **Accuracy**  
- **Precision, Recall, and F1-score**  
- **Confusion Matrix**  
- **ROC-AUC Score**  

## **Key Findings**  
- **Random Forest achieved the highest ROC-AUC score (0.91)**, making it the most reliable predictor.  
- **Logistic Regression (AUC = 0.88)** performed well and remains a viable alternative due to its interpretability.  
- **Decision Tree (AUC = 0.74)** underperformed, likely due to overfitting.  
- **Key risk factors identified** include chest pain type, cholesterol level, and maximum heart rate.  

## **Installation and Usage**  
### **1. Clone the Repository**  
```bash
git clone https://github.com/your-repository/heart-disease-prediction.git
cd heart-disease-prediction
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Notebook**  
Use **Google Colab** or Jupyter Notebook to execute the steps.  

## **Future Enhancements**  
- Implement hyperparameter tuning for further optimization.  
- Apply deep learning models for improved accuracy.  
- Enhance feature engineering for better insights.  

## **License**  
This project is open-source and available under the MIT License.  

## **Acknowledgments**  
Special thanks to the contributors and publicly available datasets that made this project possible.
