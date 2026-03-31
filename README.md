# Secure Password Strength Analyzer & Manager

## Overview
This project is a Python-based cybersecurity tool designed to help users evaluate the strength of their passwords and generate secure, high-entropy credentials. It addresses the common issue of weak password usage by providing instant feedback and a secure generation utility.

## Features
* **Strength Analysis:** Evaluates passwords based on length, casing, digits, and special characters.
* **Secure Generation:** Generates random passwords using Python's `secrets` and `random` modules.
* **Local Vault:** Simulates a password manager by saving history to a local file.
* **CLI Interface:** Simple, menu-driven command-line interface.

## Technologies Used
* **Language:** Python 3.x
* **Modules:** `random`, `string`, `sys`

## How to Install & Run
1.  Ensure Python is installed on your system.
2.  Clone this repository or download the files.
3.  Open a terminal in the project folder.
4.  Run the application:
    ```bash
    python main.py
    ```

## Testing
* Select Option 1 and enter "12345" (Should return WEAK).
* Select Option 1 and enter "StrongP@ss1" (Should return STRONG).
* Select Option 2 to generate a new password.
