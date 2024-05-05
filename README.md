# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

***Half Adder***
**Program:**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/b1a4cf95-9a40-4224-8e5c-bf0201525c4a)

Developed by:ABISHAI K C RegisterNumber:212223240002

**RTL Schematic**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/20e1b5fb-8428-482b-b9f5-151c87e6d1c2)

**Truthtable**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/986f0296-a721-4056-9638-32f7e0ddcbbc)

**Output/TIMING Waveform**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/0d5f3aef-d813-4d6b-83e3-fb9ed8f9e3c7)

**HALF SUBTRACTOR**
**Program**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/a1c56c7b-e496-45f5-afb6-de3e56c9647a)


**RTL Schematic**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/9380b318-90d3-4b4a-b226-f43917a2a2ff)

**Truthtable**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/378b4776-cce3-4ce7-8cdb-8e0e8993a90a)

**Output/TIMING Waveform**

![image](https://github.com/Abishai95141/HALF_ADDER_SUBTRACTOR/assets/139335314/42353123-68dd-4bf2-b22d-83ca1856a48f)

**Result:**
The code is excecuted successfully.
