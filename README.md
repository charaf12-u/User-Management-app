# User Management App

A simple Flutter application demonstrating how to integrate local database storage using SQLite (`sqflite`).

## Features

- **Local Database:** Uses `sqflite` to store user data locally on the device.
- **CRUD Operations:** Implements Create, Read, Update, and Delete operations for user management.
- **Pre-populated Data:** Automatically seeds the database with sample users (John, Jane, Alice, Bob) on first launch.
- **Clean Architecture:** Separates the data model (`User.dart`), database logic (`DatabaseHelper.dart`), and UI (`main.dart`).

## Project Structure

- `lib/main.dart`: The entry point of the application and the main UI (User List).
- `lib/User.dart`: The data model representing a user.
- `lib/DatabaseHelper.dart`: A singleton class that manages the SQLite database connection and queries.

## Getting Started

To run this project locally, ensure you have Flutter installed.

1. Clone the repository:
   ```bash
   git clone https://github.com/charaf12-u/User-Management-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd User-Management-app
   ```
3. Get the dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```
