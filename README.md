# Library Management System

**Authors:** Damien Lebas, Cristian Carp, Oscar Stemmelin

## Overview
This project consists of a Python-based library management system.
It was developed as part of an academic group project and aims to manage a library database through a simple command-line interface.

The project includes a `code` directory containing all Python source files, as well as a JSON file that serves as the database. Additional files include the project requirements, the original assignment instructions, and this README.

## Project Structure
The repository is organized as follows:

### Code Directory
The `code` folder contains:
- `main.py`: Main program executed by the user
- `librairie.py`: Contains the `Library` class and its associated methods
- `modeles.py`: Defines the `Book` and `User` data classes
- `tests.py`: Contains unit tests for functions and methods
- `data.json`: JSON file acting as the database, storing books and users

### Other Files
- `requirements.txt`: Lists the required Python dependencies
- `consignes.md`: Copy of the original project instructions
- `README.md`: Project documentation

## Features
This application allows users to:
- Display the list of available books
- Add or remove books and users
- Search for a book
- Borrow a book
- Return a book
- Display descriptive statistics of the database
