# Design-of-Degenerated-Common-source-Amplifier


## Project Overview
This project involves the design, simulation, and analysis of a degenerated common source amplifier using 180nm CMOS technology. The aim is to achieve enhanced stability and linearity through source degeneration.

## Objectives
- Design a degenerated common source amplifier.
- Simulate and analyze performance metrics such as Gain, Output Resistance, and Transconductance.
- Validate the amplifier's performance using Cadence Spectre tool.

## Project Details

### Design and Schematic
- Developed the amplifier schematic using Cadence Virtuoso.
- Implemented source degeneration to improve stability and linearity.

### Simulation and Analysis
- Performed AC analysis in Cadence Spectre to calculate:
  - **Gain**: Achieved through the formula \( A_v = -\frac{g_m \cdot R_D}{1 + g_m \cdot R_S} \)
  - **Output Resistance (Rout)**: \( R_{out} \approx r_o \parallel (1/g_m) \)
  - **Transconductance (g_m)**: Calculated during the simulation

## Tools Used
- **EDA Tools**: Cadence Virtuoso, Cadence Spectre
