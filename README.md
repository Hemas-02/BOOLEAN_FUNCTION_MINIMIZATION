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

i)
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule



Developed by: Hemalatha

RegisterNumber:24901252


**RTL**

![WhatsApp Image 2024-12-09 at 08 51 30_2547392f](https://github.com/user-attachments/assets/ac79ea05-c527-4b7f-b44c-0664d79b845d)

![WhatsApp Image 2024-12-09 at 08 51 30_cd6b2f58](https://github.com/user-attachments/assets/5152d00a-cc7c-4dbd-8c4e-6cc5388d74e3)



**OUTPUT **

![WhatsApp Image 2024-12-09 at 08 51 30_a41ea9bb](https://github.com/user-attachments/assets/17fcace8-ca1b-4e05-8230-cc5083b69415)

![WhatsApp Image 2024-12-09 at 08 51 30_10da5651](https://github.com/user-attachments/assets/793abf3b-d6c1-4605-941e-540aeabc2d41)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

