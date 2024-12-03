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

 module
 experiment2(A,B,C,D,f1,w,x,y,z,f2);
 input A,B,C,D,w,x,y,z;
 output f1,f2;
 assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
 assign f2=((~y&z)|(x&y)|(w&y));
 endmodule


Developed by:Deepika.V
RegisterNumber:24000724


**RTL realization**
![Screenshot (75)](https://github.com/user-attachments/assets/bc733abd-29dc-4444-b977-928eebe4fd32)


**Output:**

**RTL**
![Screenshot (77)](https://github.com/user-attachments/assets/ad469786-51c0-4876-a8a6-4951ecae2c01)


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

