# 🚀 CAN Driver for STM32F466RETx  

This project implements a **CAN (Controller Area Network) driver** for the **STM32F466RETx** microcontroller using a **Nucleo board** and an **MCP2551 CAN transceiver**. The goal is to develop a reliable and flexible CAN communication layer that supports various configurations and operational modes.

---

## 🎯 Project Overview  
The project aims to create a robust CAN driver that can handle transmission, reception, and interrupts effectively. The driver will be designed for scalability, making it easy to configure different baud rates and handle errors gracefully.  

### ✅ Current Status  
✔️ Configured for **loopback mode** for initial testing  
✔️ Basic transmission and reception implemented  
✔️ GPIO and CAN peripheral initialization included  
![image](https://github.com/user-attachments/assets/9b1587cb-f60c-4fc7-8d02-00646fe73a48)

### 🚧 Upcoming Features  
- State machine for managing transmission and reception  
- Configurable baud rates  
- Enhanced robustness (e.g., error handling and recovery)  
- Move RX message handling to the interrupt  
- Enable TX interrupt for better performance  

---

## 🛠️ Hardware Setup  
### **Required Components**  
- **Nucleo-F466RE** – STM32F466RETx-based development board  
- **MCP2551** – CAN transceiver  

### **Wiring**  
| Nucleo Pin | MCP2551 Pin | Description |
|------------|-------------|-------------|
| PB8 | TXD | CAN Transmit |
| PB9 | RXD | CAN Receive |
| GND | GND | Ground |
| +3.3V | VCC | Power |

---
