# Diabetes Predictor

## 🚀 Project Overview
This is a **Machine Learning** project that predicts whether a person has diabetes based on medical attributes. The model is built using **Support Vector Machine (SVM)** and deployed using **Flask** as a web application.

## 📌 Features
- Predicts diabetes based on user input.
- Uses **SVM** for classification.
- Scales input features using **MinMaxScaler**.
- Web-based interface built with **Flask**.
- Model trained on a **diabetes dataset**.

## 🛠️ Tech Stack
- **Python** 🐍
- **Flask** (Web Framework)
- **Scikit-Learn** (Machine Learning Model)
- **Pandas & NumPy** (Data Processing)
- **HTML/CSS** (Frontend UI)

## 📊 Dataset Attributes
- **Glucose Level**
- **BMI**
- **Blood Pressure**
- **Pregnancies**
- **Skin Thickness**
- **Insulin**
- **Diabetes Pedigree Function**
- **Age**
- **Outcome** (Diabetes status - 0: No, 1: Yes)

## 🏗️ Project Structure
```
├── static/                # CSS, JS, Images
├── templates/             # HTML Files
│   ├── index.html         # Main UI
├── diabetes.csv           # Dataset
├── model.pkl              # Trained ML Model
├── app.py                 # Flask Application
```

## 📥 Installation & Usage
### 🔹 1. Clone the Repository
```bash
git clone https://github.com/rbpata/Diabetes-Prediction.git
cd Diabetes-Prediction
```

### 🔹 2. Run the Flask App
```bash
python app.py
```

### 🔹 3. Open in Browser
Go to `http://127.0.0.1:5000/` to access the web interface.

## 🎯 Model Training & Deployment
1. **Preprocess Data:** Feature selection and normalization using **MinMaxScaler**.
2. **Train Model:** Support Vector Machine (**SVM**) with **80-20% Train-Test Split**.
3. **Evaluate Model:** Achieved good accuracy on test data.
4. **Deploy Model:** Saved as `model.pkl` and integrated with **Flask API**.

## 📌 Future Improvements
- Improve model accuracy with feature engineering.
- Implement more ML models for better comparison.
- Deploy on **Heroku** or **AWS** for public access.
- Add a **User Authentication System**.

## 🤝 Contribution
Feel free to fork this repository, create a branch, and submit a **pull request**! Open to suggestions and improvements. 🚀

---
**Developed by [Ram Pata]** 🚀 | Let's connect on [LinkedIn](www.linkedin.com/in/ram-pata)!

