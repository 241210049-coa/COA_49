Multiplexer and Encoder Design (COA Lab)
Author

Jitarth Singh

Overview

This project presents the design and simulation of fundamental digital logic components as part of the Computer Organization and Architecture (COA) laboratory work. The implementation focuses on multiplexers and encoders, which are essential building blocks in digital systems.

The following components have been designed and tested:

8×1 Multiplexer (Direct Implementation)
8×1 Multiplexer using 2×1 Multiplexers
Encoder
Priority Encoder
Objectives
To understand the working principles of multiplexers and encoders
To design an 8×1 multiplexer using a direct approach
To implement an 8×1 multiplexer using multiple 2×1 multiplexers
To study the functionality of encoders and priority encoders
To verify the output behavior for different input combinations
System Description
1. 8×1 Multiplexer (Direct Implementation)

The 8×1 multiplexer selects one of eight input lines based on three selection lines. The selected input is forwarded to the output.

Inputs: D0 to D7
Select Lines: S0, S1, S2
Output: Y

The output depends on the binary value of the select lines.

2. 8×1 Multiplexer using 2×1 Multiplexers

This design implements an 8×1 multiplexer using seven 2×1 multiplexers in a hierarchical structure.

First Stage: Four 2×1 multiplexers
Second Stage: Two 2×1 multiplexers
Final Stage: One 2×1 multiplexer

This approach demonstrates how complex circuits can be built using simpler components.

3. Encoder

An encoder converts multiple input lines into a smaller number of output lines.

Example: 8-to-3 Encoder
Function: Converts one active input into a binary output
4. Priority Encoder

A priority encoder outputs the binary code of the highest-priority active input.

Handles multiple active inputs
Assigns priority (highest input has highest priority)
Outputs corresponding binary code
Working Principle
In multiplexers, select lines determine which input is passed to the output
In encoders, the input line number is converted into binary form
In priority encoders, if multiple inputs are active, the one with the highest priority is selected
Tools Used
Digital Logic Simulator (e.g., Logisim / Proteus or equivalent)
Basic digital components (MUX, logic gates, switches, LEDs)
Result

All circuits were successfully designed and verified. The outputs matched the expected theoretical results for different input combinations.

Conclusion

This experiment helped in understanding the practical implementation of multiplexers and encoders. It also demonstrated how complex digital circuits can be constructed using simpler building blocks such as 2×1 multiplexers.