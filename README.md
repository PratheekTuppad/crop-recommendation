# 🌾 Crop Recommendation System using Django

This is a machine learning-powered crop recommendation web application built using **Django**. It helps farmers and agricultural researchers predict the most suitable crops to grow based on environmental inputs like **NPK**, **temperature**, **humidity**, **soil type**, and more.

---

## 🚀 Features

- 🌱 Predicts top 3 suitable crops
- 🧪 Recommends the best fertilizer for each crop
- 🔍 Supports both Naive Bayes and Logistic Regression algorithms
- ⚠️ Warns when NPK values are too low (e.g., 0)
- 📱 Responsive UI (HTML/CSS) with background image
- 🛠️ Built using Django, Pandas, NumPy, scikit-learn

---

## 🖼️ Preview

> _Screenshots of the project can be added here if available._

---

## 🧠 How It Works

- Takes user input for:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature
  - Humidity
  - pH value
  - Rainfall
  - Soil type
- Runs machine learning model to:
  - Predict 3 best crops
  - Suggest fertilizer based on crop and soil type

---

## 💻 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/PratheekTuppad/crop-recommendation.git
cd crop-recommendation
2. Create virtual environment and install dependencies
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate    # On Windows
# or
source venv/bin/activate # On Mac/Linux

pip install -r requirements.txt
If you don't have requirements.txt, install manually:

bash
Copy
Edit
pip install django pandas numpy scikit-learn
3. Run the server
bash
Copy
Edit
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to use the app.

📁 Project Structure
cpp
Copy
Edit
crop_recommendation/
├── crop_recommendation/
│   ├── settings.py
│   ├── urls.py
├── templates/
│   ├── index.html
│   └── result.html
├── static/
│   └── styles/
├── views.py
├── manage.py
└── README.md
🤝 Contributing
Pull requests are welcome! Feel free to improve the UI, add more ML models, or expand datasets.
