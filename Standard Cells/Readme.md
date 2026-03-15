# Standard Cells

This directory contains the **standard cell layouts and descriptions** used in the Wide Band Gap (WBG) Course Project.  
Standard cells are the fundamental building blocks of digital integrated circuits and are widely used in ASIC design and VLSI implementation.

These cells are designed using **CMOS logic principles** and follow standard layout design rules.

---

## Contents

The following standard cells are included in this directory:

| Cell | Description |
|-----|-------------|
| Inverter | Basic CMOS inverter used for signal inversion |
| NAND Gate | Two input NAND gate implemented using CMOS logic |
| NOR Gate | Two input NOR gate implemented using CMOS logic |



---

## CMOS Standard Cell Design

Standard cells are typically designed using complementary MOS (CMOS) technology, which combines:

- **NMOS transistors**
- **PMOS transistors**

CMOS logic provides:

- Low static power consumption
- High noise immunity
- High integration density

---

## Layout Methodology

The standard cells in this project follow typical VLSI layout practices:

1. **PMOS transistors** are placed in the n-well region.
2. **NMOS transistors** are placed in the p-substrate.
3. Power rails are placed at the top and bottom of the layout:
   - VDD (top)
   - GND (bottom)
4. Metal interconnections are used to connect transistor terminals.

This structure enables easy placement in a **standard cell library row-based layout**.

---

## Example: CMOS Inverter

A CMOS inverter consists of:

- One PMOS transistor connected to VDD
- One NMOS transistor connected to GND
- The gates of both transistors connected together as the input

Operation:

- Input = 0 → PMOS ON, NMOS OFF → Output = 1
- Input = 1 → PMOS OFF, NMOS ON → Output = 0

---

## Applications of Standard Cells

Standard cells are used in the implementation of:

- Logic synthesis
- Digital circuit design
- ASIC development
- Microprocessors
- Memory circuits

In modern chip design flows, large digital circuits are constructed by placing and routing thousands of standard cells.

---

## Purpose in This Project

The goal of this directory is to demonstrate the **layout design of basic CMOS standard cells** as part of the Wide Band Gap course project.

These layouts provide a foundation for understanding:

- transistor level design
- CMOS logic implementation
- physical design considerations in VLSI circuits

---
## Author
Ravuri Leela Venkata Sai Krishna  
B.Tech Electrical and Computer Engineering
