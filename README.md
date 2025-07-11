# 📡 ConfamNetwork – Nigeria's Network Health Tracker

**ConfamNetwork** is a mobile and web-based solution that helps users track, report, and visualize mobile network strength across Nigeria. The platform uses passive signal logging and real-time crowdsourced data to generate a live heatmap of mobile network quality by location and provider.

---

## 🚀 Features

### 📱 Mobile App (React Native)
- Auto-detect and log poor mobile signal 
- Background ping tests
- Manual network test with latency, upload/download speed
- Real-time network condition reporting
- View nearby network ratings and history

### 🗺️ Web Dashboard (React)
- Interactive heatmap of mobile network quality
- Filter by network provider, location, or date
- Live updates powered by aggregated crowd data

### 🔧 Backend (Node.js + Express + MongoDB)
- Secure API for collecting and serving network health data
- Geo-indexed database for fast heatmap queries
- Scheduled data aggregation and analytics endpoints

---


## 🧠 Use Cases
- Users checking which network works best in their area
- Remote workers, students, and travelers avoiding poor signal zones
- Data collection for telecom advocacy and transparency
- ISPs and service providers identifying weak zones

---

## 🛠️ Tech Stack

| Layer     | Technology                  |
|-----------|-----------------------------|
| Frontend  | React Native (Expo), React.js, Tailwind |
| Backend   | Node.js, Express.js         |
| Database  | MongoDB Atlas + GeoJSON     |
| Maps      | Google Maps API or Leaflet  |
| Auth      | Anonymous by default        |
| Background | react-native-background-fetch / Expo Task Manager |
