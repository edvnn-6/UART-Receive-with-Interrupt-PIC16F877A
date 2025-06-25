# UART Receive with Interrupt – PIC16F877A

This project demonstrates how to implement **UART reception** with **interrupts** using the **PIC16F877A** microcontroller. Received characters are displayed on **PORTB**.

## 👨‍💻 Author
**Edvin Jose Vakaparamban**  
📅 Created on: [Your Date]

---

## 🔧 Project Overview

- Configures the **UART module** at **9600 bps**.
- Enables **interrupt-based reception** (RCIF).
- Incoming UART data is displayed on **PORTB** (useful for LEDs or debugging).
- Efficient for real-time, non-blocking communication.

---

## 🧰 Hardware Requirements

- **PIC16F877A** Microcontroller
- USB-to-Serial Converter (e.g., FTDI, CH340)
- LEDs on PORTB (optional, for visual feedback)
- Breadboard, wires, 16 MHz crystal oscillator

---

## ⚙️ Key Configurations

| Feature           | Value     |
|------------------|-----------|
| Baud Rate        | 9600 bps  |
| UART Mode        | Async RX  |
| RX Pin           | RC7       |
| Output Port      | PORTB     |
| Clock            | 16 MHz    |

---

