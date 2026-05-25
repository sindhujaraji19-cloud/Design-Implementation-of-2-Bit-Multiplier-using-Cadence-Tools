# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

<img width="1920" height="1080" alt="Screenshot (519)" src="https://github.com/user-attachments/assets/29b4db89-e37f-409a-a3a3-a761b15247af" />

<img width="1920" height="1080" alt="Screenshot (523)" src="https://github.com/user-attachments/assets/a17df61f-b48b-4f4f-b3cb-631b5a32ebc6" />

### Schematicand Symbol of 2-Input EX-OR Gate:

<img width="1920" height="1080" alt="Screenshot (520)" src="https://github.com/user-attachments/assets/f7643ead-e46b-4fda-b4a4-078001ac3f7f" />

<img width="1920" height="1080" alt="Screenshot (524)" src="https://github.com/user-attachments/assets/1e36aac3-bf33-4801-bede-8a9c08af3961" />

### Schematicand Symbol of Half Adder:

<img width="1920" height="1080" alt="Screenshot (521)" src="https://github.com/user-attachments/assets/d758d6fb-28bc-481e-abc9-4bfa08d69b21" />

<img width="1920" height="1080" alt="Screenshot (525)" src="https://github.com/user-attachments/assets/eb071363-8531-42e4-8657-aa7f470f2c08" />

### Schematic of 2-Bit Multiplier:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/187be364-d03d-403f-ad41-6eb3c79e6e6d" />

## Output
### Transient Analysis Output:
![Screenshot 2025-05-15 153033](https://github.com/user-attachments/assets/2c94f184-525c-49ba-8733-27c982f0dffa)

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4e5b3484-62bc-45a1-bed2-84febef8adf0" />

Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
