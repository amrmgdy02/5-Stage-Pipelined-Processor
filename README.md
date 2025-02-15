## 5-Stage Pipelined Processor
A 5-stage pipelined RISC-like processor implemented in VHDL with Harvard architecture. Features include a custom ISA, exception handling, and pipeline hazard resolution. Designed for FPGA deployment on the DE1-SoC board.

## 🔥 Features
RISC-like ISA with 8 general-purpose 16-bit registers and special-purpose registers (PC, SP, EPC).
Pipeline architecture with fetch, decode, execute, memory, and write-back stages.
Exception handling for stack underflow and invalid memory access.
Supports arithmetic, logic, memory, and branch instructions.
Data and control hazard management using forwarding and static branch prediction.
VHDL implementation of processor components: ALU, Register File, Memory Blocks, and Pipeline Stages.
Testbench & Simulation in ModelSim with waveform analysis.
Assembler for converting assembly programs into machine code.
## 📌 Project Phases
✅ Phase 1: Design & Documentation
Instruction format, opcode mapping, and register structure.
Data flow diagram and pipeline stage details.
Pipeline hazard analysis and resolution techniques.
✅ Phase 2: Implementation & Testing
VHDL implementation of all components.
Integration and simulation of pipeline functionality.
Execution of test programs with waveform analysis.
## 🛠️ Tools & Technologies
VHDL for design
ModelSim for simulation
## 📄 Report & Documentation
Detailed design specifications and changes.
Performance comparison between pipelined and non-pipelined versions.
FPGA resource utilization and clock speed analysis.
## 🎯 Goal: Build an efficient pipelined processor with a functional ISA and optimized hazard handling
