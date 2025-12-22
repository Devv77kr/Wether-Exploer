# Weather-Exploer
📌 Project Overview
Weather Explorer is a web application that shows real-time weather for any city and gives smart recommendations like whether it is a good time to go for a walk or if driving visibility is clear.
# pic bad weather and good weather
<img width="1766" height="941" alt="Screenshot 2025-09-04 215128" src="https://github.com/user-attachments/assets/ac4d3a8c-a8a1-4a96-ae1e-6c9a5dc75992" />

<img width="1281" height="541" alt="Screenshot 2025-09-22 192044" src="https://github.com/user-attachments/assets/fedbce11-9017-471b-ab2f-b458f312bf09" />

 
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
