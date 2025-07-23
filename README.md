#  Community Health and Diet Recommendation System (Flask App)

This project is a Flask web application that predicts BMI categories, vitamin deficiencies, and generates personalized weekly diet plans based on user input (age, height, weight, disease, and vitamin deficiency). It uses machine learning models and datasets for inference.

##  Features

- BMI calculation and classification
- Vitamin deficiency prediction and food recommendations
- Disease-based weekly diet plan using ML
- Healthy balanced weekly diet for non-patients
- Web-based user interface using HTML templates

##  Tech Stack

- **Frontend**: HTML, CSS (Jinja templates)
- **Backend**: Python Flask
- **Machine Learning**: Scikit-learn models (`.pkl` files)
- **Data Handling**: Pandas, Numpy

##  Folder Structure

```
├── app.py
├── requirements.txt
├── README.md
├── templates/
│   ├── index.html
│   └── result.html
├── static/
│   └── (optional: css, images, etc.)
├── bmi_classifier.pkl
├── vitamin_model.pkl
├── vitamin_encoder.pkl
├── disease_encoder.pkl
├── diet_model1.pkl
├── label_encoder_disease1pkl
├── full.csv
```

##  Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/health-diet-flask-app.git
cd health-diet-flask-app
```

2. **Create and Activate Virtual Environment (Optional)**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the App**

```bash
python app.py
```

Visit `http://127.0.0.1:5000/` in your browser.

##  Machine Learning Models

- `bmi_classifier.pkl`: Predicts BMI category
- `vitamin_model.pkl`: Predicts disease from vitamin deficiency
- `diet_model1.pkl`: Recommends weekly meal plan for diseases
- Label encoders for vitamin and disease categories

##  Dataset

- `full.csv`: Contains mappings of vitamin deficiencies to recommended and avoidable foods.

##  To-Do / Future Enhancements

- Add authentication (login/signup)
- Enable multiple user sessions
- Improve UI with Bootstrap
- Upload personal health reports
- Export diet plan to PDF

##  Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

##  License

This project is licensed under the MIT License.

##  Author

- **Your Name**
- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
