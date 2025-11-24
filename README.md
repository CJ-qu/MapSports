# Mapty // Map your workouts 🏃‍♂️🚴‍♀️

![Mapty Logo](logo.png)

## 📖 Description

Mapty is a web application that allows users to log their running and cycling workouts based on their location. It uses the Geolocation API to get the user's current position and renders a map using the Leaflet library. Users can click on the map to add a new workout, which is then stored in the browser's Local Storage, ensuring data persistence across sessions.

This project was built as part of Jonas Schmedtmann's JavaScript course to practice Object-Oriented Programming (OOP), working with external libraries, and managing application state.

## ✨ Features

- **Geolocation**: Automatically fetches your current location to center the map.
- **Map Interaction**: Click anywhere on the map to log a workout.
- **Workout Types**: Support for **Running** and **Cycling**.
- **Custom Data**:
  - **Running**: Distance, Duration, Cadence, Pace.
  - **Cycling**: Distance, Duration, Elevation Gain, Speed.
- **Popups**: Custom markers and popups on the map displaying workout details.
- **List View**: All workouts are listed in a sidebar for easy access.
- **Move to Marker**: Clicking a workout in the list moves the map to the corresponding marker.
- **Local Storage**: Workouts are saved in the browser, so they remain available after reloading the page.

## 🛠 Technologies Used

- **HTML5** & **CSS3**
- **JavaScript (ES6+)**
  - Classes & OOP
  - Geolocation API
  - Local Storage API
- **[Leaflet](https://leafletjs.com/)** - Open-source JavaScript library for mobile-friendly interactive maps.

## 🚀 How to Run

1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/mapty.git
    ```

2.  **Open `index.html`**
    Simply open the `index.html` file in any modern web browser. No build step or server is required.

## 📸 Screenshots

![App Architecture](Mapty-architecture-final.png)

## 📚 Learnings

This project focuses on:
- Planning application architecture (Flowcharts & Class Diagrams).
- Using the **Geolocation API**.
- Integrating third-party libraries (**Leaflet**).
- Managing data with **Local Storage**.
- Implementing **Object-Oriented Programming** in JavaScript.

## © Credits

Based on the "Complete JavaScript Course" by [Jonas Schmedtmann](https://twitter.com/jonasschmedtman).

---
&copy; Copyright by Chuanjie Qu.
