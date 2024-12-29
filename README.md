# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions  


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Hemalatha.R
RegisterNumber:24901252

module

experiment2(A,B,c<d<f1,w,x,y,z,f2);

input A,B,C,D,w,x,y,z;

assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));

assign f2=((~y&z)|(x&y)|(w&y));

end module

**RTL**

![image](https://github.com/user-attachments/assets/4f524c4c-c4dd-47c2-bcfb-ae2c97253cb8)

**OUTPUT **
![image](https://github.com/user-attachments/assets/28059130-78d0-42ab-81ce-db4d4f9b3093)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

