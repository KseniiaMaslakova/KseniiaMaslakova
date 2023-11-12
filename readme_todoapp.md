# Task Management App by Kseniia

This document provides instructions for setting up and running the Task Management application on macOS and Windows, along with instructions for running tests.

For a visual overview of the application's features and functionality, check out the demo video [here](https://drive.google.com/drive/folders/1Kco6ItOJxMe837tcEymARCYo6LjhqloA?usp=sharing).

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3
- pip (Python package manager)

## Setup Instructions

1. **Clone the Repository**  
   Clone the repository to your local machine.

2. **Install Dependencies**  
   Navigate to the root directory of the project and run the following command to install the required Python packages:

   ```
   pip install -r requirements.txt
   ```
## Running the Application

### On macOS

1. **Open Terminal**  
   Open the Terminal application.

2. **Navigate to Project Directory**  
   Use the `cd` command to navigate to the root directory of the project.

3. **Start the Application**  
   Run the following command:
   ```
   python3 app.py
   ```
### On Windows

1. **Open Command Prompt**  
   Open the Command Prompt application.

2. **Navigate to Project Directory**  
   Use the `cd` command to navigate to the root directory of the project.

3. **Start the Application**  
   Run the following command:
   ```
   python app.py
   ```
## Running Tests

To run the unit tests for the application, follow these steps:

1. **Navigate to the Project Directory**  
   Ensure you are in the root directory of the project.

2. **Run the Test Script**  
   Execute the following command:
   ```
   python test.py
   ```

## Folder Structure

The project has the following folder structure:
   ```
.
├── app.py               # Main application file
├── instance
│   └── tasks.sqlite3    # SQLite database file
├── requirements.txt     # Python dependencies
├── templates            # HTML templates for the app
│   ├── kanban.html
│   ├── login.html
│   └── register.html
└── test.py              # Test script for the application
   ```


### Notes:

- Ensure that Python and pip are correctly installed and accessible from the command line.
- The application is assumed to run on localhost. Check `app.py` for specific configurations.
- Modify the paths and commands as necessary based on your local setup and environment variables.
