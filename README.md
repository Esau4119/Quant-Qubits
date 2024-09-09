# Quant-Qubits

Goal: 

 Create multiple versions of a circuit consisting of a single qubit,
apply various transformations to its quantum state to achieve specific
objectives, run the circuit using a quantum simulator running on your
local machine, obtain simulation results to visualize its quantum state, 
and reason about what is happening in the quantum program. 


Circuit #1:
A single qubit initialized to the |0> state
Add a measurement gate to the circuit
Execute the circuit using the Qiskit statevector simulator (aer_simulator_statevector or statevector_simulator)
Query the simulator results to obtain the state vector, and print out the state vector
Visualize the quantum state using a Bloch Sphere
Use Qiskit tools to create a diagram/drawing of the quantum circuit (see https://docs.quantum.ibm.com/build/circuit-visualization)



Circuit #2: 
A single qubit initialized to the |0> state
Apply a quantum gate that will transform the invert the quantum state, eg., from |0> to |1> or conversely from |1> to |0> 
Execute the circuit using the Qiskit statevector simulator (aer_simulator_statevector or statevector_simulator)
Query the simulator results to obtain the state vector
Visualize the quantum state using a Bloch Sphere
Query the simulator results to obtain then print out the values measured (e.g., counts)
Use Qiskit tools to create a diagram/drawing of the quantum circuit


Circuit #3:
A single qubit initialized to the |0> state
Apply a quantum gate that creates a state of superposition, e.g, equal probabilities of |0> and |1>
Execute the circuit using the Qiskit aer_simulator backend (aer_simulator)
Query the simulator results to obtain the state vector and counts
Visualize the quantum state using a Bloch Sphere
Make a histogram bar chart plot of the counts.
Use Qiskit tools to create a diagram/drawing of the quantum circuit



“Circuit’ #4:
A single qubit initialized to the |0> state
Apply one or more quantum gates such that the state vector, when plotted with a Bloch sphere, points towards the +Y axis. Remember the +z axis is at the North pole, and the x- and y-axes form a plane of zero latitude positioned at the equator. 
Hint: see  https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.QuantumCircuit and have a look at the gates that rotate about the x, y, and z axes.
Execute the circuit using the Qiskit statevector simulator (aer_simulator_statevector or statevector_simulator)
Query the simulator results to obtain the state vector
Visualize the quantum state using a Bloch Sphere


“Circuit” #5:  Construct a circuit that implements the Identity transformation
using N single-qubit gates where N is an arbitrary number >= 1, and the gates
may be any of those discussed in class lecture (or any gates listed in the Qiskit documentation 
