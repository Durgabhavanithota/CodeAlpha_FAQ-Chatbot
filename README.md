# 🛒 E-Commerce FAQ Chatbot

## 📌 Project Overview

The E-Commerce FAQ Chatbot is an NLP-based customer support chatbot that answers frequently asked questions related to online shopping.

The chatbot uses **TF-IDF** and **Cosine Similarity** to understand a user's question and find the most relevant FAQ from a self-created dataset containing 20 questions and answers.

## 🎯 Objectives

* Provide quick answers to common e-commerce questions
* Understand different ways of asking similar questions
* Handle unknown or unrelated questions
* Provide a simple and user-friendly chatbot interface

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLP
* TF-IDF
* Cosine Similarity
* Gradio
* Jupyter Notebook

## 🧠 How It Works

```text
User Question
      ↓
Text Cleaning
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Find Best Matching FAQ
      ↓
Return Answer
      ↓
Gradio Chatbot Interface
```

## 📊 Dataset

The chatbot uses a **self-created dataset** containing 20 e-commerce FAQ questions and their corresponding answers.

The dataset covers topics such as:

* Orders
* Payments
* Delivery
* Order tracking
* Returns
* Refunds
* Accounts
* Passwords
* Customer support

No external dataset was used.

## 💬 Example Questions

* How can I track my order?
* Can I return a product?
* How can I reset my password?
* What payment methods do you accept?
* How long does delivery take?

## ✨ Features

* FAQ-based customer support
* Natural language question matching
* TF-IDF text representation
* Cosine similarity matching
* Unknown question handling
* Greeting and goodbye responses
* Interactive Gradio interface
* Suggested questions

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open `faq_chatbot.ipynb` using Jupyter Notebook or JupyterLab.

### 4. Run the notebook

Run the cells from top to bottom.

### 5. Launch the chatbot

Run the final Gradio cell to open the chatbot interface.

## 📁 Project Structure

```text
FAQ-Chatbot/
│
├── faq_chatbot.ipynb
├── faq_dataset.csv
├── faq_dataset_cleaned.csv
├── README.md
└── requirements.txt
```

## 🚀 Future Improvements

* Add more FAQ questions
* Improve semantic understanding using advanced NLP models
* Add conversation memory
* Connect the chatbot to a real e-commerce database
* Deploy the chatbot as a web application

## 👩‍💻 Project Type

AI / NLP / Machine Learning Project
