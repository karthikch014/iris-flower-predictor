# 🌸 Iris Flower Predictor - Machine Learning Project

![Iris Flower](https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg)

A beginner-friendly machine learning project to predict the species of an Iris flower (Setosa, Versicolor, Virginica) based on user-input flower measurements. The model is trained using the Iris dataset from Scikit-learn and deployed using Streamlit for easy accessibility.

---

## 📌 Features

- 🔍 Predicts flower species from 4 features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- ✅ User-friendly web interface using Streamlit
- 🧠 Trained using a Logistic Regression model
- 🌐 Deployed on Streamlit Cloud
- 💡 Ideal for beginners to learn ML + deployment

---

## 🚀 Live Demo

👉 [Click here to view the live app](https://iris-flower-predictor-frdisth8uhu6fqv2rigft4.streamlit.app/)

> Replace the above link with your actual Streamlit deployment URL after publishing.

---

## 🧠 Technologies Used

| Tool / Library      | Purpose                         |
|---------------------|---------------------------------|
| Python              | Programming language            |
| Scikit-learn        | ML model & Iris dataset         |
| Pandas, NumPy       | Data preprocessing              |
| Streamlit           | Web app framework               |
| Git & GitHub        | Version control & hosting       |

---

## 📁 Project Structure

```
iris-flower-predictor/
│
├── app.py               # Streamlit application code
├── requirements.txt     # List of required packages
├── Procfile             # For deployment
├── README.md            # Project documentation
└── .gitignore           # Files to ignore in Git

```

---

## 🧪 How to Run Locally

### 🖥️ Prerequisites:
- Python installed (3.7+)
- Git installed

### 🛠️ Steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/karthikch014/iris-flower-predictor.git
   cd iris-flower-predictor
2. **Create and Activate Virtual Environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   venv/bin/activate  # On Mac/Linux
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
4. **Run the App**
```bash
  streamlit run app.py
