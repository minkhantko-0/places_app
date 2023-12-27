# fav_places_app

# fav_places_app

This Flutter project focuses on utilizing native device features such as camera and location access, as well as storing data locally on the device storage.

## Features

- **Camera Access**: The app allows users to capture and upload photos using the device's camera.
- **Location Access**: Users can access their current location and view it on a map within the app.
- **Local Data Storage**: The app provides functionality to store data locally on the device, allowing users to save their favorite places.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/fav_places_app.git`
2. Navigate to the project directory: `cd fav_places_app`
3. Install dependencies: `flutter pub get`
4. Run the app: `flutter run`

# Configuration

1. You will need a valid Google's API key which as Geocoding, Maps and Maps Static API Services enabled.
2. You will need to replace your API key in the App in files listed below.
   - In `fav_places_app/lib/widgets/location_input.dart` you will need to replace the value of the `apiKey` variable with your API key
   - In `fav_places_app/lib/widgets/screens/places_detail.dart` you will need to replace the value of the `apiKey` variable with your API key
3. You will need to follow the instructions from `https://pub.dev/packages/google_maps_flutter` to enable Google Maps functionality for respective
   platforms(IOS, Android).

## Usage

1. Launch the app on your device or emulator.
2. Grant the necessary permissions for camera and location access.
3. Explore the app's features, including capturing photos, viewing the current location, and saving favorite places.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
