# bmi_calculator_app

This project is a BMI Calculator App built using Flutter, designed to calculate a user's Body Mass Index (BMI) based on their height and weight. Below are the details about its functionality and purpose:

Project Purpose
The app aims to provide an easy-to-use interface for calculating BMI and determining the user's health category based on their BMI. It is suitable for individuals who want to monitor their fitness and overall health.

Key Features
User-Friendly Input Interface
Users can input their height, weight, and age via sliders and buttons.
The app provides visual feedback with interactive card components.
Gender Selection
Users can select their gender (Male or Female) using intuitive toggle buttons.
BMI Calculation
The app calculates BMI using the formula:

​	
 
Height is measured in centimeters and weight in kilograms.
Result Display
After calculation, the app navigates to a Result Screen that shows:
The calculated BMI.
A descriptive category (e.g., Underweight, Normal, Overweight, Obese).
A brief interpretation of the BMI score to guide users.
Attractive Design
It uses Material Design principles for a modern, clean look.
The app includes custom widgets such as:
ReusableCard: Reusable containers for user interaction.
RoundIconButton: For adjusting weight and age incrementally.
BottomButton: For navigation to the result page.
How It Works
Input Page
Users interact with sliders and buttons to set their:
Gender.
Height (120cm–220cm).
Weight.
Age.
Gender selection is highlighted dynamically with color changes.
Calculation
When users press the "Calculate" button, the app:
Validates inputs (e.g., gender selection).
Calculates BMI using the inputs.
Determines the BMI category and interpretation.
Result Page
The app displays:
BMI Value (e.g., "22.5").
Health Category (e.g., "Normal").
Interpretation (e.g., "You have a normal body weight. Good job!").
Users can navigate back to adjust inputs.
Technologies and Libraries Used
Flutter Framework: To build the UI and handle logic.
Dart Programming Language: For application logic and component interactions.
FontAwesome Flutter Package: For gender icons.
Custom Widgets: Reusable components for efficiency and clean code.
Target Audience
This project is designed for:

Fitness enthusiasts.
Individuals interested in monitoring their health.
Anyone looking for a quick and reliable BMI calculation tool.
Possible Extensions
Health Tips
Provide personalized tips based on BMI results.
Storage
Save past BMI calculations for progress tracking.
Unit Conversion
Allow switching between metric and imperial units.
Customization
Add themes and more gender options.


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
