# Weather-Exploer
📌 Project Overview
Weather Explorer is a web application that shows real-time weather for any city and gives smart recommendations like whether it is a good time to go for a walk or if driving visibility is clear.
# pic of  bad weather and good weather
<img width="1896" height="839" alt="Screenshot 2025-12-22 174008" src="https://github.com/user-attachments/assets/26c297ff-c6c9-4692-89f2-239faf5c0fda" />

<img width="1817" height="822" alt="Screenshot 2025-12-22 174038" src="https://github.com/user-attachments/assets/bce27683-c2d4-4d7a-bab1-42e3fdea9f7b" />


 
# ✨ Features
Search weather by city name (global support).
​

Shows current temperature, description, and weather icon.
​

5‑day forecast with icons and temperatures.
​

Dynamic background changes according to weather (clear, clouds, rain, snow, etc.).
​

Activity recommendation section, e.g.:

Clear → walking, cycling, outdoor sports.

Rain → stay indoors, gym, movies, etc.
​

Simple, responsive UI built with HTML and CSS.
​

🛠️ Tech Stack
HTML5 – Structure of the app.
​

CSS3 – Styling, layout, and dynamic backgrounds.
​

JavaScript (Vanilla JS) – API calls, DOM updates, activity logic.
​

OpenWeatherMap API – Current weather and forecast data.
​

🚀 How to Run Locally
Clone or download the project folder.

Make sure you have the files:

index.html

style.css

script.js
​

Get a free API key from OpenWeatherMap and replace apiKey in script.js with your key.
​

Open index.html directly in your browser (Chrome/Edge/Firefox).

Type a city name in the search box and press Search.

🧠 Activity Recommendation Logic
The app checks the main weather condition (clear, clouds, rain, snow, etc.) and suggests activities:

Clear / Clouds → outdoor activities like walking, jogging, cycling.

Rain / Thunderstorm → indoor activities and avoid unnecessary driving.

Snow → snow sports or staying warm indoors
