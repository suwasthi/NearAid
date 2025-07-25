# NearAid 
**Smart Helmet Emergency Assistant App**

NearAid is a mobile application designed to work with a smart helmet system. In the event of an accident, the app detects the GPS location, finds the nearest hospital using the Google Places API, and sends the hospital contact number to the microcontroller (e.g., ESP32) via Bluetooth.

---

## Features

-  Real-time GPS location detection
-  Finds nearest hospital using Google Places API
-  Sends hospital contact number to MCU over Bluetooth
-  Designed for quick response after a crash
-  Works with permission handling and user prompts

---

## Tech Stack

- **Flutter** – Cross-platform mobile app development  
- **Google Maps Places API** – For hospital search  
- **Bluetooth (flutter_blue or flutter_bluetooth_serial)** – Communication with MCU  
- **Geolocator** – GPS location access  
- **Permission Handler** – Runtime permissions  

---

## Screenshots

*(Add screenshots of your app UI here if available)*

---

## Getting Started

### Prerequisites

- Flutter SDK installed  
- Android Studio / VS Code with emulator or real device  
- Google Cloud project with Places API enabled  
- Bluetooth-enabled MCU ready to pair (ESP32, etc.)
