# Weather-Report-Using-GUI

A simple Java-based desktop application that provides real-time weather updates using the OpenWeatherMap API. The app includes a basic Graphical User Interface (GUI) that lets users enter a city name and instantly view the current weather conditions including temperature, humidity, and atmospheric pressure.

## 🌤️ Features

- Retrieve real-time weather data for any city
- Display:
  - Current weather condition
  - Humidity
  - Atmospheric pressure
- Lightweight and easy-to-use GUI

## 📦 Requirements

- Java 8 or later
- Maven
- Internet connection (for API access)
- OpenWeatherMap API Key *(You need to obtain your own API key from [here](https://openweathermap.org/api))*

## 🛠️ Installation

### Step 1: Clone the Repository


`git clone https://github.com/dhakshayanigodavarthy/Weather-Report-GUI-Java.git
⁠ `

Rename the folder if you'd like:

`mv Weather-Report-GUI-Java Weather-Report-Using-GUI`

`cd Weather-Report-Using-GUI`


### Step 2: Add your OpenWeatherMap API Key

Open the Java file that contains the API call (e.g., `WeatherFetcher.java`) and replace the placeholder with your actual API key:

 ⁠`java
String apiKey = "YOUR_API_KEY_HERE"`;


### Step 3: Build the Project

 ⁠bash
mvn install


⁠ This will generate the `.jar` file in the `target/` directory.

## 🚀 Usage

To run the application:

 
`java -jar target/weather-report-0.1-SNAPSHOT.jar`


Once the application starts:

1. Enter the name of a city into the input field.
2. Press `Enter`.
3. The GUI will update to display the current weather details.

## 📝 License

This project is licensed under the MIT License.
See the [LICENSE](https://opensource.org/licenses/MIT) for more details.
