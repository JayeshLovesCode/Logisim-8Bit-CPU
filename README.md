# 8-Bit ALU and Logical Shifter
Designed using **Logisim**, this project implements a functional 8-bit Arithmetic Logic Unit (ALU) capable of performing core arithmetic and bitwise operations.

## Features
* **Arithmetic Operations:** Supports Addition and Subtraction with overflow detection.
* **Logical Operations:** Includes AND, OR, and XOR gates.
* **Shifting Module:** Dedicated units for **Logical Shift Left (LSL)** and **Logical Shift Right (LSR)**.
* **Status Flags:** Implements Zero (Z), Negative (N), and Overflow (V) flags for branch logic.

## How it Works
The ALU takes two 8-bit inputs and a 3-bit control signal (opcode) to determine the operation. The Shifter module was built using multiplexers to efficiently handle bit-shifting without complex propagation delays.
