Here's a detailed README file template for your assignment:

---

 Assignment 2: React Native Applications

This repository contains multiple small React Native applications developed as part of **Assignment No. 2** for the course. Each app demonstrates different features and functionalities in React Native, ranging from weather tracking to unit conversions. Below are the details of each app, the instructions to run them, and challenges encountered during development.

Table of Contents
1. [Weather App](#weather-app)
2. [Tip Calculator](#tip-calculator)
3. [Stopwatch App](#stopwatch-app)
4. [BMI Calculator](#bmi-calculator)
5. [Currency Converter](#currency-converter)
6. [Unit Conversion App](#unit-conversion-app)
7. [Quiz App](#quiz-app)
8. [Dark Mode Implementation](#dark-mode-implementation)
9. [Step Counter App](#step-counter-app)
10. [Recipe App](#recipe-app)
11. [Installation and Setup](#installation-and-setup)

---

### 1. Weather App

**Task**: A simple weather app that fetches and displays current weather for a city using the OpenWeather API.

- **Features**:
  - Search bar for city input.
  - Displays temperature, humidity, and weather icon.

**Challenge**: Implemented search functionality and displayed a relevant weather icon based on the API response.

---

### 2. Tip Calculator

**Task**: A calculator that allows users to enter a bill amount, choose a tip percentage, and calculate the total amount.

- **Features**:
  - Choose between 10%, 15%, and 20% tip.
  - Split the bill between multiple people.

**Challenge**: Added functionality for bill splitting and calculating per person payment.

---
3. Stopwatch App

Task: A stopwatch with start, stop, and reset functionality.

- **Features**:
  - Time displayed in minutes, seconds, and milliseconds.
  - Smooth operation using React Native’s `useEffect` hook.

Challenge: Ensured the stopwatch continues running even when the app is minimized.

---

4. BMI Calculator

Task: A calculator that computes BMI based on height and weight inputs.

- Features:
  - Calculates and displays BMI.
  - Message displayed based on the BMI result (Underweight, Normal, Overweight, Obese).

Challenge**: Provided clear inputs and displayed corresponding BMI messages.

---

5. Currency Converter

Task: Convert between different currencies using the ExchangeRatesAPI.io.
Features:
  - Real-time currency conversion.
  - Ability to save favorite currency pairs.

**Challenge**: Implemented currency saving for quicker access.

---

6. Unit Conversion App

Task: Convert between various units of measurement (length, weight, temperature, etc.).

Features:
  - Categories like length, weight, and temperature.
  - Easy-to-use selection for conversion.

**Challenge**: Allow users to select from different categories of conversions.

---

7. Quiz App

Task: A multiple-choice quiz app with a score displayed at the end.

Features:
  - Timer for each question with a countdown display.
  - Score shown after completion.

Challenge: Implemented countdown timers for each question to ensure fair play.

---

8. Dark Mode Implementation

Task: Add dark mode to the quiz app.
Features:
  - Dark mode using React Native's `Appearance API` or `useColorScheme` hook.
  - Manual toggle for switching modes.

Challenge: Ensured dark mode persisted even after app restart.

---

9. Step Counter App

Task: A step tracker that uses React Native’s pedometer or sensor APIs to track steps.

- Features:
  - Daily steps tracked with auto-reset at midnight.
  - Notification when reaching a goal (e.g., 10,000 steps).

Challenge: Displaying daily total and providing a reset mechanism.

---

 10. Recipe App

Task: A recipe app with details for each recipe.

Features:
  - Navigation using React Navigation between home screen and recipe detail screen.
  - Search bar for filtering recipes by name or category.

Challenge: Seamless navigation between home and recipe detail screens.

---

 Installation and Setup

To run the apps locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the app:

   ```bash
   npx expo start
   ```

4. Choose your preferred emulator or scan the QR code with the Expo Go app.

---

Challenges Encountered

- Ensuring the **stopwatch** continued functioning in the background required using React Native's `useEffect` hook to manage timer state effectively.
- In the **tip calculator**, handling bill splitting and ensuring the correct distribution across people was an interesting challenge that was addressed by adding proper validation and rounding logic.
- For the **weather app**, integrating with the OpenWeather API and parsing the response data to show the correct weather icon required careful handling of API responses.
