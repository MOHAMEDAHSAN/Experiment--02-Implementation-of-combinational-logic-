# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
## Equipments Required:
### Hardware – PCs, Cyclone II , USB flasher
### Software – Quartus prime

## Theory:
Logic gates are electronic circuits which perform logical functions on one or more inputs to produce one output.
1.AND gate :
<br\>
The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B
2.OR gate : The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation. Y= A+B

## Procedure:
1. Create a New Project:
Open Quartus and create a new project by selecting "File" > "New Project Wizard."
Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

2.Create a New Design File:
Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3.Write the Combinational Logic Code:
Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4.Compile the Project:
To compile the project, click on "Processing" > "Start Compilation" in the menu.
Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5.Analyze and Fix Errors:
If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
Review and fix any issues in your code if necessary.
View the RTL diagram.

6.Verification:
Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
Give the Input Combinations according to the Truth Table amd then simulate the Output waveform
## Program:
![CODE](https://github.com/MOHAMEDAHSAN/Experiment--02-Implementation-of-combinational-logic-/assets/139331378/4c6839ae-faaf-4f1f-bb99-84725c44e30f)


## Output:

## RTL realization
### F1:
![F1](https://github.com/MOHAMEDAHSAN/Experiment--02-Implementation-of-combinational-logic-/assets/139331378/85a38899-7ac3-4333-8d8d-ec5121672430)

### F2:
![F2](https://github.com/MOHAMEDAHSAN/Experiment--02-Implementation-of-combinational-logic-/assets/139331378/1fecf16e-7952-466c-8351-486d9317395d)

## Timing Diagram
![TIMINGDIAG](https://github.com/MOHAMEDAHSAN/Experiment--02-Implementation-of-combinational-logic-/assets/139331378/29d2d49b-5684-4f94-a88c-aa5792f9d320)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
