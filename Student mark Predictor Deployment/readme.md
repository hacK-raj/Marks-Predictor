# 🎓 Student Mark Predictor

This is a simple web application built with **Flask** and **Machine Learning** that predicts student marks based on the number of study hours. It uses a **linear regression model** trained on sample data.

## 🔍 Project Overview

- 📈 **Input:** Number of hours a student studies.
- 🎯 **Output:** Predicted marks.
- 💻 **Frontend:** HTML + CSS
- ⚙️ **Backend:** Python (Flask)
- 🧠 **ML Model:** Linear Regression (scikit-learn)

---

## 🔥 Live Demo

👉 [Click here to view the deployed project](https://your-render-link.onrender.com)

> Replace the link with your actual Render deployment URL.

---

## 📁 Project Structure

```
Student-Mark-Predictor/
│
├── static/
│   └── styles.css           # CSS styles
├── templates/
│   └── index.html           # Main HTML page
├── student_mark_predictor.pkl  # Trained ML model
├── app.py                   # Flask application
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## 🚀 Getting Started (Local Setup)

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Student-Mark-Predictor.git
cd Student-Mark-Predictor
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 📦 Deployment (Render)

1. Create a new web service on [Render](https://render.com/)

2. Connect your GitHub repo

3. Use the following **build and start commands**:

   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `python app.py`

4. Make sure your `student_mark_predictor.pkl` file is **inside your repo**.

---

## 📚 Requirements

```
Flask==1.1.1
numpy>=1.18.1
scikit-learn>=0.22.1
pandas>=1.0.1
jinja2==3.1.2
```

---

## 🧠 Model Info

The model used is a simple **Linear Regression** model trained using the `Hours vs Scores` dataset.

---

## 🙇‍♂️ Author

**Rajdeep Seal**\
📧 [Your Email]\
🔗 [LinkedIn or GitHub profile link]

---

## 🌟 Show Your Support

If you liked this project, leave a ⭐ on the repo!

