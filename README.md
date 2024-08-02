Encryption Algorithm Application

As part of our second-year core module in Information Security, my team and I developed an encryption algorithm application using Python. The application incorporates two encryption methods: AES and a custom algorithm created by our team.
Table of Contents

    Overview
    Features
    Technologies Used
    Setup
    How to Run
    Usage
    Contributing
    License

Overview

This encryption algorithm application was developed as a part of our second-year Information Security module. The primary objective was to create a robust application that demonstrates our understanding and implementation of encryption techniques. The application includes two encryption methods: the well-known AES (Advanced Encryption Standard) and a custom encryption algorithm developed by our team.
Features

    AES Encryption and Decryption: Provides secure encryption and decryption using the AES algorithm.
    Custom Encryption Algorithm: Implements a unique encryption method developed by our team.
    User-Friendly Interface: Simple and intuitive interface for users to encrypt and decrypt text.
    Local Storage: Securely stores encrypted data locally.

Technologies Used

    Python: Core programming language used for the application.
    PyCryptodome: Python library for cryptographic operations, used for AES implementation.
    Tkinter: Python library for creating graphical user interfaces.
    SQLite: Lightweight database for storing encrypted data locally.

Setup

To set up and run this project on your local machine, follow these steps:

    Clone the Repository:

    bash

git clone https://github.com/your-username/encryption-algorithm-application.git
cd encryption-algorithm-application

Create and Activate Virtual Environment:

bash

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install Dependencies:

bash

pip install -r requirements.txt

Set Up Environment Variables:
Create a .env file in the project root directory and add any necessary environment variables.

makefile

    SECRET_KEY=your_secret_key

How to Run

    Start the Application:

    bash

    python app.py

    Access the Interface:
    The application will open a GUI window where you can use the encryption and decryption features.

Usage

    Encrypt Text:
        Open the application.
        Choose the encryption method (AES or Custom).
        Enter the text you want to encrypt.
        Click the "Encrypt" button to encrypt the text.
        The encrypted text will be displayed and stored locally.

    Decrypt Text:
        Open the application.
        Choose the decryption method (AES or Custom).
        Enter the encrypted text you want to decrypt.
        Click the "Decrypt" button to decrypt the text.
        The decrypted text will be displayed.

Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create an issue or submit a pull request.
License

This project is licensed under the MIT License - see the LICENSE file for details.
