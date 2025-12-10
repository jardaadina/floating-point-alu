# Floating Point ALU (IEEE 754)

This project aims to design and implement an Arithmetic Logic Unit (ALU) capable of performing addition and multiplication operations for floating-point numbers, according to the **IEEE 754** standard.

The unit is designed using **VHDL** and simulated on the **Xilinx** platform. It is also implemented on an **FPGA** device to evaluate its performance in terms of resource consumption and execution speed.



## Project Goal
To develop an efficient and precise ALU for floating-point addition and multiplication. This module is designed for computing systems that require high precision and optimized processing of complex numerical data.

## Project Structure

### Introduction
* Context and project objectives.

### Literature Review
* Overview of the Arithmetic Logic Unit (ALU).
* Solutions for truncation errors and calculation precision.
* Representation of floating-point numbers and the IEEE 754 format.
* Details on floating-point addition and multiplication algorithms.

### Analysis
* Algorithms for addition and multiplication.
* Flowcharts for the algorithms.

### Design
* Block diagram of the ALU architecture.



[Image of ALU block diagram]


### Implementation
* Details on the VHDL implementation of floating-point addition and multiplication.

### Testing and Validation
* FPGA testing of the ALU functionality.

### Conclusions
* Results obtained from testing and performance analysis.

## Technologies and Tools
* **VHDL:** The hardware description language used to create the ALU.
* **Xilinx:** Platform for simulation and implementation.
* **FPGA:** The hardware device used to test the physical implementation.

## Testing
Tests were conducted to verify:

* **Correctness:** Ensuring addition and multiplication operations are accurate.
* **Corner Cases:** The behavior of the ALU under extreme conditions (Overflow, Underflow, NaN, Infinity).
* **Performance:** Resource utilization and execution speed.
