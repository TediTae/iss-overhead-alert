# ISS Notifier 🚀

A simple Python script that sends you an email notification when the International Space Station (ISS) is passing over your location **and** it's dark enough to see it.

## 🌟 Features

- Tracks the real-time location of the ISS.
- Checks if the ISS is near your location.
- Verifies if it's currently night at your location.
- Sends an automatic email alert if both conditions are true.
- Perfect for learning, automation projects, and space enthusiasts.

## 📦 Requirements

- Python 3.7 or higher
- The following Python libraries:
  - `requests`
  - `datetime`
  - `smtplib` (built-in)
  - `time`

## ⚙️ Setup & Usage

1. **Clone the repository**
2. Install dependencies:
  - pip install requests
3. Edit the configuration:
- In the main.py file, update the following values:
  - MY_EMAIL = "your_email@gmail.com"
  - MY_PASSWORD = "your_app_password"  # Use an app password if you're using Gmail.
  - MY_LAT = 38.250351  # Replace with your latitude
  - MY_LONG = 27.990453  # Replace with your longitude
4. Run the app: main.py

## 🛰️ APIs Used
- Open Notify - ISS Current Location API
- Sunrise-Sunset API

## 📚 Inspiration
- This project was inspired by the "ISS Overhead Notifier" lesson in Angela Yu’s 100 Days of Code - Python Bootcamp.

## 📄 License
- This project is licensed under the MIT License.

## Contact
tolgayilmaz1377@gmail.com
