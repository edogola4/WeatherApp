# Weather App

A simple yet powerful weather application built with Django, leveraging the OpenWeatherMap API to provide real-time weather information and a 7-day weather forecast for any city around the world.

## Features

- Search for current weather and 7-day forecasts by city name.
- Displays temperature, humidity, and general weather conditions.
- User-friendly interface with responsive design.
- Error handling for invalid city names and API errors.

## Technologies Used

- Django: A high-level Python web framework for rapid development.
- OpenWeatherMap API: A service to fetch weather data.
- Bootstrap: A popular front-end framework for developing responsive web applications.
- HTML/CSS: For structuring and styling the web application.
- JavaScript (optional): For potential future enhancements.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/edogola4/weather-app.git
   cd weather-app

### Create a virtual environment (optional but recommended):

python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`


### Install requirements:

pip install django requests

### Set up the Django project:

*** Navigate to the project directory**
cd weatherapp

**Run the following command to apply migrations**
python3 manage.py migrate

### Add your OpenWeatherMap API key:
**Open views.py and replace the placeholder with your actual API key**
api_key = 'YOUR_API_KEY'


### Run the development server:
python3 manage.py runserver


### Usage
Enter the name of a city in the search box and hit the search button.
The application will display the current weather along with a 7-day forecast, including temperature and humidity.
If an invalid city is entered, an error message will be displayed.


### Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.


### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgments
OpenWeatherMap for providing the weather API.
Bootstrap for responsive design components.


### Contact
For any questions or inquiries, please reach out to me:

Name: Edwin Ogola
Email: edogola4@gmail.com
GitHub: edogola4