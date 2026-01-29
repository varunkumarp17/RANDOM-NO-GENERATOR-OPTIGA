# OPTIGA™ IoT Kit – Random Number Generation (Learning Project)

This repository contains a **learning-focused embedded C project** developed using  
**Infineon OPTIGA™ IoT Kit**, **ModusToolbox™**, and **mbedTLS**.

The application demonstrates **cryptographically secure random number generation**
using **CTR_DRBG** and prints the generated random bytes over **UART** in hexadecimal
format.

This project is created **only for learning and educational purposes**.

---

## Project Summary

- Board: Infineon OPTIGA™ IoT Kit  
- Framework: ModusToolbox™  
- Language: C  
- Crypto Library: mbedTLS  
- Output: UART (hexadecimal data)  

---

## What This Project Demonstrates

- Board initialization using `cybsp_init()`
- UART redirection using `cy_retarget_io`
- Entropy initialization with mbedTLS
- CTR_DRBG random number generation
- Printing binary data in hex format
- Basic embedded project structure
- Proper GitHub documentation practices

---

## Hardware Requirements

- Infineon OPTIGA™ IoT Kit
- USB cable (power + UART debug)
- PC / Laptop

---

## Software Requirements

- ModusToolbox™ (v3.x or later)
- GNU Arm Embedded Toolchain
- Serial terminal:
  - PuTTY / Tera Term (Windows)
  - minicom / screen (Linux)
  - CoolTerm (macOS)

---

## Build and Run Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/varunkumarp17/optiga-rng-demo.git
