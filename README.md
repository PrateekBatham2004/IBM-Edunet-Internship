# Employee Income Prediction Project 💼

This project is a complete machine learning pipeline designed to predict whether an individual's annual income is greater than $50,000 or less than or equal to $50,000. The prediction is based on census data, and the final model is deployed as an interactive web application.

---

### **🚀 Live Demo**

You can access the live, deployed web application here:

**[https://216f2b72ded4.ngrok-free.app/](https://216f2b72ded4.ngrok-free.app/)**

*Note: As this is a temporary ngrok tunnel, the link may expire. Refer to the Google Colab link in the project file.*

---

### **Project Overview**

The core of this project is a binary classification task. Using the "Adult" dataset from the UCI Machine Learning Repository, we analyze demographic and employment-related attributes to build a predictive model. The project covers the entire machine learning lifecycle, from data cleaning and preprocessing to model training, evaluation, and finally, deployment as a user-friendly web app.

### **✨ Features of the Web App**

The deployed application, built with Streamlit, offers two primary modes of prediction:

* **Single Prediction:** Users can manually input an individual's details (age, workclass, education, etc.) through a sidebar form to get an instant income class prediction.
* **Batch Prediction:** Users can upload a CSV file containing multiple employee records. The application processes the file and returns the original data with an added "Predicted Income" column, which can then be downloaded.

---

### **🤖 Model Performance**

Several classification algorithms were evaluated, including Logistic Regression, Random Forest, and SVM. The best-performing model was the **Gradient Boosting Classifier**, which achieved an accuracy of **85.81%** on the test set. This model was saved and used for the final deployment.

---

### **🛠️ Tech Stack & Libraries**

This project utilizes a range of open-source libraries:

* **Data Analysis & ML:** `pandas`, `scikit-learn`
* **Data Acquisition:** `gdown`
* **Visualization:** `matplotlib`
* **Model Persistence:** `joblib`
* **Web App & Deployment:** `streamlit`, `pyngrok`

---
