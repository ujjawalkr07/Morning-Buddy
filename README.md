# 🌞 Morning Buddy — Your AI-Powered Morning Assistant

**Morning Buddy** is a Streamlit-based web app that makes your mornings more productive and positive.  
It brings together **motivation, weather, personalized news, and smart day planning** — all powered by **Google Gemini AI**.

---

## ✨ Features

### 🏠 Home — Start with Inspiration
- Displays a **random motivational quote** and a **refreshing morning image** from Unsplash.
- Simple, peaceful interface to brighten your start of the day.

### 🌤️ Get Weather of Your City
- Fetches **real-time weather data** from the OpenWeather API.
- **Gemini AI** converts raw weather data into friendly, human-readable updates:
  - Temperature (°C), feels-like, humidity, and wind speed
  - Sunrise/sunset times
  - Smart suggestions on what to wear or carry ☂️🧥🕶️

### 📰 News by Interest
- Get the **latest 5 news articles** tailored to your interests (Technology, Sports, Health, etc.) using **NewsAPI**.
- Each article includes:
  - Headline, image, and direct source link 🔗  
  - **AI-generated summary** for quick reading and understanding

### 🗓️ Smart Planner
- Creates a **personalized daily itinerary** using:
  - Local weather forecast ☁️  
  - Nearby events 🎭  
  - Recommended places to visit 🏙️  
- The **Gemini AI planner** organizes your day chronologically:
  - Morning → Afternoon → Evening
  - Suggests activities, meal breaks, and event links
  - Adjusts recommendations based on weather and local happenings

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| Framework | Streamlit |
| Language | Python |
| AI Model | Google Gemini 2.5 Flash |
| APIs Used | OpenWeather · NewsAPI · SerpAPI · Google Search |
| Environment | dotenv for API key management |

---
