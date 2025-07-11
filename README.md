# CBE Transaction Checker

A simple, modern web app to help users quickly look up Commercial Bank of Ethiopia (CBE) transactions by Transaction ID and the last 8 digits of their account number.

## Overview
This app allows users to:
- Enter a CBE Transaction ID and the last 8 digits of their account number
- Validate the input for correct format
- Open the official CBE transaction lookup page in a new browser tab with the combined ID
- Enjoy a clean, responsive, and branded user interface

## Features
- **Modern UI**: Card-style layout, CBE logo, and responsive design
- **Input Validation**: Ensures Transaction ID is entered and account digits are exactly 8 numbers
- **Inline Error Messages**: User-friendly error display below each input
- **Loading Indicator**: Shows a spinner while opening the transaction page
- **Favicon**: CBE logo appears in the browser tab

## How to Use
1. Open `index.html` in your web browser.
2. Enter your CBE Transaction ID (e.g., `FT123456`).
3. Enter the last 8 digits of your account number (e.g., `23456789`).
4. Click **Open Transaction**.
5. If the inputs are valid, a new tab will open with your transaction details on the official CBE site.

## Setup
1. Download or clone this repository.
2. Make sure `index.html` and `cbe_logo.png` are in the same directory.
3. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, etc.).

> **Note:**
> - The app works entirely client-side (no backend required).
> - If the logo or favicon does not appear, ensure `cbe_logo.png` is present in the same folder as `index.html`.

## License
This project is provided for educational and demonstration purposes. The CBE logo is the property of Commercial Bank of Ethiopia and is used here for non-commercial, illustrative purposes only.
