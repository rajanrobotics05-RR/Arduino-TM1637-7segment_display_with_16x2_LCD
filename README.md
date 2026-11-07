# Arduino TM1637 7-Segment Display with 16x2 LCD

A festive Arduino UNO project integrating a **TM1637 4-Digit 7-Segment Display** and a **16×2 I2C LCD Display** to create a countdown timer followed by a scrolling Deepavali greeting.

Developed by **Rajan Robotics**.

## 🎯 Project Overview

This project demonstrates how to interface two different display modules with an Arduino UNO.

The system performs the following operations:

1. Displays a 10-second countdown on the TM1637 4-digit 7-segment display.
2. Displays the countdown status on the 16×2 I2C LCD.
3. After the countdown reaches zero, the LCD displays:
   - Rajan Robotics
   - Happy Deepavali
4. The TM1637 display scrolls the greeting message:
   - RAJAN ROBOTICS
   - WISHING HAPPY DEEPAVALI

## 🛠️ Components Required

| S.No | Component | Quantity |
|---|---|---|
| 1 | Arduino UNO | 1 |
| 2 | TM1637 4-Digit 7-Segment Display | 1 |
| 3 | 16×2 LCD Display with I2C Module | 1 |
| 4 | Jumper Wires | As required |
| 5 | USB Cable | 1 |

## 🔌 Circuit Connections

### TM1637 4-Digit Display

| TM1637 Pin | Arduino UNO Pin |
|---|---|
| CLK | D3 |
| DIO | D2 |
| VCC | 5V |
| GND | GND |

### 16×2 I2C LCD

| LCD Pin | Arduino UNO Pin |
|---|---|
| SDA | A4 |
| SCL | A5 |
| VCC | 5V |
| GND | GND |

## 📷 Connection Diagram

![Rajan Robotics Arduino TM1637 and LCD Connection Diagram](RR_TMJ1637_LCD_Connection.png)

## 💻 Software Requirements

- Arduino IDE
- Arduino UNO Board Package
- TM1637Display Library
- LiquidCrystal_I2C Library

### Library Installation

Install the following libraries using Arduino IDE Library Manager:

1. **TM1637Display** by Avishay Orpaz
2. **LiquidCrystal_I2C**

## ⚙️ Working Principle

### Stage 1: Initialization
The Arduino initializes the TM1637 display and the I2C LCD.

### Stage 2: Countdown
The TM1637 display shows a countdown from 10 to 00 seconds.

The LCD displays the countdown status.

### Stage 3: Greeting Display
After the countdown:

**16×2 LCD:**
```text
Rajan Robotics
Happy Deepavali
```

**TM1637 Display:**

Scrolls the greeting message:

```text
RAJAN ROBOTICS
WISHING HAPPY DEEPAVALI
```

Since the TM1637 has only four digits, letters are represented using approximate 7-segment patterns.

## 🚀 Uploading the Program

1. Connect Arduino UNO to your computer using a USB cable.
2. Open Arduino IDE.
3. Install the required libraries.
4. Open the Arduino source code.
5. Select **Tools → Board → Arduino UNO**.
6. Select the appropriate COM port.
7. Click Upload.

## 📚 Learning Outcomes

Through this project, students can learn:

- Arduino digital pin interfacing.
- I2C communication protocol.
- TM1637 display interfacing.
- 7-segment display character mapping.
- Countdown timer programming.
- String manipulation and scrolling text.
- Interfacing multiple display modules.

## 🏫 Developed By

**RAJAN ROBOTICS**

*Learn • Build • Innovate*

Vision to Reality

Government Recognised Company

UDYAM-TN-27-0023934

📞 Contact: 860 87 940 34

---

⭐ If you find this project useful, don't forget to star the repository!

**Happy Learning & Happy Deepavali! 🪔**
