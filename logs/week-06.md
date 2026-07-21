# Week 6

**Dates:** 07-06 to 07-10

## Goals
Learn how engineered TNBC features can be encoded into qubits.
Understand how classical patient data maps to qubit rotations.
Select one TNBC feature and demonstrate its quantum encoding.
Connect quantum encoding to the A-QLSTM-A architecture.
Prepare a 20–25-minute presentation explaining the process.


## Approach and Implementation
I selected a TNBC feature that stood out the most was tumor size. I normalized its values and mapped them to rotation angles. I then used Qiskit to apply an R
y rotation gate and visualize how the feature changes the qubit’s state on the Bloch sphere. I also researched how quantum-encoded features can be used as inputs in the A-QLSTM-A architecture

## Results
I learned that a classical TNBC feature can be represented by a qubit rotation. Different feature values create different rotation angles and quantum states. I prepared slides explaining the feature, normalization process, quantum circuit, Bloch sphere, and connection to A-QLSTM-A.


## Notes
The final feature values depend on the completed shared dataset. All values must be normalized consistently before they are encoded. This week’s work helped me understand how classical medical information can be prepared for a hybrid quantum-classical model.

