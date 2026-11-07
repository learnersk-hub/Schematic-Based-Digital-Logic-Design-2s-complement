# Schematic-Based-Digital-Logic-Design-2s-complement

A collection of fundamental digital logic circuits designed and simulated using **Xilinx ISE Design Suite 14.7**. The circuits were implemented using the Schematic Editor and verified through ISim simulation.

## Circuits Implemented

### 1. Half Adder
- Designed using XOR and AND gates.
- Performs addition of two 1-bit binary inputs.
- Generates Sum and Carry outputs.

### 2. Full Adder
- Designed using Half Adder blocks and logic gates.
- Performs addition of three 1-bit inputs (A, B, Cin).
- Generates Sum and Carry outputs.

### 3. 8-Bit Two's Complement Generator
- Designed using interconnected Half Adders, Full Adders and logic gates.
- Generates the 2's complement of an 8-bit binary input.
- Verified using ISim waveform simulation.

## Tools Used
- Xilinx ISE Design Suite 14.7
- ISim Simulator
- Schematic Editor

## Simulation Result

**Example: 8-bit Two's Complement**

| Parameter | Binary Value |
|---|---|
| Input | `00001001` |
| Output | `11110111` |

The simulation confirms the correct Two's Complement output for the given input.

## Learning Outcomes
- Digital logic circuit design.
- Logic gate interconnections.
- Hierarchical schematic design.
- Functional simulation and waveform analysis.

## Author

**Subodh Kushwaha**  