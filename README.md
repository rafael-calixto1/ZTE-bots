# Selenium Automation Project

This project contains Selenium-based automation scripts for web interactions.

## Prerequisites

- Python 3.x
- Chrome/Firefox browser
- WebDriver for your browser
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/rafael-calixto1/zte-bots
cd zte-bots
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv selenium-env
source selenium-env/bin/activate  # On Linux/Mac
# or
.\selenium-env\Scripts\activate  # On Windows
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Environment Setup

1. Create a `.env` file in the project root directory
2. Add the following variables to your `.env` file:
```
SELENIUM_DRIVER_PATH=/path/to/your/driver
SELENIUM_HEADLESS=false
DEBUG=false
LOG_LEVEL=INFO
```

## Project Structure

- `670V9_config.python`: Configuration settings for the automation
- `670V9_reset.python`: Reset functionality implementation
- `requirements.txt`: Python package dependencies
- `selenium-env/`: Virtual environment directory
- `.env`: Environment variables (not tracked in git)

