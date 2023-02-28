# QHack2023

**Project Description**
This VQE is used to run a 5 qubit model of BeH2 and determine the ground state energy within chemical accuracy on a noiseless simulator. Noisy 6 qubit model results are also included in the Jupyter Notebook. We have also evaluated the accuracy of this model for varying bond distance in the molecular geometry, indicating greater accuracy as bond distance increases, and an ideal bond distance of approximately 1.3 Angstrom. This works lays the groundwork for more efficient simulation on a real QPU in the NISQ era, with as few as 5 qubits. 


**Contributors**
Bartosz Tomsia, Grant Costa, Tyler Cowan


**How to run the code on Google Colaboratory:**

1. Open QHack2023_submission.ipynb in Google Colaboratory 
2. Runtime --> Run all. The code blocks until section "Bond Distance Data Collection" will take approximately 5 minutes to run on a laptop.
3. The remaining code blocks will take approximately 30-40 minutes, and constitute analysis of our VQE model. 

The code can be run in Google Colab or on qBraid. We found qBraid to be approximately twice as fast. 

**Qbraid Instructions:**

Same as Google Colaboratory, except do installation in the first codeblock via :
 %pip install qiskit qiskit-nature[pyscf] pylatexenc --quiet

instead of 
!pip install qiskit qiskit-nature[pyscf] pylatexenc -U --quiet



**References for this project**


[1] https://github.com/Qiskit-Partners/mapomatic
[2] https://pennylane.ai/qml/demos/tutorial_mol_geo_opt.html
[3] https://arxiv.org/abs/2111.05176
[4] https://qiskit.org/documentation/partners/qiskit_ibm_runtime/how_to/error-suppression.html 
[5] https://mitiq.readthedocs.io/en/stable/examples/simple-landscape-qiskit.html
[6] https://pennylane.ai/qml/demos/tutorial_error_mitigation.html#mitigating-noisy-circuits-in-quantum-chemistry
[7] https://qiskit.org/documentation/nature/howtos/adapt_vqe.html
[8] https://github.com/qulacs/Quantaggle_dataset/blob/master/datasets/Small_Molecules_1/README.md
[9] https://arxiv.org/abs/1704.05018
[10] https://arxiv.org/abs/2203.14756
[11] https://qiskit.org/textbook/ch-applications/vqe-molecules.html
[12] https://github.com/aws/amazon-braket-examples/blob/main/examples/hybrid_jobs/4_Embedded_simulators_in_Braket_Jobs/Embedded_simulators_in_Braket_Jobs.ipynb
[13] https://pennylane.ai/qml/demos/tutorial_qubit_tapering.html
[14] https://medium.com/qiskit/qiskit-nature-0-5-toward-quantum-centric-supercomputing-in-the-realm-of-natural-sciences-a2fe854737cf
