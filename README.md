# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-22 at 10 35 37_acd88bfa](https://github.com/user-attachments/assets/4e66d394-3982-4b36-8186-e08cdb8e327d)





**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~ b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: DHARSHINI S RegisterNumber: 24900238*/


**RTL realization**
![image](https://github.com/user-attachments/assets/54757286-f823-456b-b96b-3db834efa80e)





**Timing Diagram**
![Screenshot 2024-11-12 102020](https://github.com/user-attachments/assets/254bd6b4-3485-44c2-9126-ff5ee5bf9785)

**Result:** 

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

