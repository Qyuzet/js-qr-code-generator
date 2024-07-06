# JS QR Code Generator

## Overview

The **JS QR Code Generator** is a web application designed to generate QR codes from user-inputted text. This project showcases the use of JavaScript, HTML, and CSS, demonstrating key concepts such as API integration, DOM manipulation, and responsive design. This tool is practical for generating QR codes for URLs, text, and other data types.
[TRY NOW!o](https://qyuzet.github.io/js-qr-code-generator/)



## Features

- **Text Input**: Users can input any text or URL.
- **QR Code Generation**: Generates a QR code based on the provided input.
- **API Integration**: Utilizes an external API to generate the QR codes.
- **Responsive Design**: Ensures functionality across various devices.

## Installation

To run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Qyuzet/js-qr-code-generator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd js-qr-code-generator
    ```
3. Open `index.html` in your preferred web browser.

## File Structure

- **index.html**: The main HTML file containing the structure of the app.
- **style.css**: The CSS file providing the styling for the app.
- **scripts.js**: The JavaScript file containing the logic and functionality of the app.

## Usage

1. Open `index.html` in a web browser.
2. Enter the text or URL you want to convert into a QR code.
3. Click the "Generate QR Code" button to display the QR code.

### Code Explanation

#### HTML (`index.html`)

The HTML file sets up the basic structure of the QR code generator, including input fields for text/URL and a button to generate the QR code.

#### CSS (`style.css`)

The CSS file ensures the app has a clean and modern look. It styles the input fields, button, and the QR code display area.

#### JavaScript (`scripts.js`)

The JavaScript file implements the core functionality of the app. Key functions and features include:

- **Event Listeners**: Handling user interactions such as entering text and clicking the button.
- **API Fetching**:
  - **generateQRCode()**: Fetches the QR code from an external API based on the user input and updates the DOM to display the QR code.

### Detailed Explanation

#### API Integration
The `generateQRCode()` function is responsible for generating the QR code using an external API. Here's how it works:

1. **Fetch Request**: Sends a GET request to the API endpoint with the user-inputted text or URL.
2. **Process Response**: Receives and processes the response to extract the QR code image.
3. **Update DOM**: Updates the HTML to display the generated QR code.

## Responsive Design

The app is designed to be fully responsive, ensuring it works seamlessly on various devices, including desktops, tablets, and mobile phones. The use of CSS Flexbox and media queries ensures that the layout adjusts appropriately to different screen sizes.

## Academic Insights

This project demonstrates key concepts in web development, including API integration, DOM manipulation, and responsive design. It serves as a practical example for computer science students to understand how front-end technologies can be integrated to create functional web applications. Through this project, students can learn:

- **HTML5**: Structuring web content.
- **CSS3**: Styling web pages.
- **JavaScript**: Adding interactivity and handling data.
- **API Integration**: Fetching and displaying data from external sources.
- **Responsive Design**: Ensuring usability across different devices.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Qyuzet/js-qr-code-generator/blob/main/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Riki Awal Syahputra at [riqyuzet@gmail.com](mailto:riqyuzet@gmail.com).

## Live Demo

You can try the app live at [JS QR Code Generator Demo](https://qyuzet.github.io/js-qr-code-generator/).

For more details and to view the code, visit the [GitHub repository](https://github.com/Qyuzet/js-qr-code-generator).
