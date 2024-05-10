# Efficient quantum algorithms for stabilizer entropies
Program to efficiently compute stabilizer entropy with quantum computers. 

Python code to measure stabilizer entropy (SE) using two copies of a state in the Bell basis. Simulates various states with optional depolarizing noise and finite number of measurements. Runs on qiskit.

Companion Code for "Efficient quantum algorithms for stabilizer entropies" by T. Haug, S. Lee and M.S. Kim (arXiv:2305.19152) 

@Tobias Haug, Imperial College London
@Soovin Lee, Imperial College London

This code measures SEs using two copies of a state in the Bell basis. It implements three algorithms:

1. Measure SE via Bell measurements (efficient for odd n)
2. Measure SE via Bell measurements on complex conjugate, followed by Pauli measurements (efficient for integer n>1)
3. Gradients of SEs via Bell measurements (efficient for odd n)

As comparison, also computes exact SE using statevector simulator. Also can simulate depolarizing error and correct it via error mitigation.

Requirements: Python, Qiskit

