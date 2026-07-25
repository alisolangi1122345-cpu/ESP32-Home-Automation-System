# 🏠 ESP32 Home Automation (2-Channel Relay)

Control two electrical appliances wirelessly using an ESP32 and a 2-channel relay module. This project demonstrates how to build a simple, expandable home automation system that can be adapted for IoT applications.

---

## 📸 Project Preview

> *(Add project photos, wiring diagram, and demonstration GIF here.)*

---

## 🚀 Features

- ✅ Control 2 AC/DC appliances
- ✅ ESP32-based controller
- ✅ 2-Channel Relay Module
- ✅ Easy to expand to multiple relays
- ✅ Suitable for IoT projects
- ✅ Low-cost hardware

---

## 🛠 Hardware Used

| Component | Quantity |
|-----------|----------|
| ESP32 Dev Board | 1 |
| 2-Channel Relay Module | 1 |
| Jumper Wires | As required |
| Power Supply | 5V |
| AC/DC Load | 2 |

---

## 📂 Project Structure

```
ESP32-Home-Automation-2CH-Relay
│
├── Code/
│   └── HomeAutomation.ino
│
├── Images/
│   ├── Circuit.jpg
│   ├── Prototype.jpg
│   └── Demo.gif
│
├── Diagram/
│   └── WiringDiagram.png
│
├── LICENSE
└── README.md
```

---

## 🔌 Connections

| ESP32 Pin | Relay Pin |
|-----------|-----------|
| GPIO 26 | Relay IN1 |
| GPIO 27 | Relay IN2 |
| 5V | VCC |
| GND | GND |

> Change GPIO pins according to your code if needed.

---

## ⚙️ How It Works

1. ESP32 initializes both relay outputs.
2. Commands are received from the selected control method (Bluetooth, Wi-Fi, Blynk, or Web Server).
3. Relay 1 and Relay 2 switch connected appliances ON or OFF.
4. The design can be expanded to support additional relays and smart home features.

---

## 📋 Applications

- Home Automation
- Smart Lighting
- Fan Control
- Water Pump Switching
- Smart Socket
- Educational Projects

---

## 🔮 Future Improvements

- Wi-Fi Web Server
- Blynk IoT Integration
- Google Assistant
- Alexa Control
- Voice Commands
- Scheduling
- Energy Monitoring

---

## 📸 Demonstration

*(Add your project video or GIF here.)*

---

## 👨‍💻 Author

**Ali Nawaz**

Electrical Engineering Student

- 📧 alisolangi1122345@gmail.com
- 💼 https://www.linkedin.com/in/ali-solangi-0b106240a/

---

⭐ If you found this project useful, consider giving it a star!
