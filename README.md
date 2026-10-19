![background Image](images/toolkit.jpeg)
# 🔐 Secure Toolkit — Python Security Application

A `Python` desktop application built with `Tkinter` that provides tools for 
**password management**, **file encryption**, **secure notes**, and **key/token generation**.

The application focuses on practical implementations such as 
**local data storage**, `encryption workflows`, and **user-friendly desktop interfaces**. 
Each module is designed to be **modular**, **readable**, and **easy to extend**.

This project is intended as a **portfolio-grade** example showcasing 

`Python application development`, **clean code organization**, and 
**desktop GUI design** using `Tkinter`.


---
## 📌 Overview

**Secure Toolkit** is a multi-module Python application that allows users to:

- Encrypt and decrypt sensitive data
- Securely store credentials and notes
- Protect files using strong symmetric encryption
- Generate cryptographically secure keys and passwords

The project emphasizes **clarity, security awareness, and real-world usability**.

---

## 🎥 Demo / Screenshots


<details> <!-- 1st -->

<summary>Password Tool Image</summary>

Main dashboard of the password management tool:

![Password Tool Screenshot](images/Password-Tool.png)

</details>


<details> <!-- 2nd -->

<summary>Password Manager Image</summary>

The main dashboard for securely storing, viewing, and managing encrypted passwords:
![Password Manager Screenshot](images/Password-Manager.png)
</details>


<details> <!-- 3rd -->

<summary>File Encryption Image</summary>

Interface for encrypting and decrypting files using strong cryptographic keys:

![File Encryption Screenshot](images/File-Encryption.png)

</details>


<details> <!-- 4th -->

<summary>Secure Notes Image</summary>

Secure notes section for storing sensitive information with encryption protection:

![Secure Notes Screenshot](images/Secure-Notes.png)

</details>


<details> <!-- 5th -->

<summary>Key/Token Generator Image</summary>

Built-in generator for creating strong passwords, cryptographic keys, and secure tokens:

![Key/Token Generator Screenshot](images/Key-Token-Generator.png)

</details>

---

## ✨ Key Features

### 🔑 Password Encryption Tool
- Reversible password encryption using **Fernet (AES)**
- Password decryption with key-based security
- Password strength analysis
- Secure random password generation
- Clipboard copy support
- Show / hide password toggle

---

### 🗂️ Encrypted Password Manager
- Secure storage of website credentials
- All data encrypted before being written to disk
- Search functionality for stored credentials
- Decryption performed only inside the application
- Clipboard support for selected entries

---

### 📁 File Encryption & Decryption
- Encrypt and decrypt files using AES encryption
- Supports multiple file selection
- Automatic backup creation during decryption
- Prevents accidental data loss

---

### 📝 Secure Notes
- Encrypted personal notes storage
- Notes remain encrypted on disk at all times
- Decryption occurs only on demand

---

### 🔐 Key / Token Generator
- Generates cryptographically secure random keys
- Customizable key length
- Suitable for tokens, API keys, or secrets

---

## 🗂️ Project Structure


## 🛠️ Installation

### 1️⃣ Clone the Repository
```bash
  git clone https://github.com/DevGopi-17/Multi-Functional-Security-Toolkit.git
  cd Multi-Functional-Security-Toolkit
```

```result
```

## Create & Activate Virtual Environment (Recommended)
```bash
python3 -m venv venv
# macOS / Linux
source venv/bin/activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# Windows (CMD)
venv\Scripts\activate.bat
```

## Run the Application

```bash
python secure_toolkit.py
```
---

## 🤝 Contributing
Feel free to submit issues or pull requests. Future enhancements may include:
- Multi-user support
- Cloud synchronization
- Additional encryption algorithms
- Improved UI/UX
- Automated testing & CI/CD
- Plugin system

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with attribution.

See the [LICENSE](LICENSE) file for details.

