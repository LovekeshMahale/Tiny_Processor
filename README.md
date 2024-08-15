# FPGA-Based Tiny Processor and System Design

## Project Overview

This repository details the design and implementation of a "Tiny" Processor, featuring comprehensive Verilog code, testbenches, block diagrams, and simulation results. It also includes advanced components such as FSM detection, enhanced register files, and various multiplier designs, alongside FPGA implementation and live demonstrations.

## Project Components

1. **Processor Design Showcase**
    - **Verilog Implementation**: Complete code for a Tiny Processor incorporating 16 8-bit registers.
    - **Verification Testbench**: Framework created to test and validate processor functionality.
    - **XDC Constraint Files**: Essential files for configuring FPGA hardware.
    - **System Block Diagram**: Diagram illustrating the connections and interactions of Verilog modules.
    - **Simulation Outputs**: Results from various simulations to verify processor performance.
    - **FPGA Demo Video**: Video demonstrating the processor executing a program with a minimum of four instructions.
    - **Processor Features**: Executes commands using a register file and an accumulator; includes an extended register for multiplication/division and a carry/borrow register for arithmetic operations.

2. **Finite State Machine (FSM) Implementations**
    - **Verilog Code**: Development of FSMs (Moore and Mealy) to detect the sequence 10010.
    - **FSM Verification**: Testbench designed to ensure FSMs function as intended.
    - **FSM Simulation Results**: Outputs from simulations of the FSM designs.
    - **FPGA Implementation**: Demonstration of FSM functionality on FPGA, using switches for input and LEDs for output.

3. **Enhanced Register File with Arithmetic Unit Integration**
    - **Verilog Code**: Extension of the register file from 8 to 16 registers with dual-port reading capabilities.
    - **Testbench**: Verification framework for the extended register file and integrated ALU.
    - **Simulation Outputs**: Results validating the dual-port register file and ALU operations.
    - **FPGA Implementation**: Showcase of the enhanced register file and ALU design on FPGA.

4. **8-bit Multiplier Designs**
    - **Verilog Code**: Design and implementation of both 8-bit x 8-bit array and binary multipliers.
    - **Multiplier Testbench**: Verification of both array and binary multipliers.
    - **Comparison Results**: Data comparing the performance of array and binary multipliers.
    - **FPGA Demonstration**: Demonstration of the 4-bit multiplier designs on FPGA.

## Academic Context
This project was completed as part of the Digital Systems course at the Indian Institute of Technology Gandhinagar (IIT Gandhinagar), under the guidance of [Prof. Joycee Mekie](https://joycee.people.iitgn.ac.in/).
