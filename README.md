# 🏥 **New York Workers’ Compensation Board (WCB) - Claim Injury Prediction**  

## **📌 Abstract**  
The **New York Workers’ Compensation Board (WCB)** faces significant challenges in **manually processing claims**, a time-intensive task that impacts efficiency. To address this, we developed **machine learning models** to **automate the prediction of claim outcomes**.  

This project approached the **claim injuries problem** from two perspectives:  
1️⃣ **Multiclass Classification** – Predicting the **final decision** on claim injury types.  
2️⃣ **Binary Classification** – Predicting whether a **worker would reach an agreement or not**.  

Using **labeled data from claims filed between 2020 and 2022**, this project includes:  
✔ **Exploratory Data Analysis (EDA)**  
✔ **Feature Selection** (Spearman Correlation, LASSO, Mutual Information, Decision Trees, Random Forest)  
✔ **Machine Learning Model Development**  

---

## **📊 Machine Learning Models**  

### **🛠 Feature Selection Approaches**  
We experimented with various feature selection techniques to enhance model performance:  
- 📌 **Spearman Correlation**  
- 📌 **LASSO Regularization**  
- 📌 **Mutual Information** for encoded categorical features  
- 📌 **Decision Trees & Random Forest Feature Importance**  

### **🚀 Models Tested**  
We experimented with several **machine learning algorithms**, including:  
- **Baseline Models**:  
  - ✅ Logistic Regression  
  - ✅ K-Nearest Neighbors  
  - ✅ Decision Trees  
  - ✅ Gaussian Naive Bayes  
  - ✅ Multi-layer Perceptron (MLP)  

- **Ensemble & Boosting Models**:  
  - ✅ Random Forest  
  - ✅ AdaBoost  
  - ✅ Gradient Boosting  
  - ✅ XGBoost  
  - ✅ LightGBM  
  - ✅ CatBoost  
  - ✅ Bagging Classifier  

---

## **🏆 Best Performing Models**  

| Classification Type | Best Model | f1 Score |
|---------------------|--------------------------|---------|
| **Multiclass** | Voting Classifier (Random Forest + LightGBM) | **0.4549** |
| **Binary** | Voting Classifier (Logistic Regression + Gaussian Naive Bayes + Gradient Boosting) | **0.6284** |

---

## **🖥️ Interactive Interface**  
📌 **An interface was also developed** to visualize and interact with the model predictions.  
🔗 You can find it in my GitHub repository: **"ML_Interface"**  

---

## **📂 Download Dataset & Additional Files**  
🔗 [Click here to download additional resources](https://liveeduisegiunl-my.sharepoint.com/:f:/g/personal/20230083_novaims_unl_pt/EkvfYn9s0UpMgLeSkQteCVcBaRuXNhLBVwmiu1B8llVeTQ?e=XjOuHL)  

---

## **📌 Notes & Limitations**  

🔹 The **encoding process** could be improved for better generalization.  
🔹 **More models** could have been tested, but **dataset size constraints** limited experimentation.  

---

## **🔍 Conclusion & Future Work**  

As with every project, **limited resources** (time and computational power) posed constraints. However, several avenues for **future improvements** can be explored:  

🚀 **Deployment on Cloud Platforms**  
- Implementing the model on **AWS SageMaker** using **MLOps tools** (e.g., Kubeflow) could improve **scalability and monitoring**.  

🧠 **Advanced Deep Learning Approaches**  
- **Exploring deep learning models** with **PyTorch** or **Keras** could enhance performance for complex datasets.  
- **Ensemble deep learning** models might provide **more robust predictions**.  

💡 **Quantum Machine Learning Potential**  
- Although still in its infancy, **quantum computing** could enable **faster computations** and better handling of **large datasets**.  

⚠ **Challenges Faced**:  
- **Significant class imbalance** affected model generalization.  
- **Lengthy training times** limited experimentation with **hyperparameter tuning** and **alternative models**.  
- **Deploying in a cloud-based environment** with scalable resources **could have enabled faster experimentation** and **testing of more sophisticated algorithms**.  

---

## 📢 **Final Thoughts**  
Despite the challenges, this project demonstrated the **potential of machine learning** in **automating claim processing** and improving **operational efficiency** for the **New York Workers’ Compensation Board**.  

📌 **This project serves as a foundation** for further **optimization and deployment in real-world settings!** 🚀  

---

👨‍💻 **Author:**  
✉️ **Jorge Cordeiro**  


