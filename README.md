# 🔒 Password Manager

A simple Password Manager built using Python and Tkinter. This application allows you to generate strong passwords, save them securely, and copy them to your clipboard for easy access.

## 📌 Features

- **Generate Secure Passwords** – Randomly generates strong passwords with letters, numbers, and symbols.
- **Save Credentials** – Stores website, email, and password details in a text file.
- **Clipboard Support** – Automatically copies the generated password to your clipboard.
- **User-Friendly GUI** – Built with Tkinter for easy navigation.

## 🚀 Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/password-manager.git
   cd password-manager
   ```
2. **Install Dependencies**
   Ensure you have Python installed, then install the required library:
   ```bash
   pip install pyperclip
   ```
3. **Run the Application**
   ```bash
   python main.py
   ```

## 📂 File Structure

```
password-manager/
│── main.py          # Main application script
│── logo.png         # App logo (required for UI)
│── data.txt         # Stores saved credentials
│── README.md        # Project documentation
```

## 🛠️ Technologies Used

- **Python** – Core language
- **Tkinter** – GUI framework
- **Pyperclip** – For copying passwords to clipboard

## ⚠️ Disclaimer

This program stores passwords in plain text (`data.txt`). For enhanced security, consider encrypting stored passwords using a library like `cryptography` or using a password manager.
---
Feel free to contribute and enhance this project! 🚀
