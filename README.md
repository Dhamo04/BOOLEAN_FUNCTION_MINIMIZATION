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

```
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
Developed by:DHAMODHARAN S RegisterNumber:25009463
```


**RTL realization**

**Output:**
<img width="1535" height="729" alt="image" src="https://github.com/user-attachments/assets/9084374a-8fb4-4c21-9954-e9b13c76c923" />
<img width="1489" height="716" alt="image" src="https://github.com/user-attachments/assets/1dd9e717-6ed1-44b1-946a-c22a6045453b" />



**RTL**

**Timing Diagram**
<img width="1597" height="849" alt="image" src="https://github.com/user-attachments/assets/d166468e-9788-4d71-8e64-a4c8c26aaee4" />
<img width="1594" height="847" alt="image" src="https://github.com/user-attachments/assets/93860783-ba0b-472a-82ff-5c2a4aac9546" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

