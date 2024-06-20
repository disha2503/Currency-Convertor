Currency Converter

A simple web-based currency converter application that fetches the latest exchange rates and converts the specified amount from one currency to another.

Table of Contents
Overview
Features
Technologies Used
File Structure
File Description
Usage

Overview
This project provides a straightforward interface for users to convert amounts from one currency to another using real-time exchange rates. The exchange rates are fetched from the ExchangeRate-API.

Features
Supports a wide range of currencies.
Real-time exchange rate fetching.
Simple and user-friendly interface.

Technologies Used
HTML
CSS
JavaScript
ExchangeRate-API

File Structure
currency-converter/
├── images/
│   └── exchanging.png
├── index.html
├── style.css
├── currency-codes.js
├── api-key.js
└── script.js

File Descriptions
index.html: The main HTML file that sets up the structure of the web page.
style.css: The CSS file for styling the web page.
currency-codes.js: Contains an array of supported currency codes.
api-key.js: Contains the API key for the ExchangeRate-API.
script.js: Contains the main JavaScript logic for the currency converter.

Usage
Enter the amount:

Enter the amount you wish to convert in the input field.
Select the currencies:

Choose the currency you want to convert from in the "From" dropdown.
Choose the currency you want to convert to in the "To" dropdown.

Convert:

Click the "Convert" button to get the converted amount.
