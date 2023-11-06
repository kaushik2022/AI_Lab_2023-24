# Ex.No: 7  Logic Programming –  Logic Circuit Design                                           

### DATE:02.09.2023
### REGISTER NUMBER : 212222040074
### AIM: 
To write a logic program to design a circuit like half adder and half subtractor.
###  Algorithm:
1. Start the Program
2. Design a AND gate logic if both inputs are 1 then output is 1.
3. Design a OR gate logic if any one of input is 1 then output is 1.
4. Design a XOR gate logic if both inputs are different then output is 1.
5. Design a NOT gate logic if input is 0 then output is 1.
6. Design a half adder and half subtractor using the rules.
7. Test the logic.
8. Stop the program.

### Program:
% Define the XOR gate xor(0, 0, 0). xor(0, 1, 1). xor(1, 0, 1). xor(1, 1, 0).

% Define the AND gate and(0, 0, 0). and(0, 1, 0). and(1, 0, 0). and(1, 1, 1).

% Define the NOT gate not(0, 1). not(1, 0).

% Define the half-subtractor circuit half_subtractor(A, B, Diff, Borrow) :- xor(A, B, Diff), not(B, NotB), and(A, NotB, Borrow).

% Define the half-adder circuit half_adder(A, B, Sum, Carry) :- xor(A, B, Sum), and(A, B, Carry).

### Output:

![image](https://github.com/kaushik2022/AI_Lab_2023-24/assets/129837020/9205d3c8-10c3-492a-8311-cd485dbd484e)



### Result:
Thus the truth table of circuit verified sucessfully.












### Output:



### Result:
Thus the truth table of circuit verified sucessfully.
