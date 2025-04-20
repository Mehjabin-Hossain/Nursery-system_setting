# Selenium Testing Project

This project contains automated test scripts using Selenium WebDriver for testing web application functionalities.

## Project Overview

The project includes automated tests for various settings and configurations in a web application, with a focus on bank settings and invoice print settings.

## Prerequisites

- Python 3.x
- Chrome WebDriver
- Selenium WebDriver
- PyAutoGUI

## Installation

1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install selenium pyautogui
   ```
3. Ensure Chrome WebDriver is installed and in your system PATH

## Project Structure

- `bank_settings.py`: Test script for bank settings and invoice print settings functionality
- `login_logout_utilities.py`: Utility functions for login and logout operations

## Test Features

### Bank Settings Test

The test script (`bank_settings.py`) automates the following scenarios:

1. Login to the application
2. Navigate to Settings > Company Settings > Bank Settings
3. Configure bank details:
   - Bank name
   - Account number
   - Company identification number
4. Upload and configure invoice print settings

## Test Execution

To run the tests:

```bash
python bank_settings.py
```

Test results will be saved in 'Bank Settings Output.txt'

## Output

The test execution generates a detailed output file containing:
- Tester's name
- Test date
- Test steps results (Pass/Fail)
- Error messages (if any)

## Configuration

Update the following variables in the test scripts as needed:

- `credentials`: List of test user credentials
- `SCRIPTS_PATH`: Path to the test scripts folder
- File paths for uploads (e.g., invoice logo)

## Notes

- Ensure proper internet connectivity before running tests
- The tests include appropriate wait times for element loading
- Screenshots are captured for failed scenarios
- Tests handle various error scenarios with proper logging