# Classy Weather

The **Classy Weather** is an intuitive React application that provides users with accurate and real-time weather forecasts based on their location. With a clean interface and engaging visuals, it allows users to easily track daily weather conditions, including temperatures and weather icons.

## Features

- **Location Search**: Enter a location to get its current weather forecast.
- **Real-Time Updates**: Fetch the latest weather data seamlessly.
- **Weather Icons**: Dynamic weather icons representing different weather conditions.
- **Temperature Display**: Clear presentation of daily maximum and minimum temperatures.
- **Country Flags**: Displays the corresponding country flag next to the location name.

## Components

The project is organized into the following React components:

- **App**: The main component that manages state and renders the application layout.
- **Input**: A component for users to enter their desired location.
- **Weather**: Displays the weather information for the selected location.
- **Day**: Represents an individual day's weather, showing temperatures and conditions.

## How It Works

1. Users can input a location into the search bar. The app will fetch geographical data for the specified location.
   
2. Once the location is verified, the app retrieves the weather forecast using the location's latitude and longitude.

3. The weather data is displayed, including daily maximum and minimum temperatures along with the corresponding weather conditions represented by icons.

4. The country flag for the specified location is shown next to the location name for easy identification.

## Technologies Used

- **React**: For building the user interface and managing state.
- **CSS**: For styling components and ensuring a responsive design.
- **JavaScript (ES6+)**: Core language for building the application logic.
- **Open-Meteo API**: For fetching weather data based on geographical location.

## Screenshots

![image](https://github.com/user-attachments/assets/7604488b-e741-4183-b217-ddbe54533621)


## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ClassyWeather.git
   ```
2. **Install the dependencies**:
   ```bash
   npm install
   ```
3. **Start the application**:
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.
