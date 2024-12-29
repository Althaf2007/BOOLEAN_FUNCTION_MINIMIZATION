# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Function Minimization is the process of reducing a Boolean expression to its simplest form without changing its functionality. This minimization reduces the number of gates and inputs required, optimizing circuit design.

Logic Gates: Fundamental building blocks like AND, OR, and NOT gates are used to implement Boolean expressions. Karnaugh Map (K-map): A graphical technique for minimizing Boolean expressions by grouping terms based on commonalities. The given Boolean functions can be minimized as follows:

F1 = A’B’C’D’ + AC’D’ + B’CD’ + A’BCD + BC’D The terms can be simplified using K-map techniques to reduce the complexity of the circuit. F2 = xy’z + x’y’z + w’xy + wx’y + wxy Similar simplification can be done for this function to reduce the gate count. The resulting minimized expressions are implemented using Verilog HDL and simulated on the Quartus Prime tool. The outputs can then be verified on an FPGA board (e.g., Cyclone II).

**Logic Diagram**

![Screenshot 2024-12-29 163009](https://github.com/user-attachments/assets/fd5cce8f-464b-416e-a93d-51eb52efc57c)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```

module project3333(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2 = ((~y & z) | (x & y) | (w & y));
endmodule

```

Developed by:K.Mohamed Althaf 

RegisterNumber:24005994

**Truth Table:**

![Screenshot 2024-12-26 141058](https://github.com/user-attachments/assets/a33fc5c2-ae29-4f8e-ae58-2880ab6556cd)


**F1 & F2 Solution:**

![f1](https://github.com/user-attachments/assets/7b1a859a-45cd-41cc-b996-75f511764f77)
![f2 so](https://github.com/user-attachments/assets/ccd00e86-f026-46c4-b775-56e3a3ace89c)

**Output:**

![Screenshot 2024-11-18 084919](https://github.com/user-attachments/assets/3c3e7759-748b-4191-840a-c056cbefad3f)


**Timing Diagram**

![Screenshot 2024-11-18 084840](https://github.com/user-attachments/assets/110c5e8f-0a72-45f8-bec8-c8eb17cb3fe1)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

