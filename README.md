

# Implementation-of-Half-Adder-and-Full-Adder-circuit

### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: MERCY A

RegisterNumber: 23012506 

*/ 
# Half Adder:

![ha coding](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/bb562efc-75da-4a47-a9d7-0d5c0e530547)


# Full Adder:

![full coding](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/0aec15ae-7b99-4e3e-8fa5-0568110ebb38)


# Logic symbol & Truthtable:

Half Adder:

![Screenshot 2023-11-28 134040](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/2d6f1832-c884-468f-92c6-bd72b65f15c2)

Full Adder:

![Screenshot 2023-11-28 134057](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/9ca1d38d-6311-4f73-8591-82304f55acdd)



# RTL realization

Half Adder:


![ha diagram](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/ce858fc7-21b6-4c6a-a137-fb75bfd4c3bb)



Full Adder:


![full diagram](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/dde23d00-4bb4-4d00-a9ac-7695ced7b6eb)




### Output:

### TIMING DIAGRAM:

Half Adder:


![ha wave](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/8800fca6-efbc-486b-bf70-1fa6e467e691)


Full Adder:

![full wave](https://github.com/mercyarulappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149233730/8e5e3603-f28b-4b29-b097-d7c85ab1c116)







### Result:
