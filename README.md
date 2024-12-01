### NAME: P. VISHAL
### REG.NO: 24901233
### EXPERIMENT-1: STUDY OF LOGIC GATES

### AIM 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

### EQUIPMENT REQUIREMENT

Software – Quartus prime 

### THEORY

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

### AND GATE

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

### OR GATE

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

### NOT GATE

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

## NAND GATE

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

### NOR GATE

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

### Ex-OR GATE

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

### Ex-NOR GATE

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

### PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM
```

module Logicgates(a,b,notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate);
input a,b;
output notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate;
not(notgate,a);
not(notgate,a);
not(notgate,a);
and(andgate,a,b);
or(orgate,a,b);
nand(nandgate,a,b);
nor(norgate,a,b);
xor(xorgate,a,b);
xnor(xnorgate,a,b);
endmodule
```
### TRUTH TABLE
![image](https://github.com/user-attachments/assets/eb62a46b-6e8a-4b02-8fc7-6caabe17b547)

### RTL OUTPUT
![WhatsApp Image 2024-12-01 at 11 07 29_b123e890](https://github.com/user-attachments/assets/129b9834-2abe-4fae-a605-884653daa240)

### OUTPUT WAVEFORM
![WhatsApp Image 2024-12-01 at 11 07 50_892ceada](https://github.com/user-attachments/assets/591b4e1c-49a5-4c8f-b820-6f21416344ff)

### Result
Studied and verified the truth table of logic gates in Quartus II using Verilog programming sucessfully

