# Traffic-volume-estimator

**Traffic-volume-estimator** is a machine learning-powered traffic volume estimator built using Flask for web deployment, Jupyter Notebook for experimentation, and Spyder for local development. It analyzes features like weather, time, and date to predict traffic volume, helping cities and developers gain real-time road usage insights.

---

## 🔧 Tech Stack

- 🐍 Python 3.x
- 📘 Jupyter Notebook (for training and analysis)
- 🧪 Spyder (IDE used)
- 🌐 Flask (for the web interface)
- 📊 Pandas, NumPy, Scikit-learn, Matplotlib

---

## 📁 Project Structure

```bash
Traffic-volume-estimator/
Traffic-volume-estimator/
├── app.py                        # Flask application
├── model.pkl
├── static/
│   └── images/
│       ├── Car.jpg
│       └── Traffic.jpg
├── templates/
│   ├── index.html                # Main form page
│   └── output.html               # Output results page
├── notebook/
│   └── traffic volume estimation1.ipynb
│   └── traffic volume estimation1-checkpoint.ipynb
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation


## Installation Method

```bash
# 1. Clone the repository
git clone https://github.com/your-username/Traffic-volume-estimator.git
cd Traffic-volume-estimator

# 2. Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate          # On Windows, use: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask application
python3 app.py
