<h1 align="center">RISC-V Single-Cycle Architecture (Extended)</h1>

<p align="center">
  Microarchitecture implemented in SystemVerilog with extended instruction set.
</p>

<h2 align="center">🖼️ Architecture Diagram</h2>

<p align="center">
  <img src="Diagrama Monociclo Estendido.jpg" width="600"/>
</p>

---

## 📌 Overview

This project consists of the modification and expansion of a previously implemented **single-cycle RISC-V microarchitecture** in SystemVerilog.

The main goal was to extend the supported instruction set, originally limited to basic arithmetic, logical operations, memory access, and simple branching.

---

## 🚀 Extensions Implemented

The architecture was enhanced to support additional instructions, increasing its computational capability.

### ➕ New Instructions:
- `mul` (multiplication)
- `div` (division)
- `xor`, `xori`
- `ori`, `andi`
- `sll` (shift left logical)
- `bne` (branch if not equal)
- `blt` (branch if less than)
- `bge` (branch if greater or equal)

---

## ⚙️ Architectural Modifications

To support the new instructions, the following components were modified:

- Arithmetic Logic Unit (ALU)
- Control Unit
- Instruction Decoder

These changes ensure correct execution and integration of the extended instruction set.

---

## 🧪 Simulation and Testing

The architecture was validated using:

- **Intel Quartus**
- Test programs written in **RARS (RISC-V Assembler and Simulator)**

---

## ▶️ How to Run the Project

### Option 1 — Open directly in Quartus
1. Clone or download this repository:
```bash
https://github.com/natycristina/Extended-Single-Cycle-RISC-V-Implementation.git

2. Open the project file:

Ic-teste-validando.qpf

3. Compile the project

4. Open the waveform file:

Waveform.vwf

5. Run simulation

### Option 2 — Create a new Quartus project

1. Open Quartus

2. Create a new project

3. Add all .sv files from this repository

4. Compile the design

5. Run simulation using the waveform file

##  📁 Project Structure

*.sv → SystemVerilog source files

*.vwf → Waveform simulation file

*.qpf → Quartus project file

*.txt → Machine code / test inputs

## 🎯 Conclusion

This project demonstrates the extension of a basic RISC-V processor, highlighting how architectural modifications enable support for a richer instruction set.

It was a valuable experience in digital design, computer architecture, and hardware description using SystemVerilog.

## 👩‍💻 Author

Nataly Cristina

Developed as part of an undergraduate research project (Iniciação Científica).
