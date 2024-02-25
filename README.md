# QR Linkify

## Introduction

The QR Linkify is a web-based application that provides functionalities for generating, displaying, and scanning QR codes. It is designed to be a simple and user-friendly tool for managing information through QR codes.

## Features

1. *QR Code Generator*: Allows users to generate QR codes by providing information such as Name, Roll No, Class, and Email.

2. *QR Code Display*: Displays QR codes based on the data provided. It's linked with the QR Code Generator for ease of use.

3. *QR Code Scanner*: Utilizes the Instascan library to scan QR codes. Scanned data is stored and can be viewed later.

4. *Scanned Data Display*: Presents the scanned data in a tabular format for easy reference.

## Technologies Used

- *HTML*: Structure for web pages.
- *CSS*: Styling for a visually appealing user interface.
- *JavaScript*: Interactivity and logic.
- *Instascan Library*: For QR code scanning functionality.
- *QRCode.js Library*: For QR code generation.

## Installation

1. Clone the repository:

   bash
   git clone <https://github.com/nahidaayisha/QR-code-generator-and-scanner.git>
   

2. Open the respective HTML files in your web browser.

## Usage

1. *QR Code Generator*:
   - Open qrGenerator.html in a web browser.
   - Enter details (Name, Roll No, Class, Email).
   - Click "Generate QR Code."

2. *QR Code Display*:
   - Open qrDisplay.html in a web browser.
   - Provide data in the URL parameters to display a QR code.

3. *QR Code Scanner*:
   - Open index.html in a web browser.
   - Use the camera to scan QR codes.
   - Click "Show Details" to view scanned data.

4. *Scanned Data Display*:
   - Open displayData.html in a web browser.
   - The table displays scanned data with corresponding Sl.No.

## Contribution

Contributions are welcome! If you find any issues or have suggestions, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
