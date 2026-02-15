# 8-Bit Arithmetic Logic Unit (ALU)
A Verilog implementation of an 8-bit ALU capable of performing arithmetic and logical operations. This project was simulated using Icarus Verilog and visualized with GTKWave.
## Features
8-bit Data Width: Handles two 8-bit inputs (A and B).
## Operations
Arithmetic: Addition, Subtraction.\
Logical: AND, OR, XOR, NOT.\
Shifting: Logical left shift and logical right shift.\
Flags: Includes Zero flag, Carry flag.
## Tools Used
Language: Verilog HDL\
Simulator: Icarus Verilog (iverilog)\
Waveform Viewer: GTKWave\
Editor: VS Code with Verilog extensions.
## Project Structure
├── alu.v                     # Main ALU design module\
├── alu_tb.v                  # Testbench for verification\
├── alu.vcd                   # Waveform file (generated after simulation)\
└── 8-bit ALU report.docx     # Detailed design and analysis report
## How to Run
To compile and simulate the project, run the following commands in your terminal:\
### Compile the code:
iverilog ALU.v ALU_tb.v\
Running "iverilog ALU.v ALU_tb.v" to compile the design. This creates a simulation file (traditionally named a.out).\
### Run the simulation:
vvp a.out
### View the waveforms:
gtkwave alu.vcd
## Simulation Results
The testbench verifies each opcode by applying various input combinations. You can view the timing diagrams in GTKWave to observe signal transitions.


<img width="1610" height="195" alt="Screenshot 2026-02-15 133736" src="https://github.com/user-attachments/assets/631a97ee-1104-4d3c-be73-f8aca5acbcbe" />
