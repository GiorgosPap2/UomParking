# UomParking Project

## Overview
This repository contains the source code for the "UomParking" project, an academic assignment developed as part of a course at the University of Macedonia (UoM). The project implements a parking session management system with a graphical user interface (GUI), SQLite database integration, and payment processing capabilities using PayPal. The system allows users to manage parking sessions, calculate durations, and process payments based on the assignment requirements.

## Features
- **Parking Session Management**: Record and retrieve parking session details including start/end times and locations.
- **Database Integration**: Use of SQLite to store parking history with columns for session ID, user ID, license plate, location, duration, start time, end time, and cost.
- **GUI Interface**: A user-friendly interface for interacting with parking data and initiating payments.
- **Payment Processing**: Integration with PayPal for processing parking fees.
- **Data Visualization**: Display of parking statistics, such as average session duration and location-based session counts, using bar charts.

## Assignment Context
This project fulfills the requirements outlined in the attached assignment document (in Greek). Key tasks include:
- Developing a GUI for parking session management.
- Implementing database operations to store and query parking data.
- Calculating average parking durations and visualizing data.
- Integrating PayPal for payment transactions with specific response handling (e.g., R1-R7 responses as per the assignment).

## Installation and Setup

### Prerequisites
- Java Development Kit (JDK) 8 or higher.
- Android Studio (for Android app development).
- SQLite database support.
- Internet connection for PayPal API integration.

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/VlachavasI/UomParking.git
   ```
2. Open the project in Android Studio.
3. Configure the SQLite database by ensuring the `DatabaseHelper` class points to the correct table (`TABLE_PARKING_HISTORY`) and column names.
4. Set up PayPal SDK credentials:
   - Obtain a PayPal client ID and secret from the PayPal Developer Dashboard.
   - Update the PayPal configuration in the project (e.g., in strings.xml or a config file).
5. Build and run the app on an emulator or physical device.

## Usage
- **Launch the App**: Start the app to access the main GUI.
- **Manage Parking Sessions**: Add new sessions or view existing ones via the interface.
- **View Statistics**: Check the average parking duration or location-based session counts on the chart view.
- **Process Payment**: Initiate a PayPal payment for a selected parking session, handling responses (R1-R7) as defined in the assignment.
- **Exit**: Close the app or follow R7 to log out and end the session.

## File Structure
- `app/src/main/java/...`: Contains Java source files including database helpers, GUI logic, and payment integration.
- `app/src/main/res/layout/`: XML files for the GUI design.
- `app/src/main/assets/`: Database files or initial data (if applicable).

## Contributing
This is an academic project and not open for external contributions. Modifications should be made by the author (VlachavasI) as part of the assignment requirements.

## License
This project is for educational purposes only and is not licensed for commercial use.

## Acknowledgments
- University of Macedonia for providing the assignment framework.
- PayPal for the payment gateway SDK.
- Android Open Source Project for the development platform.

## Contact
For questions related to this project, contact the author via the GitHub profile: [VlachavasI](https://github.com/VlachavasI).