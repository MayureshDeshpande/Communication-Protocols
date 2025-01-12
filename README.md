# Communication-Protocols
Communication Protocols Design and Verification
Overview
This repository contains the design and verification of three widely-used communication protocols:

Serial Peripheral Interface (SPI)
Universal Asynchronous Receiver Transmitter (UART)
Inter-Integrated Circuit (I2C)
The designs are implemented using Verilog, and the verification environment is developed in SystemVerilog. The project also includes a comprehensive testing framework to simulate various network conditions and evaluate protocol performance.

Features
Design Modules:
design.v: Contains Verilog-based implementations for SPI, UART, and I2C.
Testbench Framework:
testbench.sv: Developed in SystemVerilog, this file provides a robust simulation environment to validate protocol functionality.
Simulation Scenarios:
Simulates different operating conditions such as varying clock frequencies, edge cases, and error handling.
Tests include corner cases like buffer overflows, invalid data transmissions, and error flags.
