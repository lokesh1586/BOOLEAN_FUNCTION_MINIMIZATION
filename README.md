# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**
![WhatsApp Image 2024-12-08 at 19 50 52_1dbdabd4](https://github.com/user-attachments/assets/5b0e7b59-af77-4445-8057-db25e727cacf)





**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**<br>
module ex2(a,b,c,d,f1,w,x,y,z,f2);<br>
input a,b,c,d,w,x,y,z;<br>
output f1,f2;<br>
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));<br>
assign f2=((~y&z)|(x&y)|(w&y));<br>
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Lokesh M <br>RegisterNumber:*/24900227


**Output:**

**RTL**<br>
![Screenshot 2024-12-08 194353](https://github.com/user-attachments/assets/b8ecd81a-e538-4bf8-8e60-450f899c508f)


**Timing Diagram**
![Screenshot 2024-12-08 194251](https://github.com/user-attachments/assets/e64a8f86-7f67-4553-ad18-6512c4577001)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

