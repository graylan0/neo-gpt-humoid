gray00:Can you give some examples of other math systems?
```Dave_TestBOT
 — 
Today at 3:32 PM
(See Quantifactors in computing for more of the details associated with the various physics laws in this section.) In this chapter, we will explore the application of these equations to several different computing technologies which make use of quantum phenomena: hardware architectures for both classical and quantum computing, quantum gates, quantum algorithms, quantum cryptography, quantum sensing, quantum teleportation, quantum error correction, and the quantum search algorithm. We will also show how our results can be used to model the physical process of how quantum phenomena appear and function, allowing researchers to further explore these phenomena through the incorporation of quantifactors as a new modeling tool. Many of these topics have already been covered by the authors in other popular books like Foundations of Quantum Computer Science (Addai, 1997) or Understanding Quantum Computing (Buhrman, 2017). 



A Quantum Circuit, a Classical Circuit, and a Quantum Gate

There are actually three types of circuits, but for the purpose of conceptual clarity, we will make a distinction. At first, we will discuss the circuit type and its function. The circuit can be a classical circuit (like a classical computer) or a quantum circuit (like a quantum computer), with a classical computer being the same as a classical circuit on paper, but a quantum computer being a quantum circuit with quantum devices such as an quantum gate. A quantum gate is an operation where one or more of the qubits in the circuit change to a lower energy state. The classical logic gates in computers are used to create and manipulate bits, which are the bits in quantum computing.  Quantum bits are the building blocks as well as the quantum information which can perform complex calculations. A single bit or qubit is either one of the lowest energy states or zero energy states. Bits require measurement and a series of operations in order to change their states to either one or zero. A quantum cir
cuit could be used to implement two or more bits that change states as an experiment to calculate a function or perform an operation. A quantum gate can either create a quantum gate in which each of the two or more qubits that make up the gate becomes the control and the other qubits become the target logic states, or create a quantum gate composed of either 2 or 3 qubits or a larger gate. For example, a two-qubit quantum gate can be implemented using three two-qubit circuits and a third qubit for the control and target logic input/outputs.  Quantum gates can be used to perform a gate operation such as a Hadamard gate or to control a quantum system (such as the controlled NOT gate for quantum control).

Quantum gates can play two roles for a quantum computer: storing quantum information and providing a measurement. They can be used to encode quantum information to provide information (measure) as well as to perform a gate operation that transforms quantum information for a measurement. For example, we will describe a qubit that is a logical bit in a two-qubit quantum gate by the state and the measurement operators for the qubit (a logical bit is just two qubits that when in the same state, are equivalent to each other, and therefore can be treated as identical, and an orthogonal basis in two Hilbert spaces is the basis in which to represent a logical bit). The two-qubit state can be represented by a vector of two states for each of the two qubits, and the measurement operator by two vectors each representing a different measurement result. It is the measurement that transforms the qubit state into a measurement result. When we perform a measurement we change the state of the qubit and produce two measurement results.

There are two types of operations that can be performed on a quantum computer: unitary operations that rotate quantum states; and probabilistic operations that can accept probabilistic outcomes instead of a single definitive outcome. The unitary op
eration which applies the probabilistic operation consists in a series of operations using different quantum devices such as a quantum gate or a set of qubits in the circuit. The unitary operation that controls the qubits in a circuit also applies a different operations to the qubits. A particular quantum gate or a quantum gate set uses a particular basis or representation of a qubit that is called the CNOT gate and can be represented as [0⊗0⊗1⊗−1] as it is shown in figure 1. The CNOT gate is defined by the rotation matrix that contains a product of two CNOT gates. CNOT gate is a special type of unitary gate that is defined using a basis that is called CNOT gate basis. There is always only one unitary operation that is used to create a CNOT gate.
```

```
For the CNOT gate circuit shown in figure 1, the operation on the qubit 1 is A1 ⊗ B1 then B2 ⊗ −B, where A1 = I and B1 = I⊗−1 and A2 = I and B2 = I⊗−1 and A3 = I and B3 = I and B4 = −I and A5 = −I and B5 = I and B6 = I, so the A1 ⊗ B1 = R6, B2 ⊗ −B = L6, A3 ⊗ B3 = L12 and D5 = –K and B5 ⊗ B6 = L10 which are represented by the CNOT gate basis R6 = I⊗−1L6 = I+1+1I⊗-1. By changing a particular qubit state or a measurement output we can change the outcome of the CNOT gate operation. Therefore the transformation between the CNOT gate basis R6  and the CNOT gate CNOT basis L12  is R6 = −I⊗L6 = I−1+1−1I⊗+1 =+1I⊗-1L12 = −R12.
```


Figure: CNOT gate basis from R6 to L12

The operation on qubit 2 is A2 ⊗ B2 then B3 ⊗, where A2 = I and B2 = I⊗−1 and A3 = I, B3 = I⊗−1. Both these qubits, A2 and A3, use the CNOT gate basis C2. The qubit state can be represented in two basis sets as CNOT gate basis C2  which is described by the following CNOT gate matrix L12  shown in figure 2 and C2 = R−2⊗L12  which is shown in figure 3.

Figure: Qubit state basis C2 from R−1⊗L to L

The probabilistic operation for a qubit is the operations that accept probabilistic outcomes. To accept a probabilistic outcome, one or more of the qubits of a gat
e must change to a different state,
