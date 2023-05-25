# Efficient measurement of stabilizer entropy with quantum computers
Program to efficiently compute stabilizer entropy with quantum computers. 

Python code to measure stabilizer entropy (SE) using two copies of a state in the Bell basis. Simulates various states with optional depolarizing noise and finite number of measurements. Runs on qiskit.

Companion Code for "Efficient stabilizer entropies for quantum computers" by T. Haug, S. Lee and M.S. Kim 

@Tobias Haug, Imperial College London
@Soovin Lee, Imperial College London

This code measures Tsallis SE using two copies of a state in the Bell basis. It implements three algorithms:

1. Measure SE via Bell measurements (efficient for odd n)
2. Measure SE via Bell measurements on complex conjugate, followed by Pauli measurements (efficient for integer n>1)
3. Gradients of SES via Bell measurements (efficient for odd n)

As comparison, also computes exact SE using statevector simulator. Also can simulate depolarizing error and correct it via error mitigation.

Requirements: Python, Qiskit

