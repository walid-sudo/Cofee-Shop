# Coffee Display Web Application

This is a simple web application that displays a list of coffee items retrieved from an external API and allows users to navigate through the coffee items.
Features

    Fetches coffee data from an external API.
    Displays coffee information (name, image, description) on the web page.
    Allows users to navigate through coffee items using a "Next" button.

# Usage

To use this web application, follow these steps:

    Open the index.html file in your web browser.

    The application will fetch coffee data from an external API and display the information of the first coffee item.

    To view the next coffee item, click the "Next" button.

# Code Overview

    The code uses the fetch API to retrieve coffee data from the external API.

    It listens for the "DOMContentLoaded" event to ensure the HTML is fully loaded before executing JavaScript.

    The coffee data is fetched from the external API and displayed in the coffee-container on the web page.

    The "Next" button allows users to cycle through the coffee items in a circular manner.

    Error handling is in place to handle issues related to data retrieval and formatting.

# Dependencies

    This web application does not have any external dependencies, as it uses plain JavaScript to fetch and display data.

# API Endpoint

The coffee data is fetched from the following API endpoint:

    https://cofee.onrender.com/coffees

# Compatibility

This web application should work in modern web browsers that support JavaScript.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Author

Walid Mohamed

Feel free to customize and expand upon this README as needed for your project.

# Live Server

https://walid-sudo.github.io/Cofee-Shop/