[README (1).md](https://github.com/user-attachments/files/30199607/README.1.md)
# Weather Alert App

A simple weather app made using Flutter. It shows the current weather 
of your location and sends a notification if bad weather is expected.

This is one of my first Flutter projects.

## Features
- Shows current weather (temperature, condition, humidity, wind)
- Sends a notification for bad weather (rain, storms, extreme temp)
- Pull down to refresh
- Simple UI

## Built With
- Flutter
- Dart
- OpenWeatherMap API
- flutter_local_notifications
- geolocator

## Getting Started

1. Clone this repo
```
git clone https://github.com/your-username/weather-alert-app.git
```

2. Install dependencies
```
flutter pub get
```

3. Add your OpenWeatherMap API key in `lib/services/weather_service.dart`
```
static const String apiKey = "YOUR_API_KEY_HERE";
```

4. Run the app
```
flutter run
```

## Project Structure
```
lib/
  main.dart
  models/
    weather_model.dart
  services/
    weather_service.dart
    notification_service.dart
  screens/
    home_screen.dart
```

## To-Do
- Add city search
- Better UI
- Add weekly forecast
- Dark mode
