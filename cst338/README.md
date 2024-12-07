# OptiNet - Network Diagnostic & Monitoring Tools
=============================================

A comprehensive network monitoring and diagnostic suite providing real-time network analysis, connection testing, port scanning, and device discovery tools.

## Features
-----------
- Real-time bandwidth monitoring
- Network interface monitoring
- Connection analyzer (Ping, Traceroute, DNS Lookup)
- Port scanner with service detection  
- HTTP status checker
- Network device scanner
- Active connection status
- Data transfer statistics

## Requirements
-----------
- Python 3.x (Download from https://www.python.org/downloads/)
- Internet connection for initial setup
- Administrator/sudo privileges for network operations

## Required Python Packages
----------------------
Run these commands in terminal/command prompt:
```bash
pip install flask
pip install flask-socketio
pip install psutil
pip install dnspython
pip install scapy
pip install requests
```

## Directory Structure
-----------------
```
OptiNet/
├── app.py
├── ports.txt
├── static/
│   ├── monitor.js
│   ├── analyzer.js
│   ├── scanner.js
│   ├── http-checker.js
│   └── styles.css
└── templates/
    ├── index.html
    ├── analyzer.html
    ├── scanner.html
    ├── http-checker.html
    └── about.html
```

## How to Run
---------
1. Open terminal/command prompt
2. Navigate to OptiNet folder:
   ```bash
   cd path_to_OptiNet_folder
   ```
3. Run with administrator/sudo privileges:
   ```bash
   python app.py
   ```
4. Access in web browser:
   ```
   http://localhost:5000
   ```

## Troubleshooting
--------------
1. Port 5000 in use:
   - Change port in app.py
   - Try port 8080 or 3000
   - Update browser URL accordingly

2. Python not recognized:
   - Verify Python installation
   - Add Python to system PATH
   - Try 'python3' command

3. Package installation fails:
   - Use administrator/sudo privileges
   - Update pip: python -m pip install --upgrade pip
   - Check internet connection

4. Network scanning fails:
   - Run with administrator privileges
   - Check firewall settings
   - Verify network permissions

## Project Team
--------------
Prepared by:
- Arif Arman Bin Mazlan (160466)
- Muhammad Irfan Danish Bin Noor Azlin (16369)
- Muhammad Nurillanwar Bin Mohammadin (160349)
- Muhammad Aqif Bin Ali Yasak (164320)
- Idham Fitri Bin Mohd Rodzi (160474)

Provided for:
ASSOC. PROF. DR. AMAN JANTAN
CST338 LECTURER
```
