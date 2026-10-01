# Support Ticket Search System

## 📌 Overview

The **Support Ticket Search System** is a Python-based application that helps users search and find relevant customer support tickets using **Natural Language Processing (NLP)** and text similarity techniques.

The system uses **TF-IDF (Term Frequency–Inverse Document Frequency)** and **Cosine Similarity** to compare a user's search query with existing support tickets and identify relevant results.

## 🎯 Objectives

* Build a simple support-ticket search system.
* Process text data using NLP techniques.
* Convert ticket text into numerical representations using TF-IDF.
* Calculate similarity between a search query and support tickets.
* Display the most relevant tickets to the user.

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **TF-IDF**
* **Cosine Similarity**
* **NLTK**
* **NumPy**
* **HTML/CSS**

## 🔍 Key Features

* Search support tickets using natural-language queries.
* Text preprocessing using NLP techniques.
* TF-IDF-based text representation.
* Cosine similarity-based matching.
* Displays relevant support tickets.
* Simple web interface using Flask.
* Ticket assignment functionality.

## 📂 Project Structure

```text
support-ticket-search/
│
├── app.py
├── assign.py
├── tickets.txt
├── requirements.txt
├── templates/
│   └── ...
├── screenshots/
│   └── ...
└── README.md
```

## ⚙️ How It Works

The system follows these basic steps:

1. The user enters a search query.
2. The ticket data is loaded from the available ticket dataset.
3. Text is processed using NLP techniques.
4. TF-IDF converts the text into numerical vectors.
5. Cosine Similarity compares the query with the ticket vectors.
6. The most relevant tickets are identified.
7. The results are displayed through the
