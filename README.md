# 🚦 Traffic Volume Estimator

**Traffic Volume Estimator** is a machine learning-powered web application that predicts traffic volume based on various inputs such as weather, time, and date. It leverages a trained regression model and provides an intuitive web interface using Flask. The system helps urban planners, developers, and researchers monitor and forecast traffic flow effectively.

---

## 🔧 Tech Stack

- 🐍 **Python 3.x** – Core programming language  
- 📓 **Jupyter Notebook** – For data exploration and model training  
- 🧪 **Spyder** – Used as the local development environment  
- 🌐 **Flask** – Web framework for deployment  
- 📊 **Pandas**, **NumPy**, **Scikit-learn**, **Matplotlib** – For data processing, modeling, and visualization

---

## 📁 Project Structure

The project directory is organized as follows:

Traffic-volume-estimator/
├── app.py # Flask web application
├── model.pkl # Trained ML model (Pickle format)
├── static/
│ └── images/
│ ├── Car.jpg # Background image for output page
│ └── Traffic.jpg # Background image for input page
├── templates/
│ ├── index.html # User input form (traffic details)
│ └── output.html # Prediction result display
├── notebook/
│ ├── traffic volume estimation1.ipynb # Training & analysis notebook
│ └── traffic volume estimation1-checkpoint.ipynb # Auto-saved checkpoint
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## ⚙️ Installation Instructions

Follow these steps to run the application locally:

```bash
# 1. Clone the repository

# 2. Create a virtual environment
python3 -m venv venv

# 3. Activate the environment
source venv\Scripts\activate        # On Linux: venv/bin/activate

# 4. Install required dependencies
pip install -r requirements.txt

# 5. Start the Flask application
python3 app.py
