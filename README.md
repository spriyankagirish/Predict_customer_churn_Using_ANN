# 💼 Churn Modelling Using ANN


## 🧠 About the Project

This app uses an Artificial Neural Network (ANN) to predict customer churn for a bank. Churn prediction helps businesses proactively identify customers likely to leave and take preventive action.

---

## 🛠️ Built With

- **Python**
- **TensorFlow / Keras**
- **Scikit-learn**
- **Gradio** *(for creating the web UI on Hugging Face)*
- **Pandas / NumPy**

---

## 📦 Features

- Interactive input form to simulate customer profiles
- Predicts whether a customer will churn (`Yes` or `No`)
- Displays confidence score of the prediction
- Clean and responsive Streamlit interface

---

## 📊 Dataset

Used a cleaned dataset containing:
- Customer demographics (e.g., Geography, Gender, Age)
- Banking behavior (e.g., Balance, Credit card status)
- Target column: `Exited` (1 if the customer left, 0 if they stayed)

---

## 🧮 Model Architecture

- Input layer: preprocessed features (after encoding and scaling)
- 2 Hidden layers with ReLU activation
- Output layer with Sigmoid activation for binary classification

---

## 📈 Model Performance

- Accuracy: **~85%** on test data  
- Optimizer: `Adam`  
- Loss Function: `binary_crossentropy`

---

## 💡 How to Use

1. Go to the Hugging Face Space link.
2. Fill in the customer details in the form.
3. Click **Predict**.
4. View prediction and probability score.

---
## 🔗 ScreenShot
![image](https://github.com/user-attachments/assets/6f8b1be3-994f-4292-b0a6-071ae7833013)
![image](https://github.com/user-attachments/assets/e0c33f7b-5594-4d6b-ab04-61373c27eca5)


---
## 🔗 Links

- 🌐 [Live Demo on Hugging Face]https://huggingface.co/spaces/PriyankaSG/Predict_customer_churn_Using_ANN

 

### Note on Dataset Access

To maintain data privacy and prevent misuse, the dataset used in this project is not uploaded directly to this repository.

**If you're a recruiter or collaborator who would like to access the dataset**, please request access here: [Google Form link]https://drive.google.com/file/d/1AwQTlHnbOGjPHwE8ZwmbfmyhsOffdvII/view?usp=sharing

Once approved, you’ll receive a link to the dataset via Google Drive within 24 hours.

*This ensures project security while keeping it fully reproducible.*

In Your Code (Notebook or Script):

# Dataset not included in the public repo
# Please request access using the link in the README to get the dataset





