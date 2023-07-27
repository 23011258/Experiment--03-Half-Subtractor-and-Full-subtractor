### NAME: YENDLURI CHANDANA
### REGISTER NUMBER: 23011258
# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin
### procedure:

### program of full subtractor :


![Screenshot (28)](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/3eb8219d-ba2c-4042-aad5-0e120744feae)

### Truthtable of full subtractor:
![image](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/711134b8-19ed-4719-82d3-ecf96c3895b7)



## Program of half subtractor:
![Screenshot (26)](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/91f0014b-877f-4ec9-93ec-7756d03f7725)





## Truthtable for halfsubtractor
![image](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/8d89d60d-b41e-4ddb-89e8-e50865d19093)


### Timing diagram for full sub:
![image](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/2ea3f74d-1c83-4aca-9731-9b0fae8dcd6a)
### RTL REALIZATION FOR FULLSUB:
![image](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/55b2b690-65fc-40ac-8859-ef0a645a3679)


##  RTL realization for half sub
![image](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/278ef179-41f7-41a5-b16a-36997114c31c)



## Timing diagram for half sub
![image](https://github.com/23011258/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139842204/fcf1f47f-e55f-48f2-8309-b1fc470e5f8b)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
