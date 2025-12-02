# Digital Logic Design Projects ⚡

This repository contains a collection of digital logic circuits designed and simulated using **Logisim**. These projects demonstrate my understanding of computer architecture fundamentals, combinational logic, and sequential circuits.

## 🛠️ Tools Used
* **Logisim** (Digital Logic Simulator)
* **Combinational Logic Analysis** (Karnaugh Maps, Boolean Algebra)

## 📂 Project Overview

### 1. 4-Bit Adder & Subtractor with 2's Complement
* **Description:** A 4-bit Arithmetic Logic Unit (ALU) capable of performing both addition and subtraction.
* **Logic:**
    * Uses **Full Adders** chained together.
    * Implements **XOR gates** for controlled inversion (2's complement) to handle subtraction.
    * Includes a mode selector input (`m`) to switch between addition (0) and subtraction (1).
    * Displays output in Hexadecimal format using splitters.

### 2. BCD to 7-Segment Decoder (Gate Level Implementation)
* **Description:** A purely combinational circuit that takes a 4-bit binary input and drives a 7-segment display.
* **Logic:**
    * Designed from scratch using **Boolean Logic** and **Karnough Map**.
    * Logic expressions were derived and simplified to minimize gate count.
    * Implemented using basic AND, OR, and NOT gates (no pre-built decoder ICs used).

### 3. Binary Decoders (3-to-8 & 5-to-32)
* **Description:** Fundamental decoder circuits demonstrating address decoding logic.
* **Logic:**
    * Standard implementation of minterm generation.
    * Includes ENABLE inputs for cascading capabilities.

---
**Author:** Arda
*Computer Engineering Student*
