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
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/265a22d3-a695-44bb-a98c-bd80e4ef3810)

# Logic symbol & Truthtable
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/510a4e35-7524-4a82-8bae-8c5d394c40f1)

# RTL
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/878a1790-9e0a-417a-98ce-a2101ecde0c2)

# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/933ad5d1-ca08-4993-9997-531d4c7a0b58)


# OR GATE:
# program:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/12c6e1a6-b9c7-4ada-a46a-9b1051865339)

# Logic symbol & Truthtable:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/4443ffea-c435-485a-aa68-27d6e2280bf8)

# RTL:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/d532f000-15d8-4c3c-ae88-a265b9c0a31f)

# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/2e21a149-4379-4453-8c6b-2cf4a5ec22e3)

# NOT GATE:
# program:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/dba2e657-3737-4723-bcbf-540499624927)

# Logic symbol & Truthtable:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/1596a5f6-776a-4d15-a190-324bb4e0e37f)

# RTL:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/35a374ab-5dc5-4ca4-9926-45c1c00c3c87)


# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/23edfc61-837a-4dab-bd7e-a2148abaa7f6)

# NAND GATE:
# program:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/39a246d2-1550-46eb-8fdb-03f1f648bfab)

# Logic symbol & Truthtable:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/308148f8-3c10-40be-9e20-add3c21d043c)

# RTL:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/e5bde3a5-4013-4ecf-bc40-64b7dfe59008)


# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/8ba23291-055c-41eb-85d1-ea932a205758)

# NOR GATE:
# program:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/749955c6-a391-4319-8534-cdf250f1a96c)

# Logic symbol & Truthtable:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/a4ec44ad-8c03-451d-a426-7d8cf78adcad)

# RTL:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/0f2c7450-0a1a-459b-8d62-3a3ad71c0764)

# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/bbc02c0a-a26f-4f57-b050-3dd73571c213)

# EX-OR GATE:
# program :
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/6a225470-2247-4499-aa57-156c4c212ecb)

# Logic symbol & Truthtable:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/782c0c17-0d95-4547-8a7c-e4fc42169c03)

# RTL:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/91aa35c3-bdab-4f63-8ecf-920d4a1f4189)

# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/d265fb3d-e225-40ac-967a-87e994482ede)

# EX-NOR:
# program:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/d802200c-e13d-40be-9b2f-5113634d2f8e)

# Logic symbol & Truthtable:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/e355a3a9-8951-4059-a91f-98187d162529)

# RTL:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/0479442a-4306-4e3e-8aef-1ca5219e4fe5)

# RTL realization Output:
![image](https://github.com/karthikeyanpachiyappan/study-of-basic-gates/assets/155143878/712e2521-11c2-42ec-9125-ae70ae16acc2)

# Result:
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified
