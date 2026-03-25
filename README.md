# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module boolean_function (
    input A, B, C, D,
    output F
);

assign F = (~A & ~B & ~C & ~D) |
           ( A & ~C & ~D )     |
           (~B &  C & ~D )     |
           (~A &  B &  C &  D) |
           ( B & ~C &  D );

endmodule



Developed by: RegisterNumber:*/  212225040141
Name : JAIRAM J


**RTL realization**

**Output:**


**RTL**
<img width="1901" height="762" alt="1" src="https://github.com/user-attachments/assets/79cf813e-550c-4a0b-8c67-db55686cba57" />





**Timing Diagram**
<img width="662" height="622" alt="exp2_waveform" src="https://github.com/user-attachments/assets/ed43e56e-c88c-4fba-8d3f-971e38cd8f3a" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

