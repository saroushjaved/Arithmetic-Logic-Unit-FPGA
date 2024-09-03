# 4-bit ALU FPGA Implementation

This repository contains the Verilog code and related files for the design and implementation of a 4-bit Arithmetic Logic Unit (ALU) on an FPGA. The project was part of an academic exercise focused on understanding and applying digital logic design principles using Xilinx ISE and the Spartan-3E FPGA development board.

## Project Overview

- **Objective**: The main goal of this project was to design and implement a 4-bit ALU that can perform a variety of arithmetic and logical operations, such as addition, subtraction, multiplication, division, and bitwise operations like AND, OR, XOR, etc.

- **Implementation**: The ALU was implemented using Verilog with a focus on behavioral level abstraction. The design was synthesized using Xilinx ISE and tested on the Spartan-3E FPGA board. An LCD interface was also implemented to display the outputs of the ALU operations.

- **Operations Supported**:
  - Arithmetic operations: Addition, Subtraction, Multiplication, Division
  - Logical operations: AND, OR, XOR, NAND, NOR, XNOR
  - Shift operations: Left Shift, Right Shift, Rotate Left, Rotate Right
  - Comparison: Greater Than, Equal To

## Files in the Repository

- **`complex_mul.v`**: Verilog code for complex number multiplication.
- **`complex_mul_fixed.v`**: Verilog code for fixed-point complex multiplication.
- **`Two_Point_FFT.v`**: Verilog code for a 2-point FFT module.
- **`Four_Point_FFT.v`**: Verilog code for a 4-point FFT module.
- **`Eight_Point_FFT.v`**: Verilog code for an 8-point FFT module.
- **`Main_FFT.v`**: Top-level module for coordinating the FFT operations.
- **`fpga_report_project.pdf`**: Detailed project report describing the design, implementation, and testing of the 4-bit ALU on the FPGA.

## Key Features

- **Behavioral Abstraction**: The ALU operations were implemented using behavioral Verilog, making it easier to understand and modify.
- **FPGA Implementation**: The project was successfully synthesized and implemented on the Spartan-3E FPGA board.
- **LCD Display**: The outputs of the ALU were displayed on an LCD, interfaced with the FPGA.

This project serves as a practical application of digital design concepts, providing a hands-on experience with FPGA development and Verilog programming.
