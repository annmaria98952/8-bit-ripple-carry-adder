# 8-Bit Ripple Carry Adder — NAND-Only CMOS Implementation

## Overview
This implementation of an 8-bit ripple carry adder uses CMOS full-adder circuits constructed using NAND logic. The circuit was designed and simulated using Cadence Virtuoso.

## Design Description
NAND gates are universal logic gates that can be used to implement other Boolean functions. This implementation explores the construction of full-adder logic using NAND gates.

The full-adder circuit generates the Sum and Carry outputs from two input bits and an incoming carry.

- **Sum:** A ⊕ B ⊕ Cin
- **Carry-out:** AB + ACin + BCin

Eight full-adder stages are cascaded to form the 8-bit ripple carry adder, allowing carry signals to propagate from one stage to the next.

## Implementation
- Designed CMOS full-adder circuitry using NAND logic.
- Cascaded eight full-adder stages to construct the 8-bit adder.
- Developed circuit schematics in Cadence Virtuoso.
- Simulated the circuit to verify sum generation and carry propagation.

## Tools Used
- Cadence Virtuoso
- CMOS schematic design and circuit simulation

## Verification
Simulation waveforms were used to examine the response of the circuit to input combinations and verify the sum and carry outputs.

## Project Files
- NAND-based CMOS full-adder schematic
- 8-bit ripple carry adder schematic
- Simulation waveform screenshots

## Key Learnings
- CMOS implementation using universal logic gates
- Full-adder design using NAND logic
- Multi-stage carry propagation
- Schematic development and circuit verification in Cadence Virtuoso
