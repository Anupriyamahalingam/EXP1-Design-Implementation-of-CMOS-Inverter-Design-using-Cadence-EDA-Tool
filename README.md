# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:

![Screenshot 2025-03-28 141357](https://github.com/user-attachments/assets/d45cc31b-ff8e-4c35-b1e9-7272071ab5c3)

#### 2. Transient Response Setup:
![Screenshot 2025-03-28 141700](https://github.com/user-attachments/assets/f2a268d9-f01e-44e7-bc66-f9de290256fc)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:

  ![Screenshot 2025-03-28 141623](https://github.com/user-attachments/assets/2e2b9221-b908-459b-89d8-201636228a69)


## Output
#### 1.Transient Analysis Output
![Screenshot 2025-03-28 141221](https://github.com/user-attachments/assets/b8a465fc-f533-4ec9-892f-fa00c223481d)

#### 2.DC Analysis Output


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.










