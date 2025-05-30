# Digital Logic Gate Design and Simulation – Lab 3

This project involves the **design, layout, and simulation of standard CMOS logic gates**—**Inverter, NAND2, NOR2, NOR3, and XOR2**—using **Cadence Virtuoso** exclusively. The goal is to implement these gates as standard cells, ensuring correct functionality and adherence to design rules.

## Objective
Design, layout, and simulate the following gates using Cadence Virtuoso:
- Inverter
- NAND2
- NOR2
- NOR3
- XOR2

## Workflow
- **Schematic Design**: Implement gate logic using the Virtuoso Schematic Editor.
- **Layout Design**: Create layouts based on transistor-level schematics and stick diagrams, following λ-based design rules.
- **DRC & LVS**: Verify design rule compliance and schematic-to-layout matching using Virtuoso's tools.
- **PEX (Parasitic Extraction)**: Generate netlists with parasitics for accurate simulation.
- **Simulation**: Perform transient analysis and delay measurements directly within Cadence Virtuoso ADE (Analog Design Environment).
- **Waveform Visualization**: Plot and analyze simulation results in Virtuoso.

## Key Design Rules (λ-based)
- Minimum width/spacing for metal and diffusion layers: **4λ**
- Contact size: **2λ × 2λ** with **1λ** surround
- Polysilicon width: **2λ**
- Poly-diffusion overlap: **2λ**
- Poly-contact spacing: **3λ**
- Well spacing: **6λ** from transistors (minimum), **9λ–10λ** between wells

## Final Deliverables
- Schematics, layouts, stick diagrams, and testbench setups for:
  - Inverter
  - NAND2
  - NOR2
  - NOR3
  - XOR2
- DRC & LVS clean layouts.
- Simulated waveforms and propagation delay measurements for all gates.

For detailed procedures, results, and diagrams, refer to the full lab report: [EE6540Lab-3.pdf](EE6540Lab-3.pdf).

