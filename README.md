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
```
module exper2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by:S.Sathya Priyan RegisterNumber:*/212225230255

**RTL realization**
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/71f48bf3-0726-423b-85b3-613a4eba9d04" />

**Output:**
**RTL**
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/b63b85fa-1ded-47ed-b16b-bb0a964a4b50" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

