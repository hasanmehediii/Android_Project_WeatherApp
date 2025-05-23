# WeatherApp

Download the .apk file in your mobile to run the application

- Link: [Drive](https://drive.google.com/drive/folders/1v6ZTG5L9biWKp6_-cMf-C0tvbJWvnNP1).
- Video: [Demo](https://youtube.com/shorts/JoENU6rynCQ?si=Yd2e_0YYbaBQ3Jo-).
# Weather App

A simple Kotlin-based weather application that allows users to search for a city and view real-time weather details, including temperature, weather conditions, local time, and other relevant information. This app provides an intuitive and seamless experience for checking the weather anywhere around the world.

## Features

- **City Search**: Enter the name of a city to search for weather information.
- **Weather Data**: Displays current weather conditions such as temperature, humidity, wind speed, and weather description.
- **Weather Icon**: Shows the corresponding weather condition image (e.g., sunny, rainy, cloudy).
- **Local Date & Time**: Displays the local date and time of the selected city.
- **Additional Info**: Includes other useful data like pressure, visibility, etc.

## Technologies Used

- **Kotlin**: The main programming language used for building the app.
- **OpenWeatherMap API**: Provides the real-time weather data and condition images.
- **Android SDK**: For developing the Android application (if it's an Android app).
- **Retrofit**: For making network requests to fetch weather data from the API.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/hasan-mehedii/Android_Project_WeatherApp.git
2. Open the project in Android Studio (or any Kotlin-compatible IDE).

3. Make sure you have the necessary dependencies configured in your `build.gradle` file:

   ```gradle
   dependencies {
       implementation "com.squareup.retrofit2:retrofit:2.x.x"
       implementation "com.squareup.retrofit2:converter-gson:2.x.x"

   }  ```

4. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and add it to your project:
5. To Run on your mobile, Generate the apk file in: Build -> Bind Apk

## Usage

1. Launch the app on your Android device.
2. Enter a city name in the search bar and press search.
3. View real-time weather data including temperature, humidity, wind speed, and weather conditions.
4. Observe the local time and date of the selected city.

## Screenshots

| ![UI](images/pic1.jfif) | ![UI](images/pic2.jfif) |
|:-------------------:|:------------------:|

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

For any queries, feel free to reach out:
- **GitHub**: [hasan-mehedii](https://github.com/hasan-mehedii)
- **Email**: [mehedi-2022415897@cs.du.ac.bd](mailto:mehedi-2022415897@cs.du.ac.bd)

