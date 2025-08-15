How it works
This project is an 8-bit custom processor designed in Verilog. It includes essential components such as:

Program Counter (PC): Keeps track of instruction addresses.

Control Unit: Decodes instructions and generates control signals.

ALU (Arithmetic Logic Unit): Performs arithmetic and logic operations.

Register File: Stores and retrieves 8-bit data values.

The processor fetches instructions, decodes them, performs operations via the ALU, and stores results. All actions are synchronized with the clock input.

How to test
To test this processor:

Ensure all Verilog files are in the correct directories.

Navigate to the test/ folder.

Use make to run the cocotb testbench:

cd test make

The testbench sets input values and verifies output through assertions.

You can modify the test.py file to check different inputs and behaviors.

External hardware
Not applicable — this project runs entirely in simulation and does not require external hardware.
