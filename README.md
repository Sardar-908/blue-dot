# 🌀 Raspberry Pi BlueDot IoT Control Interface

This project demonstrates an IoT control system using a **Raspberry Pi** and the **Blue Dot app** to interact with hardware components like sensors, buzzer, LEDs, and an I2C LCD.

## 📱 Control Interface: Blue Dot App

The system is controlled using the **D-pad** on the Blue Dot app:

| Button | Function |
|--------|----------|
| 🔼 Top | Display temperature and humidity from DHT11 on LCD |
| 🔽 Bottom | Blink all 4 LEDs in a pattern |
| ◀️ Left | Activate buzzer for 2 seconds |
| ▶️ Right | Measure and display distance from ultrasonic sensor |
| ⏺ Middle | Print "VEGA" to the console |

---

## 🧰 Components Used

- Raspberry Pi (with GPIO)
- DHT11 temperature and humidity sensor
- HC-SR04 ultrasonic distance sensor
- Buzzer
- 4x LEDs with resistors
- 16x2 I2C LCD Display (PCF8574 controller)
- Blue Dot app (installed on smartphone)
- Jumper wires and breadboard

---

## 🖥️ Software and Libraries

Install the required libraries:

```bash
pip install bluedot
sudo apt-get install python3-rpi.gpio
pip install RPLCD
pip install Adafruit_DHT
