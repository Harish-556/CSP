#  Community Health & Diet Recommender System

This web-based intelligent health assistant is built using **Flask** and various **Machine Learning models**. It offers:
- BMI calculation & classification
- Vitamin deficiency analysis & related disease prediction
- Personalized 7-day diet recommendations
- Downloadable health report
- General health tips

---

##  Features

-  BMI Prediction and Categorization
-  Disease Prediction from Vitamin Deficiency
-  Foods to Eat and Avoid based on Deficiency
-  Personalized Weekly Diet Plan based on Disease and Age
-  Clean & Responsive UI with Sidebar Navigation
-  Downloadable PDF-style Health Report (via Print)

---

##  Technologies Used

- **Frontend**: HTML, CSS, Jinja2 (Flask templates)
- **Backend**: Flask (Python)
- **Machine Learning**: Scikit-learn models (saved as .pkl using joblib)
- **Data Handling**: Pandas, NumPy

---

##  Project Structure

```
├── app.py                     # Main Flask application
├── full.csv                   # Vitamin to Food Mapping CSV
├── bmi_classifier.pkl         # Model for BMI classification
├── vitamin_model.pkl          # Vitamin deficiency to disease model
├── diet_model1.pkl            # Weekly diet plan model
├── vitamin_encoder.pkl        # LabelEncoder for vitamin names
├── disease_encoder.pkl        # LabelEncoder for diseases
├── label_encoder_disease1pkl  # LabelEncoder for diet model
├── templates/
│   ├── index.html             # Input form template
│   └── result.html            # Results and recommendations
├── requirements.txt
└── README.md
```

---

## Installation & Running Locally

1. **Clone the repository**

```bash
git clone https://github.com/your-username/health-diet-dashboard.git
cd health-diet-dashboard
```

2. **Create virtual environment (recommended)**

```bash
python -m venv venv
source venv/bin/activate     # Linux/macOS
venv\Scripts\activate      # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the Flask app**

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

##  Screenshots

<img width="1908" height="688" alt="image" src="https://github.com/user-attachments/assets/c857d938-c001-4b25-89cd-4b44ce871fc4" />
<img width="1900" height="685" alt="image" src="https://github.com/user-attachments/assets/1b5257ee-545a-4a8e-9a24-68943971d675" />
<img width="1886" height="526" alt="image" src="https://github.com/user-attachments/assets/4aec4bb0-a421-4ace-93f9-2ff108309eef" />
<img width="1781" height="841" alt="image" src="https://github.com/user-attachments/assets/d60553cd-2965-4e12-9dde-a2272a003b32" />
<img width="1791" height="833" alt="image" src="https://github.com/user-attachments/assets/e93b68f6-db9a-4d63-abb0-fe57314644fd" />






##  Model Details

- Trained using scikit-learn
- Encoded vitamin and disease labels using LabelEncoder
- Stored in `.pkl` format using `joblib`

---

##  License

This project is licensed under the MIT License.

---

##  Author

- **Name**: Harish Varma
- **Email**: your.email@example.com
- **GitHub**: [your-username](https://github.com/your-username)

---

##  Contributions

Pull requests and suggestions are welcome. Let's improve community health together!
