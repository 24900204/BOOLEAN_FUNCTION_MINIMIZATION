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

Developed by:L.Rithika RegisterNumber:24900204

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

module booleanminimization(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule


**RTL realization**

![Screenshot 2024-12-07 090530](https://github.com/user-attachments/assets/a7ec5839-a0f6-46db-b599-af880b8ffb0e)

**RTL**

![Screenshot 2024-12-07 090556](https://github.com/user-attachments/assets/1a0a0dc7-f0f7-4c61-a15e-24c123157123)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

