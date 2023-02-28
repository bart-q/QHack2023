# QHack2023

**Project name**

VQE of 5 qubit $BeH_{2}$ model

**Project Description**

This VQE is used to run a 5 qubit model of BeH2 and determine the ground state energy within chemical accuracy on a noiseless simulator. Noisy 6 qubit model results are also included in the Jupyter Notebook. We have also evaluated the accuracy of this model for varying bond distance in the molecular geometry, indicating greater accuracy as bond distance increases, and an ideal bond distance of approximately 1.3 Angstrom. This works lays the groundwork for more efficient simulation on a real QPU in the NISQ era, with as few as 5 qubits. 

**Contributors**

- Bartosz Tomsia, bart-q#6212
- Grant Costa
- Tyler Cowan, Tyy#5960


**How to run the code on Google Colaboratory:**

1. Open QHack2023_submission.ipynb in Google Colaboratory 
2. Runtime --> Run all. The code blocks until section "Bond Distance Data Collection" will take approximately 5 minutes to run on a laptop.
3. The remaining code blocks will take approximately 30-40 minutes, and constitute analysis of our VQE model. 

The code can be run in Google Colab or on qBraid. We found qBraid to be approximately twice as fast. 

**qBraid Instructions:**

Same as Google Colaboratory, except do installation in the first codeblock via :
`%pip install qiskit qiskit-nature[pyscf] pylatexenc --quiet`

instead of 
`!pip install qiskit qiskit-nature[pyscf] pylatexenc -U --quiet`

**References for this project**
1. "The Variational Quantum Eigensolver: a review of methods and best practices", Tilly et. al, [arXiv:2111.05176](https://arxiv.org/abs/2111.05176)
2. "Hardware-efficient Variational Quantum Eigensolver for Small Molecules and Quantum Magnets", Kandala et. al, [arXiv:1704.05018](https://arxiv.org/abs/1704.05018)
3. Qiskit tutorial: [Simulating Molecules using VQE](https://qiskit.org/textbook/ch-applications/vqe-molecules.html)
4. Pennylane tutorial: [Qubit tapering](https://pennylane.ai/qml/demos/tutorial_qubit_tapering.html)
5. Rossmanek article: [Qiskit Nature 0.5: Toward quantum-centric supercomputing in the realm of natural sciences](https://medium.com/qiskit/qiskit-nature-0-5-toward-quantum-centric-supercomputing-in-the-realm-of-natural-sciences-a2fe854737cf)
