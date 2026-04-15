# 🌱 AgroSnap – AI-Powered Smart Farming Assistant

⭐ Built for helping farmers make data-driven decisions

AgroSnap is an AI-driven platform that helps farmers **identify crop diseases, get treatment recommendations, and track real-time market prices** — all in their local language.

It combines **computer vision + government data APIs** to support better decision-making and reduce crop losses.

---

## 📌 Problem Statement

Farmers often face challenges in:

* Identifying crop diseases early
* Accessing reliable treatment advice
* Tracking accurate market prices

This leads to reduced yield and financial loss.

---

## 💡 Solution

AgroSnap provides:

* Instant crop analysis using AI
* Actionable treatment suggestions
* Live mandi (APMC) price tracking

All through a simple, user-friendly interface.

---

## 🚀 Key Features

* 🤖 **AI Crop Analysis**
  Detect diseases, pests, and deficiencies using image input

* 💊 **Smart Recommendations**
  Get treatment and prevention suggestions

* 💰 **Real-Time Market Prices**
  Access live data from Government APIs

* 📊 **Price Trends**
  Visualize historical and current price patterns

* 🗣️ **Multilingual Support**
  English, Hindi, Marathi, Telugu, Tamil

* 📄 **PDF Reports**
  Download analysis for offline use

---

## 🛠️ Tech Stack

* **Python** (Core Logic)
* **Streamlit** (Frontend + UI)
* **FastAPI / Express.js** (Backend APIs)
* **Google Gemini Vision API** (Image Analysis)
* **Data.gov.in API** (Market Data)
* **Plotly** (Visualization)
* **Pillow (PIL)** (Image Processing)

---

## ⚙️ How It Works

1. User uploads a crop image
2. Image is processed using Gemini Vision API
3. Disease / issue is detected
4. Recommendations are generated
5. Market data is fetched via APIs
6. Results displayed in dashboard

---

## 📂 Project Structure

```
AgroSnap/
├── backend/
│   ├── app.py
│   ├── main.py
│   ├── server.js
│   ├── style.css
│   └── requirements.txt
├── .streamlit/
├── package.json
└── README.md
```

---

## ⚡ Getting Started

### Prerequisites

* Python 3.8+
* Node.js (optional)
* API Keys (Gemini + Data.gov.in)

---

### Run the App

```bash
streamlit run backend/app.py
```

---

## 📊 Key Learnings

* Built an **end-to-end AI-powered application**
* Integrated **multiple APIs (AI + government data)**
* Designed **data-driven user workflows**
* Worked on **real-world problem solving in agriculture**

---

## 🚀 Future Improvements

* Improve AI accuracy
* Add more regional language support
* Deploy as a web/mobile application

---

## 🤝 Contributing

Feel free to fork and improve the project!

---


