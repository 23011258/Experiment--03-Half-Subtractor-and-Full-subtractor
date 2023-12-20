### NAME: YENDLURI CHANDANA
### REGISTER NUMBER: 23011258
# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
### procedure:
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 

Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

 

### program of full subtractor :



![WhatsApp Image 2023-12-18 at 16 18 28_dc10a6cc](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/86ae8254-d13a-4b2a-99a6-0c0c656047d6)

### Truthtable of full subtractor:

![WhatsApp Image 2023-12-20 at 23 21 13_a9d03e36](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/04c17193-ea17-4621-b445-b989d08297e6)


## Program of half subtractor:




![WhatsApp Image 2023-12-18 at 16 18 28_c5def574](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/c89addd7-e870-482e-8102-eaca4d7cfdbe)


## Truthtable for halfsubtractor


![WhatsApp Image 2023-12-20 at 23 21 55_006c7568](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/e901f844-9dc4-41bb-b870-55e749f836b2)

### Timing diagram for full sub:

![WhatsApp Image 2023-12-20 at 23 21 13_e8d23ead](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/06c3c43f-3329-4a22-8f2c-c7d0545d46eb)


### RTL REALIZATION FOR FULLSUB:
![WhatsApp Image 2023-12-20 at 23 21 13_346e0950](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/4c3ca254-1853-4d43-ae8b-a6e292a4ed6d)


##  RTL realization for half sub

![WhatsApp Image 2023-12-20 at 23 21 36_caac7557](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/22608b3a-921e-4f38-8532-b3cbbe5977e2)



## Timing diagram for half sub


![WhatsApp Image 2023-12-20 at 23 21 38_95fc84f7](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/df7491cf-ddc0-4c4d-8f0b-e60122597c8b)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
