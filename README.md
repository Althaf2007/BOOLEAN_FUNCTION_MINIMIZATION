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
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module project3333(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2 = ((~y & z) | (x & y) | (w & y));
endmodule
Developed by: RegisterNumber:24005994


**RTL realization**
**Output:**
LOGIC DIAGRAM
![Screenshot 2024-11-18 084919](https://github.com/user-attachments/assets/3c3e7759-748b-4191-840a-c056cbefad3f)


**RTL**
**Timing Diagram**
![Screenshot 2024-11-18 084840](https://github.com/user-attachments/assets/110c5e8f-0a72-45f8-bec8-c8eb17cb3fe1)


**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

