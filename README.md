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

## Procedure



Write the detailed procedure here 


## Program:
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:BHARATHI M K 
RegisterNumber:  23010873
*/

## CODE:
Half subtractor:

![hs code](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/5ee03e3f-2160-4bdf-8848-da4bb6672aef)

Full subtractor:

![fs code](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/dc1c547e-5704-4ee1-a8fb-67dd8dd1c099)

## Truthtable
Half subtractor:

![WhatsApp Image 2023-11-26 at 15 49 21_95ed5f5f](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/8b6e2ffa-9953-46d6-83af-fdeac411427d)

Full subtractor:

![WhatsApp Image 2023-11-26 at 15 49 27_b1a79637](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/d7411108-2026-4f26-aa33-0be3abf73a6e)

##  RTL Diagram:
Half subtractor:

![hs rtl](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/ebd266e9-e08b-4aee-b35b-e9be97211d77)

Full subtractor:

![fs rtl](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/d98189dc-ab7f-4c2a-9791-4cde35839e84)

## Output:
Half subtractor:
![hs wf](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/ed423ced-c96f-4c8e-ba88-92f1f18b8058)

Full subbtractor:
![fs wf](https://github.com/BHARATHI20MK/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474125/909ee0f6-2e93-40b3-9a96-d7ceac969f60)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
