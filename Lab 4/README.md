# 4-Bit Full Adder Design Using XOR and NAND Gates

This project demonstrates the design and simulation of a **4-bit full adder** constructed from 1-bit full adder cells, which themselves are built using XOR and NAND gates. The design, simulation, and verification were performed entirely in **Cadence Virtuoso**.

## Objective

Design and implement a **4-bit full adder** using:
- 1-bit full adders constructed from **NAND** and **XOR** gates.
- Cadence Virtuoso for schematics, simulation, and symbol generation.

The project aims to verify functional correctness, propagation delays, and power consumption.

---

## Design Workflow

1. **Build Basic Gates**:
   - Design **NAND2** and **XOR2** gate schematics.
   - Verify their functionality and measure **rising/falling propagation delays** and **average power**.
   - Generate symbols for easy reuse.

2. **Create 1-Bit Full Adder**:
   - Construct a 1-bit full adder schematic using NAND and XOR gate symbols.
   - Verify **sum** and **carry** outputs.
   - Ensure **propagation delays** for sum and carry are measured and validated.
   - Generate the 1-bit full adder symbol.

3. **Design 4-Bit Full Adder**:
   - Connect four 1-bit full adder symbols to form a **4-bit full adder**.
   - Simulate **sum (S1, S2, S3, S4)** and **carry** outputs.
   - Measure **average propagation delays** for each output.
   - Analyze **average power consumption**.

---

## Key Observations

- Propagation delays and power for NAND2 and XOR2 gates were measured and compared.
- 1-bit full adder delays for sum and carry outputs were verified, noting slight variations based on measurement points.
- 4-bit full adder demonstrated correct multi-bit binary addition with verified outputs.

---

## Final Deliverables

- Schematics, symbols, and simulation results for:
  - NAND2 Gate
  - XOR2 Gate
  - 1-Bit Full Adder
  - 4-Bit Full Adder

For detailed schematics, waveforms, propagation delay, and power analysis, refer to the full lab report: [ee6540Lab-4.pdf](ee6540Lab-4.pdf).

