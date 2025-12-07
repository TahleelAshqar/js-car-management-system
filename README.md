# js-car-management-system
A small JavaScript application for managing car data: adding cars, storing them in an array, browsing between existing cars, and dynamically rendering car information in a table. Includes OOP with a Car class, private fields, and DOM manipulation with jQuery.

# Car Management System 🚗

A JavaScript-based web application for adding, storing, and browsing car information.  
Users can enter car details (name, color, year, license number, price, and photo URL), and the system dynamically updates the display using DOM manipulation and a custom Car class.

## Features
- Add new cars through a form.
- Store cars in an in-memory array.
- Each car is represented by a dedicated `Car` class with a private ID field.
- Browse between cars using "Next" and "Back" navigation.
- Automatically renders car details with a photo inside an HTML table.
- jQuery used for input handling and element selection.

## How It Works
- User inputs are read with jQuery selectors.
- The `Car` class generates a unique ID for every new car.
- The `cars` array stores all created cars.
- Functions `next()`, `back()`, and `showCar()` handle browsing.
- `showCar()` dynamically removes the last row and inserts updated car information.

## Technologies Used
- HTML
- JavaScript (OOP + DOM manipulation)
- jQuery

## File Overview
- `cars.html` — UI layout, form input fields, table structure, and navigation buttons.
- `cars.js` — JavaScript logic for creating, storing, and displaying cars.

## Author
Created by Tahleel (تهليل)
