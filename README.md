# 🌦️ Weather App

A simple **Weather Forecast Web Application** built using **Django**.
This app allows users to search for any city and view real-time weather information such as temperature, humidity, and weather conditions.

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays temperature
* 💧 Shows humidity level
* ☁️ Weather condition description
* 🎨 Simple and clean UI
* 🔄 Real-time API data fetching

---

## 🛠️ Technologies Used

* Python
* Django
* HTML
* CSS
* OpenWeatherMap API (or any weather API)

---

## 📂 Project Structure

```
weather_project/
│
├── weather/
│   ├── migrations/
│   ├── templates/
│   │   └── weather/
│   │       └── index.html
│   ├── static/
│   ├── views.py
│   ├── models.py
│   ├── urls.py
│
├── weather_project/
│   ├── settings.py
│   ├── urls.py
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate virtual environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If requirements.txt is not available:

```bash
pip install django requests
```

---

## 🔑 API Configuration

1. Create an account on OpenWeatherMap.
2. Generate your API key.
3. Open `views.py`.
4. Replace:

```python
API_KEY = "your_api_key_here"
```

with your actual API key.

---

## ▶️ Run the Project

```bash
python manage.py runserver
```

Open browser and visit:

```
http://127.0.0.1:8000/
```

---

## 📌 Future Improvements

* 🌤️ 7-day forecast
* 📍 Detect user location automatically
* 🌙 Dark mode
* 📱 Responsive design improvements

---

## 👨‍💻 Author

**JITENDRA ROUT**
Python Full Stack Developer

---

## 📜 License

This project is for educational purposes.
