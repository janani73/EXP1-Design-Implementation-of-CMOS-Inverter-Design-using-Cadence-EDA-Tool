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
#### 1. CMOS Inverter:

<img width="750" height="421" alt="image" src="https://github.com/user-attachments/assets/f269ae45-59a3-4ebc-9a1f-dfb728f15e42" />


#### 2. Schematic of CMOS Inverter:
<img width="1920" height="1080" alt="Screenshot 2025-08-23 144308" src="https://github.com/user-attachments/assets/d5e6b3bd-694b-4bf6-8fd4-8b9c7bb0eafe" />



#### 3. Transient Response Setup:

<img width="510" height="603" alt="janani2" src="https://github.com/user-attachments/assets/120d151c-90c6-4026-bd97-3731f6b8f774" />



<img width="1920" height="1080" alt="Screenshot 2025-08-23 144549" src="https://github.com/user-attachments/assets/61573a34-004a-4307-93bc-30e03bcd3a95" />





## Output
#### 1.Transient Analysis Output

<img width="1920" height="1080" alt="Screenshot 2025-08-23 144150" src="https://github.com/user-attachments/assets/08d9a4ce-40a9-4436-8605-f73a317f1137" />




## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











