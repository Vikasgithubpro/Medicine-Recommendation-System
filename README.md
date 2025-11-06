# 💊 Medicine Recommendation System

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![ML Project](https://img.shields.io/badge/Project-Machine%20Learning-orange)]()

A **Machine Learning-based web application** that recommends appropriate medicines based on symptoms entered by the user.  
Built with **Python**, **Flask**, and **Scikit-learn**, this project helps simplify healthcare decisions through AI-powered suggestions.

---

## 🧭 Table of Contents
- [✨ Features](#-features)
- [📁 Project Structure](#-project-structure)
- [🧠 Tech Stack](#-tech-stack)
- [⚙️ How It Works](#️-how-it-works)
- [🚀 Installation & Setup](#-installation--setup)
- [🧩 Model Details](#-model-details)
- [📸 Screenshots](#-screenshots)
- [📚 Future Enhancements](#-future-enhancements)
- [👨‍💻 Author](#-author)
- [📜 License](#-license)

---

## ✨ Features

✅ Predicts the most suitable **medicine** based on entered symptoms  
✅ Uses a **trained Decision Tree Classifier** model  
✅ Clean and responsive **Flask web interface**  
✅ Real-time **symptom input and result display**  
✅ Lightweight and **easy to deploy locally**

---

## 📁 Project Structure

```bash
Medicine-Recommendation-System/
│
├── dataset/                # Dataset used for model training
├── model/                  # Trained ML models (.pkl files)
├── static/                 # CSS, JS, and image files
├── templates/              # HTML templates for the Flask app
├── app.py                  # Main application file
├── model_training.ipynb    # Jupyter notebook for model creation
├── requirements.txt         # Required dependencies
└── README.md               # Project documentation

# 🧠 Tech Stack

| Category             | Technologies Used     |
| -------------------- | --------------------- |
| **Language**         | Python                |
| **Framework**        | Flask                 |
| **Machine Learning** | Scikit-learn          |
| **Data Handling**    | Pandas, NumPy         |
| **Frontend**         | HTML, CSS, JavaScript |

# ⚙️ How It Works

1️⃣ The user enters one or more symptoms into the web form.
2️⃣ The trained ML model processes these symptoms.
3️⃣ The model predicts the best-matched medicine from the dataset.
4️⃣ The result is displayed instantly on the web page.

# 🚀 Installation & Setup

🔹 Step 1: Clone the repository
git clone https://github.com/Vikasgithubpro/Medicine-Recommendation-System.git
🔹 Step 2: Navigate to the project folder
cd Medicine-Recommendation-System
🔹 Step 3: Install dependencies
pip install -r requirements.txt
🔹 Step 4: Run the Flask app
python app.py
🔹 Step 5: Open in your browser
http://127.0.0.1:5000/

# 🧩 Model Details

Algorithm Used: Decision Tree Classifier
Dataset: Custom dataset (Symptoms → Medicines mapping)
Accuracy: ~95% on test data
Evaluation Metrics: Accuracy, Precision, Recall

# 📚 Future Enhancements

🧾 Generate downloadable prescription reports
🤖 Integrate AI chatbot for medical advice
📱 Build a mobile app version
💊 Add real-time medicine stock and dosage info
🌐 API for hospital or pharmacy integration

# 👨‍💻 Author

Vikas Singh
📂 GitHub: Vikasgithubpro
🌐 Passionate about AI, Machine Learning, and Web Development

# 📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it with proper credit.


