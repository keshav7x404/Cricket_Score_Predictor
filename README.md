# Cricket Score Predictor 🏏

This project is a web application that predicts cricket scores using machine learning.  
It's built with Flask and utilizes a pre-trained model to provide insights into potential scores during a T20 match.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features
- **Predict Live Scores**: Get real-time predictions for cricket scores.  
- **User-Friendly Interface**: Simple and intuitive web interface for inputting match details.  
- **Machine Learning Powered**: Uses a pre-trained model (`pipe.pkl`) for accurate predictions.  

---

## Technologies Used
- **Python**: The core language for the application.  
- **Flask**: Web framework for building and running the application.  
- **Scikit-learn / Pandas / NumPy**: For data manipulation and machine learning.  
- **HTML/CSS**: For the front-end user interface.  

---

## Installation

To get a local copy up and running, follow these steps:

```bash
# Clone the repository
git clone https://github.com/keshav7x404/Cricket_Score_Predictor.git

# Navigate to the project directory
cd Cricket_Score_Predictor

# Create a virtual environment (recommended)
python -m venv venv

# Activate virtual environment
# On Windows use:
venv\Scripts\activate
# On Linux/Mac use:
source venv/bin/activate

# Install the required dependencies
pip install -r requirements.txt
---
#Run the Flask application:
python app.py
├── static/                # Static files (CSS, JS, images)
│   ├── css/
│   └── images/
├── templates/             # HTML templates
│   └── index.html
├── Cricket Score Predictor.ipynb   # Jupyter notebook with model training
├── app.py                 # Flask application
├── pipe.pkl               # Pre-trained machine learning model
├── requirements.txt       # Python dependencies
├── t20_info.csv           # Dataset used for training
└── README.md              # This README file

---


```



Project Link: [Cricket Score Predictor](https://github.com/keshav7x404/Cricket_Score_Predictor)



