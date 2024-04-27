### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

# Developed by: karthikeyan P
# register no: 212223230102
# program:
![Screenshot 2024-04-10 141736](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/fdb2f0e6-5138-4cc9-87fc-40d7ba0cc7b2)
# Logic symbol & Truthtable
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/182e38e2-2b37-402a-8da5-28dc48bc319a)
# RTL
![Screenshot 2024-04-10 141851](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/667905fe-5ffe-4c35-a2d6-f162d46d3022)
# RTL realization Output:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/ace37a81-3ea9-49c4-ac84-27b5cb4d3c4c)

# OR GATE:
# program:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/f7954905-de5f-4c1d-a75b-49d213919c7c)
# Logic symbol & Truthtable:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/c9a08cd3-4d07-49d5-921d-5f08dc7fde53)
# RTL:
![Screenshot 2024-04-10 142121](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/63813683-0b1d-4f62-8531-bb82cadb9c1e)
# RTL realization Output:
![Screenshot 2024-04-10 142233](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/d5674ac5-af12-4fe2-b4ea-5313b97c0c49)
# NOT GATE:
# program:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/de1bb364-037c-473e-956b-48f1e94dfe5b)
# Logic symbol & Truthtable:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/a39d756f-2484-407f-ae30-f3f975875fb8)
# RTL:
![Screenshot 2024-04-10 142423](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/0ad19585-67c7-4078-8d29-c9d5ee269f27)

# RTL realization Output:
![Screenshot 2024-04-10 142456](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/14acd4b8-b3f2-4547-a1c1-d5e17489c5f6)
# NAND GATE:
# program:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/adf3d34c-d981-47c6-9e2f-de8622be50a4)
# Logic symbol & Truthtable:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/cbed160f-a538-4334-8d46-21408173b663)
# RTL:
![Screenshot 2024-04-10 143651](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/4ce4cded-8fda-41a7-8ce1-f85b5b9d5d47)

# RTL realization Output:
![Screenshot 2024-04-10 142754](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/fe613b4a-0e90-4f44-8747-91f1d7946e81)
# NOR GATE:
# program:
![Screenshot 2024-04-10 142915](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/a3f0e437-c54a-406f-bc49-8234f334b9a9)
# Logic symbol & Truthtable:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/6a3e27f1-da61-46b8-a520-321101b4badf)
# RTL:
![Screenshot 2024-04-10 143007](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/86b3b67d-0778-496f-9479-c6c89ac37159)
# RTL realization Output:
![Screenshot 2024-04-10 143015](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/c998769d-9113-415c-b887-440c2cb1b21b)
# EX-OR GATE:
# program :
![Screenshot 2024-04-10 143115](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/2bd5aab3-bd67-410c-b062-296ba8228c6f)
# Logic symbol & Truthtable:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/ee327dc3-8746-47dc-aef0-6de4ca243d0f)
# RTL:
![Screenshot 2024-04-10 143209](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/bac6e6a5-b6ba-4bdc-a731-61ad6e585c51)
# RTL realization Output:
![Screenshot 2024-04-10 143259](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/b59e30e5-d04e-401e-b19e-90a0be282ff0)
# EX-NOR:
# program:
![Screenshot 2024-04-10 143347](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/80eb5def-bf3b-4cbc-a7e4-80c4f0733742)
# Logic symbol & Truthtable:
![image](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/79428538-536e-4783-9eab-b3f951adb87d)
# RTL:
![Screenshot 2024-04-10 143442](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/daed8ac5-0055-41fa-9ebb-3e701350f7c7)
# RTL realization Output:
![Screenshot 2024-04-10 143525](https://github.com/Rsriram13/study-of-basic-gates/assets/145742823/5d05192d-d1f0-4408-afea-b94a0a0cd949)
# Result:
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified
