# Facial Attendance System using Python and MySQL

## Overview

This project is a Facial Attendance System that uses Python for the backend and MySQL for the database management. The system captures the facial images of individuals and marks their attendance based on facial recognition. 

## Features

- **Facial Recognition**: Uses OpenCV for capturing and recognizing faces.
- **Database Management**: MySQL is used to store and manage attendance records.
- **User Interface**: A simple GUI for interacting with the system.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- MySQL
- MySQL Connector for Python

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SatwikDonthamsetty/Facial-attendance-system-using-Python-and-MySQL.git
   cd Facial-attendance-system-using-Python-and-MySQL
   ```

2. **Install the required Python packages**:
   ```bash
   pip install opencv-python numpy mysql-connector-python
   ```

3. **Set up the MySQL database**:
   - Create a database named `attendance_system`.
   - Create the necessary tables using the provided SQL script (`database_setup.sql`).

## Usage

1. **Run the application**:
   ```bash
   python main.py
   ```

2. **Mark Attendance**:
   - The system will capture the facial image and mark the attendance if the face is recognized.

3. **Check Attendance Records**:
   - Attendance records can be viewed and managed within the MySQL database.

## Project Structure

- `main.py`: The main script to run the application.
- `database_setup.sql`: SQL script to set up the MySQL database and tables.
- `facial_recognition/`: Directory containing facial recognition related scripts.
- `gui/`: Directory containing GUI related scripts.
- `attendance_logs/`: Directory to store attendance logs.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- OpenCV
- MySQL
