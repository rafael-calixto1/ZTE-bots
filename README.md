# Selenium Automation Project

This project contains Selenium-based automation scripts for web interactions.

## Prerequisites

- Python 3.x
- Chrome/Firefox browser (depending on your setup)
- WebDriver for your browser
- Git (for version control)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <project-directory>
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
- `.gitignore`: Git ignore rules for the project
- `.env`: Environment variables (not tracked in git)

## Version Control

The project uses Git for version control. The `.gitignore` file is configured to exclude:
- Python cache and compiled files
- Virtual environment directories
- Environment files (`.env`)
- IDE-specific files
- Selenium driver logs
- Testing and coverage files

Make sure to never commit sensitive information or environment files to the repository.

## Usage

[Add specific usage instructions for your scripts here]

## Dependencies

The project uses the following main dependencies:
- Selenium 4.32.0
- WebSocket Client
- Various supporting libraries (see requirements.txt for full list)

## Contributing

[Add contribution guidelines if applicable]

## License

[Add license information] 