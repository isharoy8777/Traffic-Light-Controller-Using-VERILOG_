# 🚦 Traffic Light Controller using Verilog HDL

A **Traffic Light Controller** implemented using **Verilog HDL**, based on a **Finite State Machine (FSM)** approach.  
This project models the behavior of a real-world traffic signal system and demonstrates core **digital design and VLSI concepts** such as sequential logic, state transitions, clocked systems, and testbench-based verification.

---

## 📌 Project Description

This project implements a **clock-driven traffic signal controller** that cycles through standard traffic light states:

- 🔴 **RED**
- 🟢 **GREEN**
- 🟡 **YELLOW**

Each light remains active for a predefined duration before transitioning to the next state.  
The system is designed using **FSM principles** and verified using a **Verilog testbench**.

The project is ideal for:
- Digital Electronics Labs
- Verilog / HDL practice
- FSM-based design understanding
- FPGA / ASIC design fundamentals

---

## ✨ Key Features

- Finite State Machine (FSM)–based design
- Fully synthesizable Verilog HDL code
- Clear state transition logic
- Dedicated testbench for simulation
- Clock and reset-controlled operation
- One-hot traffic signal output behavior
- Clean and modular design

---

## 🛠️ Technologies Used

- **Hardware Description Language:** Verilog HDL
- **Design Concepts:**
  - Finite State Machines (FSM)
  - Sequential Logic
  - Clocked Circuits
  - Testbench Verification
- **Simulation Tools (any one):**
  - ModelSim / QuestaSim
  - Icarus Verilog
  - Vivado Simulator
  - GTKWave (for waveform viewing)

---

## 🧠 Design Methodology

### Finite State Machine (FSM)

The controller is implemented as a **Moore FSM**, where outputs depend only on the current state.

### States Description

| State | Active Signal |
|------|--------------|
| RED | Red light ON |
| GREEN | Green light ON |
| YELLOW | Yellow light ON |

### State Transitions

- RED → GREEN  
- GREEN → YELLOW  
- YELLOW → RED  

Transitions occur after a fixed number of clock cycles.

---



