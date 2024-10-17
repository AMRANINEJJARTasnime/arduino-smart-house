# 🏠 Smart House: Miniature Home Automation Model

![Arduino](https://img.shields.io/badge/Arduino-Controller-green) ![RFID](https://img.shields.io/badge/RFID-Technology-blue)



---

## Project Demo

https://github.com/user-attachments/assets/734fe3ae-6879-407f-bbc1-04be3175fd34

---

## Project Overview

My team and I developed an **innovative miniature smart home** using Arduino controllers, integrating smart technologies to optimize security, convenience, and energy efficiency. The system allows users to remotely control household appliances via a Bluetooth-connected app and RFID modules. We incorporated various sensors, microcontrollers, and actuators to automate and monitor key aspects of the home, including lighting, security, and environmental conditions.

---

## 🚀 Features

1. **Smart Entry System**: Controlled via **RFID** tag or security code for secure access to doors, including the garage.
2. **Environmental Display**: Displays time, date, humidity, and indoor temperature.
3. **Automatic Fan Activation**: Activates when the indoor temperature exceeds a set threshold.
4. **Bathroom Automation**: Lights and fan activate upon entry, with a "sad" face displayed when occupied, and a "happy" face when vacant.
5. **Remote-Controlled Lights**: Control room lights via mobile phone, including color-changing options.
6. **Gas and Smoke Detection**: Buzzer and fan activate when gas or smoke is detected.
7. **Garden Pool Lighting**: Automatically lights up at night to enhance ambiance and safety.

---

## 🛠️ Components
- **Microcontrollers**: Arduino Uno and Mega for handling all inputs and outputs.
- **Sensors**: 
  - DHT11 for temperature and humidity.
  - PIR HC-SR501 for motion detection.
  - MQ-135 for gas detection.
  - LDR for light level detection.
  - 1838 IR Receiver for remote control functions.
- **Actuators**: 
  - Servo motors for door control.
  - Stepper motor for automated curtains.
  - LED matrix 8x8 for visual alerts.
  - Buzzer for audio alerts.
- **Communication Modules**: 
  - HC-05 Bluetooth module for remote control via smartphone.
  - RFID RC522 for secure access.
  

---

## Libraries
- **DHT Sensor Library**: For reading temperature and humidity data.
- **IRremote Library**: For decoding infrared signals.
- **Stepper Library**: For controlling the stepper motor.
- **LiquidCrystal Library**: For interfacing with the LCD display.
- **MFRC522 Library**: For handling RFID communication.
- **SoftwareSerial Library**: For serial communication with the Bluetooth module


---

## Smart Home Project Photos

<p align="center">
  <img src="https://github.com/user-attachments/assets/59ef742a-0427-4685-ac0d-b40a7ac346ce" alt="smartHouse1" width="250"/>
  <img src="https://github.com/user-attachments/assets/7bf9e07d-0bbd-44fc-88d4-6a6a0eb90a39" alt="2" width="315"/>
  <img src="https://github.com/user-attachments/assets/963c240d-3a2d-4fc5-8552-0b27011a94ab" alt="5" width="600"/>

</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/60ef6920-a06e-484c-96db-64e57e134b75" alt="4" width="265"/>
  <img src="https://github.com/user-attachments/assets/e753af76-fbb3-4c16-a058-cf3bc44a7842" alt="3" width="200"/>
  <img src="https://github.com/user-attachments/assets/e39d46ea-89e6-44a2-bcc5-91374e13cce2" alt="6" width="250"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/eb148cdf-2d93-402b-8c75-8dec2b1fa968" alt="7" width="300"/>
  <img src="https://github.com/user-attachments/assets/4b79c4e1-6481-4e9b-bb61-1cf44a1ffc3c" alt="9" width="450"/>
  <img src="https://github.com/user-attachments/assets/753c4fe2-91d0-44ca-9bc2-d1fb2711a71e" alt="8" width="800"/>
</p>



## Contributors
- AIT EL CADI Shadia
- SAHEL Bouchra
- EL MIDAOUI Imane
- ABOUJENANE Mariam
- M'HIFED Zineb
- AMRANI NEJJAR Tasnime

