# 🧳 Smart Cloak Room System (IoT + RFID + Web Interface)

An **IoT-based Smart Cloak Room System** designed to automate luggage storage and retrieval using **RFID authentication, PIN verification, and real-time web interface**.

---

## 📌 Project Overview

This project aims to modernize traditional cloak room systems (like those in railway stations, malls, and airports) by integrating **IoT, automation, and security**.

Users can:

* Deposit items securely
* Retrieve items using RFID + PIN
* Get allocated storage slots automatically

---

## ⚙️ Tech Stack

### 🔌 Hardware

* Arduino (Uno/Nano)
* RFID Module (RC522)
* Servo Motors / Lock Mechanism
* LCD Display (optional)
* Keypad (for PIN input)

### 💻 Software

* Arduino IDE (Embedded C)
* Serial Communication
* Web Interface (HTML/CSS/JS)
* Backend (optional: Python / Node.js)

---

## 🏗️ System Architecture

1. User scans RFID card
2. System verifies identity
3. User selects:

   * Deposit OR Withdraw
4. PIN verification is performed
5. System:

   * Allocates storage slot (deposit)
   * Opens correct slot (withdraw)
6. Data is synced to web interface

---

## 🔄 Workflow

### 📥 Deposit Flow

* RFID Scan → Authentication
* Enter PIN
* Assign empty slot
* Store item
* Slot locked automatically

### 📤 Withdraw Flow

* RFID Scan
* Enter PIN
* Retrieve assigned slot
* Unlock compartment

---

## 🔐 Features

* RFID-based user authentication
* Dual security (RFID + PIN)
* Automatic slot allocation
* Real-time tracking via web interface
* Secure and efficient storage system

---

## 🌐 Smart City Relevance

This system contributes to **Smart City development** by:

* Reducing manual labor in public storage systems
* Enhancing security with digital authentication
* Improving user convenience in public transport hubs
* Enabling scalable, automated infrastructure

Use cases:

* Railway stations
* Airports
* Shopping malls
* Bus terminals

---

## 🚀 How to Run

### 🔌 Hardware Setup

* Connect RFID module to Arduino
* Connect servo/lock system
* Upload Arduino code

### 💻 Software Setup

```bash
# Run backend (if applicable)
python app.py
```

* Open web interface in browser
* Ensure serial communication is active

---

## 📊 Future Enhancements

* Mobile app integration
* QR code-based access
* Cloud database (Firebase/AWS)
* Payment integration for paid storage
* AI-based demand prediction

---

## 👨‍💻 Author

SURYAM SREESHANTH RAO

---

## ⭐ Support

If you like this project, give it a star ⭐
