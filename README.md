# **Red-Grid (Malware Simulation Lab)**

## Overview

**Red-Grid** is a comprehensive Malware Simulation Lab built to help users understand the core functionalities of various types of malware. This project offers a set of user-defined tools that simulate different types of cyber threats for educational and research purposes. 

**Note**: This project is intended for **ethical hacking** and **cybersecurity** professionals only. Misuse of this tool may lead to legal consequences. Always use responsibly and in a controlled environment.

## Features

Red-Grid includes the following malware types:

- **Keylogger**: Records keystrokes discreetly.
- **Ransomware**: Encrypts files and simulates a ransom demand.
- **Worm**: Replicates across directories simulating propagation.
- **Stealer**: Extracts dummy credential files and data.
- **Trojan**: Hides malicious functions within legitimate-looking code.
- **Rootkit**: Simulates concealment of processes/files.
- **Backdoor**: Creates persistent remote shell access.
- **Adware**: Opens browser windows to simulate ad spam.
- **File Infector**: Infects Python scripts with harmless payloads.
- **Bash Persistence Script**: Adds a simulated script to startup for persistence.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/R3L1C5/Red-Grid.git
    cd Red-Grid
    ```

2. Install necessary Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the **Red-Grid** lab, execute the following command in your terminal:
```bash
python3 malware_simulation_lab.py
 ```
Once the script runs, a command-line interface (CLI) will appear, presenting you with different malware simulation options. You can select the desired malware by typing the corresponding number and pressing Enter.
```bash
          _____                         _____                           
      __|__   |__  ______  _____    __|___  |__  _____   ____  _____   
     |     |     ||   ___||     \  |   ___|    ||     | |    ||     \  
     |     \     ||   ___||      \ |   |  |    ||     \ |    ||      \ 
     |__|\__\  __||______||______/ |______|  __||__|\__\|____||______/ 
        |_____|                       |_____|                           
                                      
1. Keylogger  
2. Ransomware  
3. Worm  
4. Stealer  
5. Trojan  
6. Rootkit  
7. Backdoor  
8. Adware  
9. File Infector  
10. Bash Persistence Script  
0. Exit
 ```
Select an option to simulate malware behavior.

## License
Distributed under the MIT License. See LICENSE for more information.

## Disclaimer
This project is designed for educational and research purposes only. Do not use this project for any illegal activities. By using this tool, you agree to accept full responsibility for any consequences arising from its use.

Author: R3L1C5
