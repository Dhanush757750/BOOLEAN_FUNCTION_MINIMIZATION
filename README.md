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
i)module EX_02(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii) module EX_02(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule
```
Developed by: RegisterNumber:212224040066


**RTL realization**
**Output:**
<img width="1920" height="1200" alt="Screenshot 2025-09-18 153015" src="https://github.com/user-attachments/assets/49ff4050-d9c5-4959-b416-b733fea301e2" />
<img width="1920" height="1200" alt="Screenshot 2025-09-18 152628" src="https://github.com/user-attachments/assets/e37c1336-2ded-4858-a00c-80bc0091858e" />

**Timing Diagram**
<img width="1920" height="1200" alt="Screenshot 2025-09-18 153131" src="https://github.com/user-attachments/assets/3325dfd8-8dc7-46aa-8e57-2f92bc20ce65" />
<img width="1920" height="1200" alt="Screenshot 2025-09-18 152749" src="https://github.com/user-attachments/assets/99a21cfe-5581-416c-87ae-842bac9ad71e" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

