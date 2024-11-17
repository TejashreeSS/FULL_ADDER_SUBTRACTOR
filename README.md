### NAME:TEJASHREE S S
### REG NO:24900167
### EXPERIMENT 4:FULL ADDER AND SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM:
To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED:
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# FULL ADDER AND SUBTRACTOR:

# FULL ADDER:
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# Figure -1 FULL ADDER

# FULL SUBTRACTOR:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# TRUTH TABLE:
![TRUTH TABLE FOR EX4](https://github.com/user-attachments/assets/c1f6c943-f462-4582-8ebd-e945a82ae6d5)

# PROCEDURE:

1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram.
# PROGRAM:

![program ex4](https://github.com/user-attachments/assets/bc6f2a95-f944-4fcb-94fa-c3fd379c4cec)


# RTL OUTPUT:
![rtl output exp4](https://github.com/user-attachments/assets/191879b2-465c-4e71-9046-0ddc00ef6217)

# OUTPUT WAVEFORM:
![waveformex4](https://github.com/user-attachments/assets/084240df-435a-4f27-9460-eb33ccf4fe6d)

# RESULT:

Studied and verified the Full Adder and Full Subtractor circuits and their truth tables using Quartus software successfully.



