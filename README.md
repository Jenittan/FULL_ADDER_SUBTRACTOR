**NAME:JENITTAN JOSE J B**

**REG NO:24006462**

**EXP NO 4:FULLADDER AND FULLSUBTRACTOR**

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**FULLADDER AND FULLSUBTRACTOR**

**FULL ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**FULL SUBTRACTOR**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTHTABLE**

**FULL ADDER**

![Screenshot 2024-12-26 103724](https://github.com/user-attachments/assets/d6dc2e46-66f8-4fdd-a936-a14ce5a53da7)


**FULL SUBTRACTOR**

![Screenshot 2024-12-26 103938](https://github.com/user-attachments/assets/f9b04c06-0edc-4407-854a-dbebce419d75)



**PROGRAM:**

![Screenshot 2024-12-26 103947](https://github.com/user-attachments/assets/951684fc-55f9-473f-8e92-2e685f06f9e8)


**RTL VIEWER**

![Screenshot 2024-12-26 103953](https://github.com/user-attachments/assets/3db7ab67-a8dd-487e-a0cd-3bc213e2571f)



**OUTPUT TIMING WAVEFORM**

![Screenshot 2024-12-26 104007](https://github.com/user-attachments/assets/4c460c48-2aaa-4aea-b0cb-5b4258b189d4)


**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



