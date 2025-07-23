# RISC-V Single-Cycle Processor (Verilog)

This project is a Verilog-based implementation of a single-cycle RISC-V processor segmented into the following modules:

## Structure

### single_cycle_top/
- `data_mem.v` — Data memory
- `inst_mem.v` — Instruction memory
- `top.v` — Top-level integration

### single_cycle_core/
- `control_unit/` — Includes `main_decoder`, `alu_decoder`, and `control_unit`
- `core_datapath/` — Includes modules like `pc_ff`, `alu`, `result_mux`, etc.
- `riscV.v` — Wrapper integrating control and datapath

## Features
- RISC-V RV32I single-cycle architecture
- Modular design for clarity
- Easy to simulate and extend

## Simulation
Compatible with ModelSim, Icarus Verilog, or any Verilog simulator.

## Author
Vishnu Hansda
