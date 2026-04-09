## Digital Logic Design: 8-Bit SECDED ECC & Finite State Machines

My collection of **logic schematics** focusing on the hardware-level implementation of error correction and sequential logic. 

The schematics detail both **combinational logic**(1/2/3) and **sequential logic** (4) systems. 

ECC memory: combinational logic
8-bit SECDED (Single Error Correction, Double Error Detection)
generate 5 parity bits through XOR gates
detect and fix single-bit corruption
detect two-bit corruption


Finite State Machine (FSM): sequential logic
ripple counter that triggers a system lock after 16 failed input attempts
---

### Logic Schematics

#### 1. System Architecture Overview
Block diagram
![System Overview](1.PNG)

#### 2. ECC Generator Logic
XOR-based parity bit creation
![ECC Generator](2.PNG)

#### 3. Main Memory & Correction Unit
Logic for error detection/correction
![Main Memory Logic](3.PNG)

#### 4. FSM - Digital Lock
Sequential Logic, ripple counters
![Sequential Logic](4.PNG)