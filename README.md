# VHDL Basic Logic Gates

## 📌 Overview

This repository contains implementations of fundamental digital logic gates using VHDL and AMD Vivado. The project focuses on understanding Boolean logic, combinational circuit design, and functional simulation.

## 🎯 Objectives

- Understand the fundamentals of digital logic design.
- Implement basic logic gates using VHDL.
- Learn VHDL entity and architecture declarations.
- Explore concurrent signal assignments and Boolean operators.
- Verify circuit functionality through simulation and testbenches.

## ⚙️ Logic Gates

The repository will cover the following digital logic gates:

| # | Logic Gate | Boolean Expression | Description |
|---|---|---|---|
| 1 | AND | `Y = A AND B` | Output is HIGH when both inputs are HIGH. |
| 2 | OR | `Y = A OR B` | Output is HIGH when at least one input is HIGH. |
| 3 | NOT | `Y = NOT A` | Output is the inverse of the input. |
| 4 | NAND | `Y = NOT (A AND B)` | Output is LOW only when both inputs are HIGH. |
| 5 | NOR | `Y = NOT (A OR B)` | Output is HIGH only when both inputs are LOW. |
| 6 | XOR | `Y = A XOR B` | Output is HIGH when the inputs are different. |
| 7 | XNOR | `Y = A XNOR B` | Output is HIGH when the inputs are equal. |

## 🛠️ Tools and Technologies

- **Hardware Description Language:** VHDL
- **Design and Simulation Tool:** AMD Vivado
- **Design Type:** Combinational Logic
- **Verification:** VHDL Testbenches and Simulation Waveforms

## 📁 Repository Structure

```text
vhdl-basic-gates/
├── README.md
├── src/
│   ├── and_gate.vhd
│   ├── or_gate.vhd
│   ├── not_gate.vhd
│   ├── nand_gate.vhd
│   ├── nor_gate.vhd
│   ├── xor_gate.vhd
│   └── xnor_gate.vhd
└── testbench/
    ├── tb_and_gate.vhd
    ├── tb_or_gate.vhd
    ├── tb_not_gate.vhd
    ├── tb_nand_gate.vhd
    ├── tb_nor_gate.vhd
    ├── tb_xor_gate.vhd
    └── tb_xnor_gate.vhd
```

*Note: The repository structure represents the planned project organization. Files will be added as each logic gate is implemented.*

## 🧪 Simulation and Verification

Each logic gate will be described using VHDL and tested in AMD Vivado.

The verification process includes:
1. Creating the VHDL design.
2. Developing a testbench to apply input combinations.
3. Running behavioral simulation.
4. Comparing the outputs against the expected truth table.
5. Examining simulation waveforms to verify circuit behavior.

## 📚 Learning Outcomes

- Understanding basic Boolean operations.
- Describing combinational circuits using VHDL.
- Working with entities, architectures, and signal assignments.
- Developing testbenches for functional verification.
- Analysing simulation waveforms.
- Building a foundation for more complex digital designs.

## 🚀 Future Improvements

- Complete the implementation of all seven logic gates.
- Add truth tables and simulation results for each gate.
- Include waveform screenshots from AMD Vivado.
- Expand the repository with combinational circuits such as multiplexers, decoders, and adders.

---

**Author:** Ghulam Sarwar  
**Technologies:** VHDL | AMD Vivado
