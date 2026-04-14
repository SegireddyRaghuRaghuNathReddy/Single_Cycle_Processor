# Single-Cycle RISC-V Processor (Verilog)

## Overview

This project implements a **Single-Cycle RISC-V Processor** using Verilog HDL.
In this architecture, each instruction is executed in a **single clock cycle**, completing all stages — fetch, decode, execute, memory access, and write-back — in one cycle.



## Features

* 32-bit RISC-V (RV32I subset)
* Single-cycle execution (CPI = 1)
* Simple and easy-to-understand architecture
* Modular Verilog design
* Fully functional datapath and control unit


## 🧠 Supported Instructions

* R-type: ADD, SUB
* I-type: ADDI
* Memory: LW, SW
* Branch: BEQ


## Processor Components

* Program Counter (PC)
* Instruction Memory
* Register File
* ALU (Arithmetic Logic Unit)
* Data Memory
* Control Unit: Main Decoder ALU Decoder
* Multiplexers and Adders


## Working Principle

In a single-cycle processor:

* Each instruction completes in **one clock cycle**
* All stages operate sequentially within the same cycle
* Control signals are generated based on the opcode




## Simulation

* Tools Used:
  * Icarus Verilog (iverilog)
  * GTKWave



## Limitations

* Longer clock cycle due to all stages in one cycle
* Lower performance compared to pipelined processors



## Future Work

* 5-Stage Pipeline Processor
* Hazard Detection & Forwarding Unit
* Instruction Cache (I-Cache)
* Data Cache (D-Cache)


## Learning Outcomes

* Understanding of CPU datapath and control
* Basics of RISC-V instruction execution
* Hands-on experience with Verilog HDL
* Foundation for pipelined processor design



## Acknowledgment

This project is inspired by standard RISC-V architecture and academic learning resources.
