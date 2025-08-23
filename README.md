Cricket Score Predictor 🏏This project is a web application that predicts cricket scores using machine learning. It's built with Flask and utilizes a pre-trained model to provide insights into potential scores during a T20 match.Table of ContentsFeaturesTechnologies UsedInstallationUsageProject StructureContributingLicenseContactFeaturesPredict Live Scores: Get real-time predictions for cricket scores.User-Friendly Interface: Simple and intuitive web interface for inputting match details.Machine Learning Powered: Uses a pre-trained model (pipe.pkl) for accurate predictions.Technologies UsedPython: The core language for the application.Flask: Web framework for building the application.Scikit-learn / Pandas / NumPy: For data manipulation and machine learning.HTML/CSS: For the front-end user interface.InstallationTo get a local copy up and running, follow these simple steps.Clone the repository:git clone https://github.com/keshav7x404/Cricket_Score_Predictor.git
Navigate to the project directory:cd Cricket_Score_Predictor
Create a virtual environment (recommended):python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
Install the required dependencies:pip install -r requirements.txt
UsageRun the Flask application:python app.py
Open your web browser and navigate to http://127.0.0.1:5000/.Input the match details (e.g., batting team, bowling team, current score, overs, wickets, runs in last 5 overs) and click "Predict" to see the estimated score.Project Structure.
├── static/                   # Static files (CSS, JS, images)
│   └── css/
│   └── images/
├── templates/                # HTML templates
│   └── index.html
├── Cricket Score Predictor.ipynb # Jupyter notebook with model training
├── app.py                    # Flask application
├── pipe.pkl                  # Pre-trained machine learning model
├── requirements.txt          # Python dependencies
├── t20_info.csv              # Dataset used for training
└── README.md                 # This README file
ContributingContributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.Fork the ProjectCreate your Feature Branch (git checkout -b feature/AmazingFeature)Commit your Changes (git commit -m 'Add some AmazingFeature')Push to the Branch (git push origin feature/AmazingFeature)Open a Pull RequestLicenseDistributed under the MIT License. See LICENSE for more information. (You should create a LICENSE file if you haven't already).ContactKeshavProject Link: https://github.com/keshav7x404/Cricket_Score_Predictor
