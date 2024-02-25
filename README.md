# AgendaCalendar Android App Testing
This repository contains QA automation tests for the AgendaCalendar Android app, implemented using Python and Appium. The project adopts the Page Object Model (POM) design pattern to ensure maintainability and readability. The project structure is divided into three main parts: Infrastructure, Login, and Testing, to encapsulate different aspects of the application under test.

## Project Structure
### Infrastructure : 
This directory contains the core components and utilities that support the automation framework, including driver setup, configuration management, and common utilities.

### Logic: 
This directory utilizes the POM for page elements and interactions.

### Testing: 
This directory holds the actual test cases for the application. It is further organized into subdirectories, each representing a different feature or aspect of the application to be tested.

## Getting Started
### Prerequisites
Python 3.6 or higher
Appium server running on your local machine or a remote server
Android SDK installed and properly configured
An Android emulator or real device set up for testing

## Installation
Clone the repository to your local machine:
git clone https://github.com/HosamHegly/agendaCalendarTesting.git

Navigate to the project directory:
cd agendaCalendarTesting

## Running Tests
Navigate to the Test directory and run this command
python -m unitest test.py

## Contributing
Contributions are welcome! If you have improvements or bug fixes, please follow the standard GitHub flow:

1.Fork the repository

2.Create your feature branch (git checkout -b feature/AmazingFeature)

3.Commit your changes (git commit -am 'Add some AmazingFeature')

4.Push to the branch (git push origin feature/AmazingFeature)

5.Open a Pull Request
