# 📧 Email Spam Classifier

## Description
This project is a web-based application built using **Streamlit** that classifies emails as Spam or Not Spam. It uses a pre-trained **Naive Bayes Classifier** model and text vectorization with **Count Vectorizer**. The dataset used for training includes labeled email data, enabling the model to effectively distinguish between spam and legitimate emails.

---

## Features
- **Classify Emails**: Enter email content to check if it is spam or not.
- **Interactive Visualizations**:
  - Word clouds for spam and non-spam emails.
  - Distribution plots to visualize the dataset.
- **Lottie Animations**: Engaging animations for a better user experience.
- **Responsive Navigation**: Sidebar navigation for easy access to different sections.

---

## Technologies Used
- **Backend**: Python (Naive Bayes Classifier, Count Vectorizer, Pickle for model persistence).
- **Frontend**: Streamlit (UI framework).
- **Data Visualization**: Matplotlib, Seaborn, and WordCloud.
- **Animations**: Lottie (via `streamlit_lottie`).
