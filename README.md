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

Developed by:Hemalatha.R
RegisterNumber:*/24901252

module exp2(a,b,c,d,w,x,y,z,f1,f2);

input a,b,c,d,w,x,y,z;

output f1,f2;

assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));

assign f2=((~y&z)|(x&y)|(w&y));

endmodule


**RTL realization**
![Screenshot (43)](https://github.com/user-attachments/assets/42997ab3-44c8-4c83-a743-15e62c76c7f4)

**Output:**

**RTL**

**Timing Diagram**
![Screenshot (44)](https://github.com/user-attachments/assets/b855ec71-49a2-407c-b3d4-15699e416a7c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

