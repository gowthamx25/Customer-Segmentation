# Customer Segmentation

This project performs customer segmentation using machine learning (K-Means clustering) and a simple web interface.  
It includes data preprocessing, model logic, clustering, and a UI (Flask app) to display results.

---

## 📌 Project Overview

Customer segmentation divides a customer base into distinct groups based on similarities in data such as spending behavior, demographics, etc.  
This helps businesses tailor marketing, improve customer experience, and make data-driven decisions. :contentReference[oaicite:1]{index=1}

---

## 🔧 Tech Stack
- Python
- Scikit-Learn (K-Means clustering)
- Flask (web UI)
- pandas, numpy
- DVC (data version control)
- Docker (containerization)

---

## 🚀 Features
✔ Load customer dataset  
✔ Train/cluster customers using K-Means  
✔ Visualize results  
✔ Interactive UI to view clusters

---

## 📦 Setup Instructions

1. Clone the repo:
git clone https://github.com/gowthamx25/Customer-Segmentation.git
cd Customer-Segmentation

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate # Mac/Linux
venv\Scripts\activate # Windows

3. Install dependencies:
pip install -r requirements.txt

4. Run the web app:
python app.py

5. Open in browser:
http://localhost:5000

---

## 📈 How It Works

1. Load dataset  
2. Preprocess features  
3. Use K-Means for segmentation  
4. Use cluster labels to understand groups

---

## 🚀 Deployment

You can containerize and deploy this app using:
- **Docker**
- **Render**
- **Railway.app**
- **Heroku**
---
