\# Multiplexer and Encoder Design (COA Lab)



\## Author



Jitarth Singh



\---



\## Objective



\* To understand the working principles of multiplexers and encoders

\* To design an 8×1 multiplexer using a direct approach

\* To implement an 8×1 multiplexer using multiple 2×1 multiplexers

\* To study the functionality of encoders and priority encoders

\* To verify output behavior for different input combinations



\---



\## Overview



This project presents the design and simulation of fundamental digital logic components as part of the Computer Organization and Architecture (COA) laboratory work. The implementation focuses on multiplexers and encoders, which are essential building blocks in digital systems.



The following components were designed and tested:



\* 8×1 Multiplexer (Direct Implementation)

\* 8×1 Multiplexer using 2×1 Multiplexers

\* Encoder

\* Priority Encoder



\---



\## Theory



\### Multiplexer



A multiplexer (MUX) is a combinational circuit that selects one input from multiple input lines and forwards it to a single output line based on select signals.



\---



\### Encoder



An encoder is a combinational circuit that converts multiple input lines into a smaller number of output lines, typically in binary form.



\---



\### Priority Encoder



A priority encoder is an advanced encoder that handles multiple active inputs by assigning priority. The highest-priority input is encoded when more than one input is active.



\---



\## System Description



\### 1. 8×1 Multiplexer (Direct Implementation)



The 8×1 multiplexer selects one of eight inputs based on three select lines.



Inputs:



\* D0 to D7



Select Lines:



\* S0, S1, S2



Output:



\* Y



The output depends on the binary value of the select lines.



\---



\### 2. 8×1 Multiplexer using 2×1 Multiplexers



This design constructs an 8×1 multiplexer using seven 2×1 multiplexers arranged in stages.



\* First Stage: Four 2×1 multiplexers

\* Second Stage: Two 2×1 multiplexers

\* Final Stage: One 2×1 multiplexer



This demonstrates hierarchical design using simpler components.



\---



\### 3. Encoder



Example: 8-to-3 Encoder



Function:



\* Converts one active input line into a 3-bit binary output



\---



\### 4. Priority Encoder



\* Handles multiple active inputs

\* Assigns priority (higher index input has higher priority)

\* Outputs binary code of the highest-priority active input



\---



\## Working Principle



\* In multiplexers, select lines determine which input is passed to the output

\* In encoders, the active input line is converted into binary form

\* In priority encoders, if multiple inputs are active, the highest-priority input is selected



\---



\## Tools Used



\* Digital Logic Simulator (Logisim / Proteus or equivalent)

\* Basic digital components such as multiplexers, logic gates, switches, and LEDs



\---



\## Results



All circuits were successfully designed and verified. The outputs matched the expected theoretical results for different input combinations.



\---



\## Applications



\* Data selection in digital systems

\* Signal routing in communication systems

\* Arithmetic and logic unit (ALU) design

\* Control units and processors



\---



\## Conclusion



This experiment helped in understanding the practical implementation of multiplexers and encoders. It also demonstrated how complex digital circuits can be constructed using simpler building blocks such as 2×1 multiplexers.



