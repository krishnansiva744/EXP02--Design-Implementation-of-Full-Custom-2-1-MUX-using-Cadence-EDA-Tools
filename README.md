# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## CircuitDiagram
![WhatsApp Image 2024-11-15 at 3 07 27 PM (1)](https://github.com/user-attachments/assets/644f306e-2325-44c7-a998-ed93c725ae46)

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. Schematic of Full Custom 2:1 MUX
![Screenshot 2025-03-23 235042](https://github.com/user-attachments/assets/5a848b9c-ea39-407d-99de-2c8457cb143b)


### 2. Transient Response Setup
![Screenshot 2025-03-23 235145](https://github.com/user-attachments/assets/af53b362-c50f-4a6e-9990-bca7d6fbf0d1)

![Screenshot 2025-03-23 235342](https://github.com/user-attachments/assets/4c235867-a281-416e-8215-1c341b7c5d88)

## Output

### 1. Transient Analysis Output
![Screenshot 2025-03-23 235407](https://github.com/user-attachments/assets/b5abb8e4-7206-409b-8530-d8418205e957)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
