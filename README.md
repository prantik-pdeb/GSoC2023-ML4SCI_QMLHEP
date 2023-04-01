# Equivariant quantum neural networks for High Energy Physics Analysis at the LHC

## Description:

The ambitious HL-LHC program will require enormous computing resources in the next two decades. New technologies are being sought after to replace the present computing infrastructure. A burning question is whether quantum computer can solve the ever growing demand of computing resources in High Energy Physics (HEP) in general and physics at LHC in particular. Our goal here is to explore and to demonstrate that Quantum Computing can be the new paradigm (Proof of Principle).

Discovery of new physics requires the identification of rare signals against immense backgrounds. Development of machine learning methods will greatly enhance our ability to achieve this objective. However, with this ever-growing volume of data in the near future, current machine learning algorithms will require large computing resources and excessive computing time to achieve good performance. Quantum Computing in Qubit platform, where qubits are used instead of bits in classical computer, has the potential to improve the time complexity of classical algorithms.

With this project we seek to implement Quantum Machine Learning methods for LHC HEP analysis based on e.g. the Pennylane framework. This will enhance the ability of the HEP community to use Quantum Machine Learning methods.

## Tasks:
Task I: Quantum Computing Part 
1) implement a simple quantum operation with Cirq or Pennylane
a) With 5 qubits 
b) Apply Hadamard operation on every qubit 
c) Apply CNOT operation on (0, 1), (1,2), (2,3), (3,4) 
d) SWAP (0, 4) 
e) Rotate X with pi/2 on any qubit 
f) Plot the circuit 
2) Implement a second circuit with a framework of your choice:
Apply a Hadmard gate to the first qubit
rotate the second qubit by pi/3 around X
Apply Hadamard gate to the third and fourth qubit
Perform a swap test between the states of the first and second qubit |q1 q2> and the third and fourth qubit |q3 q4>

Task II: Classical Graph Neural Network (GNN) 
For Task II, you will use ParticleNet’s data for Quark/Gluon jet classification available here with its corresponding description. 
● Choose 2 Graph-based architectures of your choice to classify jets as being quarks or gluons. Provide a description on what considerations you have taken to project this point-cloud dataset to a set of interconnected nodes and edges. 
● Discuss the resulting performance of the 2 chosen architectures. 


Task III: Open Task 
Please comment on quantum computing or quantum machine learning. You can also comment on one quantum algorithm or one quantum software you are familiar with. You can also suggest methods you think are good and you would like to work on. Please use your own understanding. Comments copied from the internet will not be considered.

Task VII: Equivariant quantum neural networks
In this task you are supposed to get started with equivariant quantum neural networks by implementing a Z_2 × Z_2 equivariant quantum neural network. Z_2 is a symmetry group an as an example we will generate a simple classical dataset which is respects the Z_2 x Z_2 symmetry.
This example is explained in the paper https://arxiv.org/abs/2205.06217 and additional background can be found in https://arxiv.org/abs/2210.08566. 
a) Generate a classification dataset with two classes and two features x_1 and x_2 which respects the Z_2 x Z_2 symmetry (this corresponds to mirroring along y=x). An example can be found in the first reference paper.
b) Train a QNN to solve the classification problem.
c) Train an Z_2 x Z_2 equivariant QNN to solve the classification problem and compare the results.
