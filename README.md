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
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/d8bc7081-3ce7-4206-b6e1-78051d40eb8c)

Program for logic gates and verify its truth table in quartus using Verilog programming
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/830f7302-3960-4ca9-a7ac-f584aff7c2f5)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/1ccc094c-f6f8-4aa6-90d8-ec748641578e)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/df887818-a565-4101-96d9-8c6fc03c7780)

 Developed by:swathi.s
 RegisterNumber: 212223040219
 
**Logic symbol & Truthtable**
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/35059fea-6d92-48dd-9eb8-ddd568f6c5cf)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/d47dabb2-4206-4329-933b-17b2929f5323)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/0d3c6a9c-0114-4758-8d1a-0e62d2aea584)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/a98bdc8a-d522-4b25-b1cb-234c2b7c845e)

**RTL realization Output:** 
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/777c714a-9335-415a-9147-00c277b12140)

**RTL**
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/231fd906-11e1-4828-af4b-4699770a1be5)

**Result:**
hence the output was verified sucessfully.

