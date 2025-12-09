# 📧 Phishing Email Classifier using sapcy as natural language preprocessing 

This project is a machine-learning application that detects whether an email is **phishing** or **ham (safe)**.  
It uses two trained models:

- **Logistic Regression**
- **Support Vector Machine (SVM)**

The app is built with **Streamlit** for easy interaction, you can try it here ([link]((https://myfishingfilter-u2pyk2xucsuownep7k48q4.streamlit.app/)))


This work was inspired by a research article on arXiv ([link](https://arxiv.org/abs/2303.08792)), and the project reproduces and adapts some of the methods proposed in that paper for email phishing detection.
## 🚀App Features

- Upload any `.eml` email file  
- Automatic text extraction and preprocessing  
- Multi-language support using **spaCy**  
- Classification using **Logistic Regression** or **SVM**  
- Visual prediction indicator (0 = ham, 1 = phishing)  
- Phishing Indicator

- ## 📊 Evaluation Results

Below are the key evaluation visuals generated during model training.

### 🔹 Confusion Matrix
This matrix shows how well the model distinguishes between phishing and ham emails:

####  svm_Confusion Matrix
<img width="507" height="432" alt="svm_confusion_matrix" src="https://github.com/user-attachments/assets/3670611a-7155-4ddc-863a-f13dee637eb3" />


####  logistic_Confusion Matrix
<img width="507" height="432" alt="logistic_confusion_matrix" src="https://github.com/user-attachments/assets/3896c70e-5600-443a-96da-d9d803ad632b" />

### 🔹 Logistic Regression vs SVM — Precision & Recall Comparison
This plot compares the precision and recall of both models:
<img width="789" height="390" alt="evaluation_comparison" src="https://github.com/user-attachments/assets/4f54a7c7-1ee2-4c7b-8c47-da05bf2e0c39" />

🙌 Contributions

Feel free to clone and improve the preprocessing, add new models, or optimize the Streamlit UI. 

