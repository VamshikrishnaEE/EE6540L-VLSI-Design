# 4-Bit Down Counter Design (Binary and Decimal)

## Overview

This project involves designing a **4-bit down counter** capable of operating in both **binary** and **decimal** modes. The design uses the **D Flip-Flop** implemented in a previous lab. The counter's operation is simulated under different clock periods to observe its behavior.

Key steps in the design include:
- Utilizing the previously designed **D Flip-Flop**.
- Connecting the circuit according to the provided schematic.
- Simulating the counter operation using a clock period of **2n** (as per the manual).
- Observing the counter behavior with clock periods of **0.125n** and **1n**.

Key observations:
- The down counter operates correctly with a clock period of **2n**.
- The counter shows disturbances and malfunctions with a clock period of **0.125n**.
- Adjustments in PMOS and NMOS widths improve performance, power efficiency, and space utilization, helping circuits run smoothly at higher frequencies.

---

## For Detailed Diagrams and Waveforms

Please refer to the PDF file:  
👉 [EE6540Lab-6.pdf](./EE6540Lab-6.pdf)

---

## Conclusion

This lab demonstrated the design and implementation of a **4-bit binary and decimal down counter**, reinforcing concepts of sequential logic, binary/decimal counting systems, and practical applications in digital design. A 4-bit binary counter counts from **15 (1111 in binary)** to **0 (0000 in binary)**, while a decimal counter counts from **9 to 0**.

