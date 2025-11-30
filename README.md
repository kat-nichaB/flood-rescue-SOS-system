# 🚨 HelpMeOut SOS — Open Flood Emergency Map & Reporting System

[![Deploy to Netlify](https://img.shields.io/badge/Deploy-Netlify-blue?logo=netlify)](https://www.netlify.com/)
[![Version](https://img.shields.io/badge/Version-1.0.0-green)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()

---

**HelpMeOut SOS** is an open-source web application designed for rapid emergency reporting during floods or natural disasters.  
It allows affected individuals—or relatives reporting on their behalf—to submit their location, condition, urgency level, and photos.  
All data is saved instantly to Google Sheets via Google Apps Script and displayed on a live volunteer dashboard.

The project is **mobile-first**, lightweight, and designed for fast real-world deployment by non-technical users.

---

## 📌 Key Features

### For People in Need
- 🧑‍🤝‍🧑 Report Name of affected person
- 📞 Phone number
- 👪 Optional: reporter name & phone (for relatives)
- 📍 Pin location manually or auto-detect GPS
- 🏠 Write address / landmarks (กรอกที่อยู่ + จุดสังเกต)
- 📸 Upload photos via imgBB API
- ⚡ Urgency levels (Low / Medium / High)
- 📱 Works 100% on mobile

### For Volunteers / Dashboard
- 🌍 Realtime map via OpenStreetMap
- 🟢🔴🟡 Color-coded markers
- 👥 Assign volunteers to assist quickly

---

## 🖼️ Screenshot / Mockup

![Dashboard Mockup](https://via.placeholder.com/800x400.png?text=HelpMeOut+SOS+Mockup)

*Screenshot shows color-coded map with markers and volunteer dashboard.*

---

## 🚀 Deployment

### Option 1: Netlify (Recommended)
1. Go to [Netlify](https://www.netlify.com/) and Sign Up / Sign In.
2. Click **Add new site → Deploy manually → Drag & Drop**.
3. Drag the project folder containing `index.html`, CSS, JS into Netlify.
4. Netlify generates a live HTTPS URL automatically.

### Option 2: Vercel (via GitHub)
1. Push your project folder to a GitHub repository.
2. Go to [Vercel](https://vercel.com/) and Sign Up / Sign In.
3. Click **New Project → Import Git Repository → Select your repo → Deploy**.
4. Vercel provides a live URL with HTTPS automatically.

---

## ⚙️ Configuration
- **Google Apps Script Web App URL:**  
`https://script.google.com/macros/s/YOUR_WEB_APP_URL/exec`  
- Set this URL in `index.html` to send form data to Google Sheets and upload photos.

- **imgBB API Key:**  
Set in JS script to handle image uploads.

---

## 📂 Project Structure
