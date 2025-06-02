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

## File Structure
- `app/src/main/java/...`: Contains Java source files including database helpers, GUI logic, and payment integration.
- `app/src/main/res/layout/`: XML files for the GUI design.
- `app/src/main/assets/`: Database files or initial data (if applicable).

## License
This project is for educational purposes only and is not licensed for commercial use.
