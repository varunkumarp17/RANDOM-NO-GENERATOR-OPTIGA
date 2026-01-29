# OPTIGA™ IoT Kit – Random Number Generation (Learning Project)

This repository contains a **learning and experimental project** developed using  
**Infineon OPTIGA™ IoT Kit**, **ModusToolbox™**, and **mbedTLS**.

The application demonstrates **cryptographically secure random number generation**
using **CTR_DRBG** and prints the generated data over **UART** in hexadecimal format.

---

## 📌 Project Purpose

This project is created **purely for learning and educational purposes**, to understand:

- ModusToolbox™ project structure
- Board initialization on OPTIGA™ IoT Kit
- UART retargeting using `cy_retarget_io`
- Entropy initialization
- Random number generation using **mbedTLS CTR_DRBG**
- Embedded C project organization
- Basic GitHub usage (README, YAML, version control)

---

## 🧰 Hardware Requirements

- Infineon **OPTIGA™ IoT Kit**
- USB cable (power + UART debug)
- PC / Laptop

---

## 💻 Software Requirements

- **ModusToolbox™** (recommended v3.x or later)
- GNU Arm Embedded Toolchain (installed via ModusToolbox)
- Terminal emulator:
  - PuTTY / Tera Term (Windows)
  - minicom / screen (Linux)
  - CoolTerm (macOS)

---

## 📂 Repository Structure

