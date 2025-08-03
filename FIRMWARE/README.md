# 🔌 Firmware

This directory is reserved for basic embedded control code used during experimental validation of the mechanical system.

---

## 🎯 Purpose

While the primary focus of this project is on **mechanical design and performance**, simple firmware was developed to:

- Control actuators for motion testing
- Read basic sensor inputs (e.g., encoders, limit switches)
- Enable repeatable motion profiles during experiments

---

## 📁 Directory Structure

```plaintext
firmware/
├── /src           # Minimal scripts for motor and sensor control
└── README.md      # This documentation file
```
## ⚠️ Note

This firmware is **not optimized for production or closed-loop precision**. It is intended solely for **prototyping and motion testing** of the mechanical assemblies.

Initial testing was performed using a **servo motor** controlled via an **Arduino** microcontroller for basic position control.

For future iterations, integration with full robotic middleware (e.g., **ROS**, **RTOS**, or **haptic feedback loops**) is recommended.


