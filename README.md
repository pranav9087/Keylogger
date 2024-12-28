# Python Keylogger

This project is a Python-based keylogger designed to record all keystrokes made by a user on a Windows machine. It captures keyboard inputs and stores them in a log file for monitoring and analysis purposes.

## Features

- **Keystroke Logging** – Records all keyboard inputs, including special keys.
- **Stealth Mode** – Runs in the background without displaying a console window.
- **Log File Storage** – Saves captured keystrokes to a specified log file.

## Disclaimer

**This project is intended for educational purposes and authorized testing only.** Unauthorized use of this tool to monitor individuals without explicit permission is illegal and unethical. The author is not responsible for any misuse or damage caused by this project.

## Prerequisites

- **Python 3.x** – Ensure Python is installed on the target Windows machine.
- **Required Libraries** – Install necessary Python libraries using pip:
  ```bash
  pip install -r requirements.txt
  ```

## Setup and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/pranav9087/Keylogger.git
cd Keylogger
```

### 2. Configure the Keylogger
- Modify the `keylogger.py` script to specify the desired log file path and any other configurations as needed.

### 3. Run the Keylogger
- Execute the `keylogger.py` script on the target machine:
  ```bash
  python keylogger.py
  ```
- To run the keylogger in stealth mode without a console window, you can compile it into an executable using PyInstaller:
  ```bash
  pyinstaller --onefile --noconsole keylogger.py
  ```
- After compilation, run the generated executable on the target machine.

### 4. Access the Logs
- The keylogger will save the captured keystrokes to the specified log file. Open this file to review the recorded inputs.

## Security Considerations

- **Antivirus Detection** – Be aware that antivirus software may detect and block the keylogger. Use this tool only on systems where you have explicit permission and consider obfuscation techniques if necessary.
- **Ethical Use** – Ensure that you have authorization to monitor the system where this keylogger is deployed. Unauthorized monitoring is illegal and unethical.

## Contributing

Contributions to enhance the functionality or security of this project are welcome. Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request for review.

