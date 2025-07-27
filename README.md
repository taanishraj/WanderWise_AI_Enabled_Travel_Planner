# 🌍 WanderWise – AI Enabled Travel Planner

**WanderWise** is an AI-powered travel planning tool that provides personalized destination recommendations based on user preferences. It combines machine learning, interactive UI, and real-time data to make trip planning smarter and easier.

---

## 🚀 Features

- 🧠 AI-driven travel recommendations using trained ML models  
- 📍 Destination images and metadata for better visualization  
- 🗣️ Multilingual support via translation module  
- 🌦️ Weather integration (weather display module assumed)  
- 📊 Pre-trained models using `holidify.csv` for destination analysis  
- 🔍 User-friendly interface powered by Flask  

---

## 🛠 Tech Stack

- **Backend:** Python, Flask  
- **AI/ML:** Scikit-learn, Joblib, Pandas, NumPy  
- **Frontend:** HTML/CSS (Flask templates assumed)  
- **Data:** `holidify.csv`, Pickle & Joblib ML models  
- **Tools:** Jupyter Notebook (`model1.ipynb`), `.env` config  

---

## 📁 Project Structure

```plaintext
WanderWise/
├── app.py                                  # Main Flask app
├── model1.ipynb                            # Jupyter notebook for training
├── holidify.csv                            # Dataset for recommendations
├── travel_model.pkl                        # Trained ML model (basic)
├── travel_recommendation_enhanced.pkl     # Enhanced ML model
├── travel_recommendation_enhanced.joblib  # Joblib model variant
├── translations.py                         # Language translation logic
├── weather_display.py                      # (If implemented) Weather support
├── requirements.txt                        # Python dependencies
├── .env                                    # Environment variables (e.g. API keys)
├── images/
│   ├── bengaluru.jpg
│   ├── chennai.jpg
│   ├── mysuru.jpg
│   └── ...                                 # Other destination images
└── README.md                               # Project documentation
```

---

## 🧪 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/taanishraj/WanderWise_AI_Enabled_Travel_Planner.git
cd WanderWise_AI_Enabled_Travel_Planner

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

---

## 📌 Usage

- Open your browser and go to `http://localhost:5000`  
- Input your travel preferences  
- Get destination suggestions with images and weather details  

---

## 📈 Future Improvements

- Live API integration (weather, maps, hotel booking)  
- User login & trip history  
- Enhanced UI/UX with better visuals  
- Online deployment (Heroku, Railway, etc.)

---

## 👨‍💻 Author

- [@taanishraj](https://github.com/taanishraj)

---

