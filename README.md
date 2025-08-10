# 🗺️ Leaflet + OpenRouteService (ORS) Route Map

An interactive map built with **[Leaflet.js](https://leafletjs.com/)** and **[OpenRouteService API](https://openrouteservice.org/)** that displays a driving route between two points.

## 📌 Features
- Interactive Leaflet map.
- Background map tiles from **OpenStreetMap**.
- Fetches driving route data from **ORS Directions API**.
- Draws the route in blue with start & end markers.
- Auto-zooms to fit the full route.

---

## 📂 Project Structure
📦 leaflet-ors-map
┣ 📜 index.html # Main map page
┗ 📜 README.md # Project documentation

## 🛠️ Getting Started

### 1️⃣ Get an ORS API Key
1. Create an account at [openrouteservice.org](https://openrouteservice.org/sign-up/).
2. Generate a free API key from your dashboard.

---

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/Varunkkumar/Leaflet-OpenRouteService-ORS-Route-Map.git
cd leaflet-ors-map

3️⃣ Add Your API Key
Open index.html and replace:

const apiKey = "YOUR_ORS_API_KEY";
with your real api key
