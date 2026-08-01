# Half Adder using Verilog

## Description
This project implements a **1-bit Half Adder** using Verilog HDL.

A Half Adder performs the addition of two binary inputs:
- A
- B

It produces:
- Sum
- Carry

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## Logic Equations

Sum = A ^ B

Carry = A & B

## Files

- `half_adder.v` → Verilog design
- `half_adder_tb.v` → Testbench
- `output.png` → Simulation output waveform

## Software Used

- Xilinx Vivado
- ModelSim
- Icarus Verilog

## Author

Your Name