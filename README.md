# Weather_App_show_information_By_Raushan
# Weather_App_show_information
A simple, responsive weather application built using HTML, CSS, and JavaScript. This app fetches real-time weather data from the OpenWeatherMap API and displays it to the user based on the searched city name.

Features
Search weather by city name

Displays current temperature, weather condition, humidity, and wind speed

Supports multiple cities worldwide

Responsive design for mobile and desktop

Refreshes data dynamically

Error handling for invalid city names

Tech Stack
Frontend: HTML5, CSS3, Vanilla JavaScript

API: OpenWeatherMap API

Screenshot <img width="1916" height="966" alt="Screenshot 2025-08-21 171244" src="https://github.com/user-attachments/assets/aa0105e0-82ce-4542-9a17-173aa475db30" />

How to Use
Clone the repository:

bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
Open index.html in your browser:

Just double-click or open the file with any live server.

Get your API Key:

Sign up at OpenWeatherMap

Go to the API section and copy your API key

Insert your API key in script.js:

javascript
const apiKey = "YOUR_API_KEY_HERE";
🧪 Example
javascript

const apiKey = "abcd1234";
const url = `https://api.openweathermap.org/data/2.5/weather?q=London&appid=${apiKey}&units=metric`;
error Handling
Displays alert for:

Invalid city name

Network issues

Empty input
Author
Name: Raushan Kumar

GitHub: @raushanrajalone

📄 License
This project is licensed under the MIT License
