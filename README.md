## Digital Logic Design: 8-Bit SECDED ECC & Finite State Machines

The schematics include both **combinational logic** (1/2/3) and **sequential logic** (4) systems. 

### ECC Memory: Combinational Logic
* [cite_start]**8-bit SECDED**: Implements Single Error Correction, Double Error Detection[cite: 1].
* [cite_start]**ECC Generator**: Generates 5 parity bits through a network of XOR gates[cite: 2].
* [cite_start]**Main Memory**: Uses parity bits to detect, fix single-bit corruption and detect two-bit corruption[cite: 3].

### Finite State Machine (FSM): Sequential Logic
* [cite_start]**Sequence Detector**: Built using D Flip-Flops to manage system states[cite: 4].
* [cite_start]**Lock**: Includes a ripple counter that triggers a system lock after 16 failed input attempts[cite: 4].

---

### Logic Schematics

#### 1. System Architecture Overview
[cite_start]High-level block diagram of the transmission bus and ECC architecture[cite: 1].

![System Overview](1.PNG)

#### 2. ECC Generator Logic
[cite_start]Detailed schematic for XOR-based parity bit creation[cite: 2].

![ECC Generator](2.PNG)

#### 3. Main Memory & Correction Unit
[cite_start]Combinational logic for real-time error detection and correction[cite: 3].

![Main Memory Logic](3.PNG)

#### 4. FSM - Digital Lock
[cite_start]Sequential Logic implementation featuring ripple counters and state transition logic[cite: 4].

![Sequential Logic](4.PNG)
