Project Title

8-bit ALU with Barrel Shifter and Status Flags — SKY130 Open-Source Implementation

Project Description

This project implements a compact 8-bit Arithmetic Logic Unit (ALU) integrated with a barrel shifter in Verilog, targeting SkyWater SKY130 standard cells.

The ALU supports a range of arithmetic and logical operations, including addition, subtraction, increment, decrement, AND, OR, XOR, and NOT. The barrel shifter adds flexible variable left/right shift operations in a single cycle, controlled via a shift amount input.

In addition, the ALU produces CPU-style status flags: Zero (Z), Carry (C), Negative (N), and Overflow (V), which allow conditional operations and serve as essential indicators for processor datapaths.

This project provides a modular, reusable IP block suitable for integration into mini CPUs, microcontrollers, or digital systems requiring arithmetic, logic, and bit-shifting operations. It is fully synthesizable, verifiable with comprehensive testbenches, and compatible with the OpenLane flow for tapeout readiness.

Project Proposal

The objective of this project is to design a highly functional, small-scale datapath unit that demonstrates realistic ALU operations, flexible bit manipulation, and flag generation in an 8-bit hardware context.

Key deliverables include:

Modular Verilog RTL for the ALU and barrel shifter

Functional testbenches covering arithmetic, logic, and shift operations, as well as status flag verification

STA and SDF-ready constraints for timing verification

OpenLane flow configuration and reproducible results for SkyWater SKY130 standard cells

Documentation with step-by-step build and simulation instructions, screenshots, and demonstration video

Open-source licensing (Apache 2.0) to enable public reuse and contribution

This project demonstrates practical digital design principles, combining combinational and sequential logic, modular RTL coding, and verification workflows. It offers a balanced complexity that is both educational and applicable in real-world digital systems, making it an ideal candidate for open-source hardware projects.
