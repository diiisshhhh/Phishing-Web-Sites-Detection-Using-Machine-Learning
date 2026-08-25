# Phishing Web Sites Detection Using Machine Learning

A machine learning based web application for detecting whether a given URL is likely to be a phishing website.

## 📌 Project Overview

Phishing websites are designed to imitate legitimate websites and can be used to steal sensitive information such as usernames, passwords, and financial details.

This project uses machine learning and URL-based feature extraction to classify URLs as phishing or legitimate. The trained model is integrated into a web application where a user can enter a URL and receive a prediction.

## 🎯 Objectives

- Detect potentially malicious/phishing URLs.
- Extract useful features from website URLs.
- Train a machine learning classification model.
- Use the trained model to predict new URLs.
- Provide a simple web interface for URL prediction.

## ⚙️ How It Works

1. A URL is provided as input.
2. Relevant features are extracted from the URL.
3. The extracted features are passed to the trained machine learning model.
4. The model predicts whether the URL is phishing or legitimate.
5. The prediction is displayed through the web application.

## 🔍 Feature Extraction

The project includes URL-based feature extraction implemented in `feature.py`.

The extracted URL characteristics are used as input features for the machine learning model.

## 🧠 Machine Learning

The project includes:

- Dataset: `phishing.csv`
- Feature extraction: `feature.py`
- Trained model: `model.pkl`
- Jupyter Notebook: `Phishing URL Detection.ipynb`

The trained model is saved using a pickle file and is used by the application for making predictions on new URLs.

## 🌐 Web Application

The web application is implemented using Python and provides an interface for entering a URL and obtaining its classification result.

### Main Components

- `app.py` — application/backend logic
- `feature.py` — URL feature extraction
- `model.pkl` — trained machine learning model
- `templates/index.html` — web interface
- `static/styles.css` — styling
- `test-url.txt` — sample URL testing

## 🛠️ Technologies Used

- Python
- Machine Learning
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML
- CSS
- Jupyter Notebook
- Pickle

## 📁 Project Structure

```text
Phishing-Web-Sites-Detection-Using-Machine-Learning/
│
├── app.py
├── feature.py
├── model.pkl
├── phishing.csv
├── Phishing URL Detection.ipynb
├── requirements.txt
├── Procfile
├── test-url.txt
│
├── templates/
│   └── index.html
│🚀 Installation

Clone the repository and install the required dependencies:

pip install -r requirements.txt
▶️ Running the Application

Run the application using:

python app.py

Then open the local web address shown by the application in your browser.

📊 Dataset

The project uses phishing.csv as the dataset for developing the phishing URL detection model.

⚠️ Disclaimer

This project is intended for educational and demonstration purposes. The prediction should not be considered a guaranteed determination of whether a website is safe or malicious.

👩‍💻 Author

Disha Pandya
└── static/
    ├── styles.css
    └── img/
