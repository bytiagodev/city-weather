# 🌤️ Weather Watch // Logic Experiment

A clean, real-time weather dashboard built to explore the world of **External APIs** and **Asynchronous JavaScript**. This was one of my first real challenges handling live data and system errors.

[**Live Demo**](https://bytiagodev.github.io/weather-app-js/)

---

### 🧠 The Journey
Building this dashboard was my "classroom" for **Async JS**. The biggest hurdle wasn't the design, but figuring out how two different APIs talk to each other. 

The **Open-Meteo API** requires coordinates (Latitude/Longitude), but users type city names. I learned how to "chain" fetch requests: first, converting the city name into coordinates (Geocoding), and only then fetching the weather data.

### ✨ What I Explored
*   **Data Logic:** Manipulating JSON objects to extract temperature, wind speed, and weather codes.
*   **User Feedback:** Implementing *Loading* and *Error* states—essential for when the internet fails or a city isn't found.
*   **Dynamic UI:** The background colors change based on the weather (sun, rain, snow), which helped me **work with** DOM class manipulation more effectively.
*   **Glassmorphism Aesthetic:** Experimented with modern "frosted glass" effects using transparency and `backdrop-filter`.

### 🛠️ Tech Stack
*   **HTML5 & CSS3:** Focus on flexible layouts and Satoshi typography.
*   **Vanilla JavaScript:** Pure logic using the `Fetch API` and `Promises`.
*   **Open-Meteo API:** The free data source that made this possible.

---

### 💬 Junior Notes
I am still learning the nuances of API performance and clean code. If you see anything in my logic that could be optimized, I would truly appreciate your feedback!

---
