# 🔐 Sentinel Axis – Secure Access Control System

**Sentinel Axis** is a microcontroller-based **dual authentication security system** built using **Arduino**.  
It combines **RFID card scanning** and **keypad password verification** to grant or deny access securely — ideal for restricted areas, labs, or smart doors.

---

## 🚀 Overview

This project was developed to demonstrate a **low-cost, reliable access control mechanism** that integrates both hardware and embedded software logic.  
When a valid RFID tag is detected, the system requests a password entry.  
If both credentials match, the lock is released; otherwise, an alert is triggered via buzzer.

---

## 🧩 Features

✅ Dual authentication – **RFID + Password**  
✅ **LCD Display** interface for system prompts  
✅ **Buzzer alerts** for invalid attempts  
✅ **Relay control** for electronic door lock mechanism  
✅ Modular, scalable design suitable for IoT or enterprise integration  

---

## 🛠️ Components Used

| Component | Description |
|------------|-------------|
| **Arduino Uno (ATmega328P)** | Main controller board |
| **RC522 RFID Module** | Reads RFID cards/tags |
| **4x4 Keypad** | User password input |
| **16x2 LCD Display** | Displays status messages |
| **Relay Module** | Controls door lock mechanism |
| **Buzzer** | Alerts for unauthorized access |
| **Power Supply (5V)** | System power |

---

## ⚙️ Circuit Overview

The circuit connects the **RFID module**, **LCD**, **keypad**, **relay**, and **buzzer** to the Arduino’s digital I/O pins.  
A logical sequence handles input validation and actuation of the door relay.

---

## 🧠 Workflow

1. System initializes and displays “Scan RFID Card.”
2. If a valid card is scanned → prompts for password.
3. If the entered password matches → access is granted and the relay unlocks the door.
4. If invalid → buzzer sounds and “Access Denied” is shown.

---



## 📸 Demo

You can upload your project demonstration video (the one named *WhatsApp Video 2024-06-24…*)  
Rename it to `demo.mp4` and add this snippet to show a clickable preview:

```markdown
https://github.com/Rohan699650/SentinelAxis/assets
