# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
FULL ADDER:  ![Screenshot 2024-12-06 052625](https://github.com/user-attachments/assets/0559d323-2426-461c-b6dd-3d010801cd87)

FULL SUBTRACTER:  ![Screenshot 2024-12-06 054354](https://github.com/user-attachments/assets/f62d88fc-abbc-49bb-82bc-ad5b5e303a86)

**RTL Schematic**
FULL ADDER:  ![Screenshot 2024-12-06 053022](https://github.com/user-attachments/assets/e9db5f7e-bb8e-4d6f-9aaa-1cdca66c4a7a)

FULL SUBTRACTER:  ![Screenshot 2024-12-06 055055](https://github.com/user-attachments/assets/9d9bb097-4175-4bc9-87ea-98dd8d058a6b)


**Output Timing Waveform**
FULL ADDER:  ![Screenshot 2024-12-06 052604](https://github.com/user-attachments/assets/6d3e220b-c374-4841-a730-663259751826)

FULL SUBTRACTER:  ![Screenshot 2024-12-06 054744](https://github.com/user-attachments/assets/90d86641-7ae2-4683-9a36-1d606c544a06)


**Result:**
FULL ADDER:  ![Screenshot 2024-12-06 052644](https://github.com/user-attachments/assets/3b1c9620-6f8b-4b4b-881c-70bb21c54aed)

FULL SUBTRACTER:  ![Screenshot 2024-12-06 054820](https://github.com/user-attachments/assets/d28c3d92-b258-49df-8ca6-cb2877eff299)


Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



