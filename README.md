# RISC-V Assembler and Simulator

A custom assembler and simulator for a subset of the **RV32I (RISC-V)** instruction set.

##  Overview
This project converts RISC-V assembly instructions into 32-bit binary machine code and simulates program execution cycle-by-cycle.

##  Features
- Supports **R, I, S, B, and J** instruction formats
- Label resolution and virtual halt support
- Cycle-by-cycle instruction simulation
- Robust error handling for syntax and instruction-specific issues

## Tech Stack
- Python

## How to Run
to run assembler :  python assembler.py input.txt output.txt  
to run simuator : python simulator.py output.txt sim_output.txt
