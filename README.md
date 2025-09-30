![Parkle Thumbnail](thumbnail.png)

# Parkle

## Overview
Parkle is an intelligent location assistant designed to help you effortlessly find any saved spot or item—whether it's your parked car, bike, luggage, tent, or any other important location. Leveraging advanced location algorithms, sensor fusion, and real-time navigation, Parkle eliminates the stress of losing track of your belongings or places in large, busy, or unfamiliar environments.

## Core Use Cases
- Instantly save the location of your car, bike, luggage, tent, or any item with a single tap.
- Navigate back to your saved spot using a dynamic arrow and interactive map.
- Monitor real-time distance, direction, and step count as you walk.
- Receive persistent, actionable notifications and arrival alerts.
- Re-route navigation with one click if you need to restart your search.

## Key Features
- **Dynamic Arrow Navigation:** Real-time directional guidance to any saved location, adapting to your movement and orientation.
- **Satellite Map Integration:** Visualize your position and your saved spot on a high-resolution map.
- **Step & Movement Tracking:** Accurately counts steps and detects movement for enhanced navigation feedback.
- **Persistent Live Notifications:** Foreground notifications (Google Maps style) with sound, keeping you informed throughout your journey.
- **Re-route Functionality:** Instantly restart navigation if you need to search again.
- **Customizable Distance Units:** Choose between meters, kilometers, feet, or centimeters for personalized feedback.
- **Location Name Personalization:** Save and display a custom name for any location or item.

## Technology & Algorithms
- **Distance Calculation:**
  - Utilizes the Haversine formula for precise global distance measurement.
  - Employs Euclidean, Manhattan, and Chebyshev formulas for local, context-aware distance estimation.
- **Sensor Fusion:**
  - Integrates compass, accelerometer, and gyroscope data for accurate heading, movement, and step detection.
- **Proximity Detection:**
  - Implements a multi-zone system (far, near, close, here) based on distance and confidence metrics.
- **Location History & Precision:**
  - Maintains both high-accuracy and general location readings to optimize navigation reliability.
- **Cross-Platform Architecture:**
  - Built with Flutter for seamless UI and business logic, and Kotlin for advanced Android notification and foreground service management.

## Screenshots
Showcase the app's interface and features:

```
![Home Screen](screenshots/home.png)
![Arrow Navigation](screenshots/arrow.png)
![Map View](screenshots/map.png)
![Notification](screenshots/notification.png)
```

Place your screenshots in the `screenshots` directory within your project.

---

For further details, please refer to the source code and documentation.

