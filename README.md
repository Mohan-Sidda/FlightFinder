#✈️ FlightFinder: Navigating Your Air Travel Options

FlightFinder is a user-friendly web application designed to help travelers effortlessly search, compare, and choose the best air travel options. With an intuitive interface and powerful data filtering, FlightFinder enhances the travel planning experience by delivering real-time flight information based on user preferences.


---

#🔍 Project Overview

In today’s fast-paced world, travelers need access to fast and reliable flight data for effective trip planning. This project addresses that need by providing a seamless interface to navigate various flight options based on filters like source, destination, price range, departure time, and airline preference.
FlightFinder helps users:
Search and compare flights from multiple airlines.
Filter results based on criteria like price, stops, travel time, etc.
View essential flight details in a clean and responsive UI.

---

#🛠️ Tech Stack Used

Category	Technology
Frontend	HTML, CSS, JavaScript, Bootstrap
Backend	Flask (Python)
Database	SQLite
APIs/Data	External Flight Dataset / API (Mock)
Tools & Libraries	Pandas, Flask-Cors, Requests

---

#💡 Features

🔎 Search Flights: Enter source, destination, and date to fetch relevant flights.
🧭 Sort & Filter: By price, duration, airline, or number of stops.
📱 Responsive UI: Built with Bootstrap for mobile and desktop compatibility.
📊 Flight Details: Key insights like fare, duration, departure, arrival time.

---

#📁 Project Structure

FlightFinder/
│
├── static/
│   └── styles.css
├── templates/
│   ├── index.html
│   └── results.html
├── app.py
├── flights_data.csv
├── requirements.txt
└── README.md

---

#🚀 How to Run the Project

Prerequisites
Python 3.8 or above
pip (Python package installer)
Installation Steps
1. Clone the repository:
git clone https://github.com/Mohan-Sidda/FlightFinder.git
cd FlightFinder
2. Install dependencies:
pip install -r requirements.txt
3. Run the Flask server:
python app.py
4. Open your browser and visit:
http://127.0.0.1:5000/
