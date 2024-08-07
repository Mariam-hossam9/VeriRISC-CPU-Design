Objective
To understand and become familiar with the VeriRISC lab model.

Overview
The VeriRISC model is a simplified, very-reduced-instruction-set processor implemented in Verilog HDL. It features a minimal instruction set with a three-bit operation code and a five-bit operand, limiting its functionality to eight instructions and an address space of 32 locations. The design includes a fetch-and-execute cycle that is divided into eight phases for easy visualization and debugging.

Lab Exercises
This series of lab exercises is designed to help you explore and understand the architecture of the VeriRISC processor. You will engage with various components of the VeriRISC system, such as the Address Multiplexor, Counter, Controller, Register, ALU, and more. By the end of the exercises, particularly in Lab 12-1, you will integrate these components and verify the complete design with a few basic instructions.

Key Components
Accumulator Register (ac): Stores intermediate arithmetic results.
Instruction Register (ir): Holds the instruction currently being executed.
Program Counter (pc): Tracks the address of the next instruction to be executed.
ALU (Arithmetic Logic Unit): Executes arithmetic and logical operations.
Controller: Manages control signals for processor operations.
Memory: Stores instructions and data.
Phase Generator: Produces clock phases to synchronize operations.
