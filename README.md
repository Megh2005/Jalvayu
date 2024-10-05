# Jalvayu - Real-Time Weather App

Jalvayu is an Android mobile application designed to provide users with real-time weather information. Built with Kotlin and Jetpack Compose, it utilizes the Retrofit library for API calls and follows the MVVM (Model-View-ViewModel) architecture to ensure separation of concerns and maintainability.

## Problem Statement

In today's fast-paced world, staying updated with the latest weather conditions is essential for various daily activities. However, many existing weather applications are cluttered with unnecessary features and ads, making the user experience overwhelming. Jalvayu solves this problem by offering a clean, focused, and reliable weather application that provides real-time weather data with an intuitive user interface.

## Features

- **Real-Time Weather Updates**: Get up-to-date weather information for your current location or any city worldwide.
- **Modern UI**: Built using Jetpack Compose for a smooth, responsive, and modern user experience.
- **Accurate Data**: Fetches weather data using Retrofit from a reliable API source.
- **MVVM Architecture**: Ensures a clean separation of UI logic and business logic, improving scalability and testability.

## Technical Description

**Tech Stack**:

- **Kotlin**: Programming language used for Android development.
- **Jetpack Compose**: UI toolkit for creating native Android interfaces.
- **Retrofit**: Type-safe HTTP client for consuming REST APIs.
- **MVVM (Model-View-ViewModel)**: Architectural pattern for separating concerns and improving app maintainability.

**Key Components**:

- **Model**: Contains the business logic and handles data management, including fetching weather data from the API.
- **View**: The UI layer, built using Jetpack Compose, which displays the weather data to the user in a clean and intuitive way.
- **ViewModel**: Bridges the View and Model by providing data to the UI and handling UI-related logic.

**API Integration**:

- The app uses Retrofit to fetch real-time weather data from a weather API (e.g., OpenWeather, WeatherAPI). The API responses are parsed and displayed to users in a user-friendly format.

## 🚀 Features

- **Real-Time Weather Updates** :sunny:
- **Interactive UI with Jetpack Compose** :rocket:
- **MVVM Architecture for Clean Code** :building_construction:
- **Seamless Network Calls with Retrofit** :arrows_clockwise:
- **Location-Based Weather Data** :round_pushpin:
- **Customizable Themes** :art:
- **Search Functionality for Any City** :mag_right:

## Contribution

Thank you for considering contributing to Jalvayu! We welcome contributions from everyone. Here are some guidelines to help you get started.

- **Fork the repository**: Click the "Fork" button at the top right of this page to create a copy of this repository in your GitHub account.

- **Clone your fork**: Clone your forked repository to your local machine.

  ```sh
  git clone https://github.com/Megh2005/Jalvayu.git
  cd jalvayu
  ```

- **Create a branch**: Create a new branch for your feature or bugfix.
  ```sh
  git checkout -b feature/your-feature-name
  ```
- **Make your changes**: Implement your feature or bugfix.

- **Commit your changes**: Commit your changes with a descriptive commit message.

  ```sh
  git add .
  git commit -m "Add feature: your feature name"
  ```

- **Push to your fork**: Push your changes to your forked repository.

  ```sh
  git push origin feature/your-feature-name
  ```

- **Create a Pull Request**: Go to the original repository and create a pull request from your forked repository.

## Issue Template
```javascript
ISSUE TITLE =
ISSUE DESCRIPTION = 
EXPECTED BEHAVIOUR =
ACTUAL BEHAVIOUR =
STEPS TO REPRODUCE =
YOUR NAME =
YOUR GITHUB USERNAME =
```
