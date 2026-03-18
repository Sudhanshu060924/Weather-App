# 🌦️ Weather App (Java Servlet)

A simple weather web application built using **Java Servlet, JSP, HTML, CSS, and JavaScript** that fetches real-time weather data using an external API.

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays temperature
* 💧 Shows humidity
* 🌬️ Wind speed information
* ☁️ Weather condition display

---

## 📁 Project Structure

```
├── Myservlet.java   # Backend servlet (API handling)
├── index.html      # Input UI (city search)
├── index.jsp       # Result display page
├── script.js       # Client-side logic
├── style.css       # Styling
```

---

## ⚙️ How It Works

1. User enters a city name in `index.html`
2. Request is sent to `Myservlet.java`
3. Servlet calls weather API and gets JSON response
4. Data is processed and forwarded to `index.jsp`
5. Weather details are displayed to the user

---

## 🔑 API Key Setup

⚠️ This project uses a weather API. You must add your own API key.

### Option 1: Environment Variable (Recommended)

#### Windows

```
setx WEATHER_API_KEY "your_api_key"
```

#### Mac/Linux

```
export WEATHER_API_KEY="your_api_key"
```

---

## ▶️ How to Run

1. Add this project to **Apache Tomcat**
2. Place `Myservlet.java` inside proper package structure
3. Deploy and run server
4. Open in browser:

```
http://localhost:8080/YourProjectName
```

---

## ⚠️ Note

* This repository contains only core files (not full project setup)
* `.env`, build files, and IDE configs are excluded for security and simplicity

---

## 🚧 Future Improvements

* Add 5-day forecast
* Improve UI design
* Add error handling
* Make responsive for mobile

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
