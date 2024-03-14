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
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/35941858-10b9-42e9-8806-14bae87f3a05)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/f5da4608-5fc2-4c3c-b93d-aeb73230ae5b)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/592c182a-f29c-4618-a31e-1dd2c508a0be)

 Developed by:swathi.s
 RegisterNumber: 212223040219
 
**Logic symbol & Truthtable**
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/cf474a6b-237b-43cc-a6fd-1f57c17e300b)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/f77fb20a-eec0-4a51-b822-6256639c00ee)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/84d50958-2264-4a2a-a57e-699214768e46)
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/2228b30c-9b7f-4741-adad-8a22fdb437e4)




**RTL realization Output:** 
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/777c714a-9335-415a-9147-00c277b12140)




**RTL**
![image](https://github.com/swathisiva212/study-of-basic-gates/assets/155249892/231fd906-11e1-4828-af4b-4699770a1be5)

**Result:**
hence the output was verified sucessfully.

