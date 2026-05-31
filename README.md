
## Overview: What is Vayunetra?

**Vayunetra (वायुनेत्र)** is a premium, feature-rich **Atmospheric Intelligence Platform** designed to provide real-time weather analytics, air quality monitoring, and climate insights. Built with a sleek, responsive dashboard interface, it bridges the gap between raw meteorological data and user-friendly, actionable intelligence.

---

## Core Features & Functionalities

### 1. Real-Time Atmospheric Tracking

* **Detailed Current Conditions:** Tracks essential metrics including temperature, humidity, wind speed, UV index, barometric pressure, "feels like" temperature, and dew point.
* **Air Quality Index (AQI):** Integrates live AQI reporting with explicit safety health status indicators (e.g., Excellent, Moderate, Unhealthy).
* **Wind Compass:** Displays a visual, dynamic compass module that rotates in real time to show wind directions (N, NE, E, etc.).

### 2. Predictive Forecasting & Visual Analytics

* **Hourly & 10-Day Forecasts:** Offers an hourly scroll view for immediate planning alongside a broad 10-day weather outlook.
* **Data Visualization Charts:** Uses smooth line and bar charts to graph **7-day temperature trends** (mapping daily maximums/minimums) and **7-day precipitation levels**.

### 3. Solar & Astronomical Intelligence

* Tracks precise daily sunrise and sunset timings.
* Computes day versus night length to provide solar efficiency insights.
* Features a unique **"Golden Hour" countdown badge** that alerts users when optimal photography or outdoor lighting is approaching.

### 4. Interactive Maps & Global Awareness

* **Live Radar Visualization:** Embedded interactive maps that allow users to toggle between different environmental layers like Rain, Clouds, Temperature, or a Default terrain view.
* **Global Climate News Feed:** Pulls up-to-date environmental, climate, and storm news via an automated RSS feed.
* **Disaster & Severe Weather Alerts:** Actively monitors atmospheric risks to flag immediate danger hazards like heatwaves or flash storms.

### 5. Smart Capabilities & Accessibility

* **AI Insights Companion:** Features an intelligent analysis algorithm that processes local data to give automated recommendations (e.g., "Strong UV radiation. Apply SPF 50+").
* **Smart AI Chatbot Integration:** Embedded with an instant Chatbase virtual assistant to help users seamlessly navigate atmospheric queries.
* **Immersive Visual Design:** Employs advanced canvas rendering engines for dynamic weather backgrounds that change into sunny rays, falling rain, night stars, or flashing lightning based on local conditions.
* **High Accessibility Options:** Includes immediate dark mode/light mode switching alongside a **High Contrast Accessibility Mode** and pre-configured settings to respect users who prefer reduced on-screen motion.

---

## Technical Stack Architecture

The application is engineered as a highly optimized, single-page application relying entirely on free, open-source APIs (meaning no restrictive API keys are required):

| Layer | Technologies & Frameworks Used |
| --- | --- |
| **Frontend Foundation** | Semantic HTML5, CSS3 (Fluent design language with advanced frosted-glass frosting styles), Vanilla JavaScript (ES6+). |
| **Data APIs** | **Open-Meteo API** (for global meteorological/AQI data), **Nominatim OpenStreetMap** (for address geocoding), and the **Sunrise-Sunset API**. |
| **Mapping & Charts** | **Leaflet.js** (for smooth radar map rendering) and **Chart.js** (for rendering predictive trend graphs). |
| **Assistant Integration** | **Chatbase Embed Script** (for the AI helper widget). |

---

## Technical Performance Optimization

* **Persistent Cache Engine:** Features an intelligent local-storage caching mechanism that preserves weather data for up to an hour. This ensures an ultra-fast layout paint on reload and eliminates redundant API network requests.
* **Debounced System Calls:** Search fields and map switches are completely debounced to handle rapid user input gracefully without lag.
* **Idle State Optimization:** Utilizes page visibility event listeners to pause intensive visual canvas rendering whenever a user switches browser tabs, saving processing hardware and battery life.

---

> **Developer Credits:** Built and designed by **Swastik Pattanayak**. Operating globally under the mandate of *Free Atmospheric Intelligence for All*.
