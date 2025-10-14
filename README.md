# 🧠 ANN Customer Churn Prediction

This project uses an Artificial Neural Network (ANN) built with **TensorFlow** and **Keras** to predict customer churn based on historical data.  
It demonstrates how machine learning can be used to identify customers likely to leave a service.
“I implemented an additional Random Forest model to compare with the ANN results.
From the comparison of both models, the Artificial Neural Network (ANN) and the Random Forest classifier, it is clear that both achieved good performance in predicting customer churn.The Random Forest model achieved an accuracy of about 87% (0.868), which slightly outperformed or matched the ANN model which was 86%(0.854). However, similar to the ANN, it struggled to accurately identify customers who actually exited, which is common in imbalanced datasets.Overall, both models demonstrate strong predictive capability, with Random Forest being slightly more stable and interpretable, while the ANN shows potential for improvement with further tuning or more balanced data.
However,After applying SMOTE(Synthetic Minority Oversampling Technique) to balance the data, I got my Artificial Neural Network accuracy to 82.8%. This is a bit lower than my unbalanced ANN, which was around 86–87%, but now my model can detect exited customers better.I know this small drop in accuracy is normal when using SMOTE because it makes the classes more fair. Compared to my balanced Random Forest, which got 83.7%, my ANN is close but still a little lower.Overall, my balanced Random Forest is more stable, but my balanced ANN shows better sensitivity and fairness.

## 📊 Project Overview
- **Goal:** Predict customer churn using deep learning.
- **Dataset:** Bank Customer Churn dataset (CSV format).
- **Tools:** Python, TensorFlow, Keras, Pandas, NumPy, Matplotlib.
- **Notebook:** `ANN_Customer_Churn_Prediction.ipynb`

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedAbdi-2002/ANN_Customer_Churn_Prediction

## 🧾 License
This project is for academic purposes under Karatina University coursework.
note tha the second ANN document is advanced done


## 👤 Author
**Mohamed Mohamed Abdi - P101/2227G/22**  
Bachelor of Science in Computer Science  
Karatina University  

