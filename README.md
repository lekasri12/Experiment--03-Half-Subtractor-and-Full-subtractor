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
Developed by: LEKA SRI G
RegisterNumber: 212223100025 


## Output:
![286814959-675998da-6c6e-4585-9b05-5d57f67d408e](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/02f6266f-d007-4c18-bbff-2c60af08ab6d)
![286814884-753c3337-033b-443c-9356-12d04898d9a0](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/f989d4f6-476f-4526-9067-974ffbb7b487)


## Truthtable
![286815021-7698f76d-9fd5-4281-a957-b1c1d1456b02](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/1cf80c98-e735-4a78-bc4d-fc06ca3ee457)
![286815060-e57ffc4c-ff7f-491f-bc40-8830451b2644](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/f238bf17-00f0-4b2a-884b-a8826be7a1ed)

##  RTL realization
![286815151-9c03c8ad-c711-4284-8a10-1f5c447bda9e](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/52e6b847-1f41-4d09-8f9f-224df7a0675c)
![286815193-ed07fe5f-e061-4c0a-bdc4-25378e74390b](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/7a388afb-0864-412a-91fc-c130a35ce326)



## Timing diagram 
![286815261-cb37605e-2769-47de-bfaa-8efdf8714ba0](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/8002db4a-6d16-4ae4-a0d4-e571690fd91d)
![286815286-73092ebc-e14d-4267-8427-cf49c275044c](https://github.com/lekasri12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037427/9810e3e5-88a7-4b84-8502-e5e7f0227ab3)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
