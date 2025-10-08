# fifo

This project implements a FIFO (First-In First-Out) memory buffer in Verilog HDL.
A FIFO is a commonly used data structure in hardware design for temporary data storage between two subsystems operating at different rates — often used in UARTs, DMA controllers, and other streaming data paths.

The design includes:

Parameterized 16×8 FIFO memory

Separate read and write control logic

Full and Empty flag generation

A SystemVerilog interface (fifo_if) for easier verification

⚙️ Features

Synchronous FIFO design (single clock domain)

8-bit data width, 16-entry depth

Full and Empty flag logic

Auto-reset of pointers and counter

Interface (fifo_if) for SystemVerilog testbench integration
