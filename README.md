This repository contains the necessary resources to create a modular design entry in Verilog HDL using the Altera Quartus II ISE 13.0 Service pack 1 Project Navigator.

## Hierarchical Schematic Entry with Multibit Signals

This project highlights the process of pulling together multiple schematic or Verilog design modules in the schematic capture tool using their symbols. The process includes symbol creation for each design module and module instantiation in the schematic capture tool. The method for entering multi-bit signals in the schematic tool is also demonstrated.

## Experimental Setup

The experimental setup involves:

- A Personal Computer (PC) with Altera Quartus II ISE 13.0 Service pack 1 Project Navigator.
- DEO Demo Board with Cyclone III EP3C16F484C6 FPGA installed on a card with 10 input toggle switches, three pushbuttons, and four 7-Segment LED displays, among other components.
- A cable connected between the demo board and the PC using a USB interface in order to transfer design information from the PC to the Demo Board.

## Projects

### 4-Bit Arithmetic Unit with Decoder
The design of an Adder/Subtractor and a Decoder has been demonstrated in detail. The method of creation, compilation, and testing of the design using a demo board is illustrated.

### Arithmetic Unit
The implementation of a complete combinational design using Schematic Capture is shown, including testing and verification using functional and timing simulations. 

### 4-Bit Logic Unit with Muxes
The design and testing process for a 4-Bit Logic Unit is outlined, with the implementation of a complete combinational design using Schematic Capture.

### 4-Bit ALU Top-Level
Finally, the project shows the implementation of a 4-bit Arithmetic Logic Unit (ALU), involving design creation, simulation, programming to FPGA, and testing.

## Contribution
To understand the steps involved in the contribution to this project, please read through the [Contribution Guide](CONTRIBUTING.md).

## License
This project is licensed under the terms of the MIT license.
