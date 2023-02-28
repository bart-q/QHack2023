# QHack2023

**Project Description**
This VQE is used to run a 5 qubit model of BeH2 and determine the ground state energy within chemical accuracy on a noiseless simulator. Noisy 6 qubit model results are also included in the Jupyter Notebook. We have also evaluated the accuracy of this model for varying bond distance in the molecular geometry, indicating greater accuracy as bond distance increases, and an ideal bond distance of approximately 1.3 Angstrom. This works lays the groundwork for more efficient simulation on a real QPU in the NISQ era, with as few as 5 qubits.


**How to run the code on Google Colaboratory:**

1. Open VQE Qiskit.ipynb in Google Colaboratory 
2. Runtime --> Run all. The code blocks until section "Bond Distance Data Collection" will take approximately 10 minutes to run on a laptop.
3. The remaining code blocks will take approximately 30-40 minutes, and constitute analysis of our VQE model. 

The code can be run in Google Colab or on qBraid. We found qBraid to be approximately twice as fast. 

Qbraid Instructions:

Same as Google Colaboratory, except do installation in the first codeblock via :
 %pip install qiskit qiskit-nature[pyscf] pylatexenc --quiet

instead of 
!pip install qiskit qiskit-nature[pyscf] pylatexenc -U --quiet
