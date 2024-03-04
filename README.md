
# Regex Matching Web App

Welcome to the Regex Matching Web App repository! This project aims to replicate the core functionality of popular regex tools like regex101.com, providing users with a simple yet powerful web application to perform regex matching on test strings.

## Project Overview

The Regex Matching Web App allows users to input a test string and a regular expression (regex) pattern and instantly see all the matches found. Built using Flask, a lightweight Python web framework, this application offers a seamless and intuitive user experience.

## Features

- **Regex Matching**: Users can input any test string and a regex pattern, and the application will display all matches found within the string.
- **User-friendly Interface**: The web interface is designed to be user-friendly, with clear input fields and immediate feedback on matched strings.
- **Bonus Feature - Email Validation**: In addition to regex matching, the app includes a bonus feature to validate email IDs, enhancing its utility and versatility.
- **Scalable Deployment**: The application is designed to be easily deployable on AWS Cloud, ensuring scalability and accessibility for a wide range of users.

## Project Structure

- **app.py**: The main Python file containing the Flask application setup and route definitions.
- **templates/index.html**: The HTML template for the user interface, including the form for inputting test strings and regex patterns.
- **requirements.txt**: A list of Python dependencies required to run the application.
- **README.md**: This file, providing an overview of the project and instructions for usage.

## Getting Started

To run the Regex Matching Web App locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python dependencies using `pip install -r requirements.txt`.
3. Run the Flask application by executing `python app.py` in your terminal.
4. Open a web browser and navigate to http://localhost:5000 to access the application.
5. Input test strings and regex patterns to see the matching results in real-time.


## Contributions

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve the Regex Matching Web App.

