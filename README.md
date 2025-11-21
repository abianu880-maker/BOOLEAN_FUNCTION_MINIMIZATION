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

Developed by:Abilasha RegisterNumber:25015770





module ex2 (
    input  wire A,
    
    input  wire B,
    
    input  wire C,
    
    input  wire D,
    
    output wire F
    
    );
assign F = (~A & B) | (C & D) | (A & ~D);
endmodule




**RTL realization**
<img width="986" height="772" alt="Screenshot 2025-11-21 182943" src="https://github.com/user-attachments/assets/548119f7-ef51-49c9-bffe-cc044bd82881" />

**Output:**
<img width="1305" height="304" alt="Screenshot 2025-11-21 183133" src="https://github.com/user-attachments/assets/a6395503-aefa-441b-868c-6a094e492225" />

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

