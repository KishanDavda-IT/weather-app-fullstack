# ☁️ DevWeather | Full-Stack API Integration

A high-performance weather dashboard that bridges the gap between clean UI and backend logic. This project demonstrates how to handle enterprise-grade data from the **Tomorrow.io REST API**.

## 🚀 Key Features
* **Live Network Inspector:** A custom-built console that visualizes the `GET` request and the `JSON` response in real-time.
* **Data Transformation:** Maps Tomorrow.io's numeric weather codes to human-readable text and dynamic FontAwesome icons.
* **Pure Black UI:** Designed with an OLED-ready aesthetic for high contrast and modern look.
* **Asynchronous Logic:** Uses `async/await` and `try/catch` for robust error handling.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Glassmorphism), JavaScript (ES6+)
* **API:** [Tomorrow.io v4 API](https://www.tomorrow.io/)
* **Icons:** FontAwesome 6.4

## 📖 How it Works
1. User enters a location (City or Coordinates).
2. The app initiates a fetch request to the Tomorrow.io `realtime` endpoint.
3. The **Network Monitor** captures the raw JSON payload before the UI updates.
4. Data is parsed and transformed into a user-friendly weather card.
