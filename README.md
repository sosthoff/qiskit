<blockquote>
Copy and paste from OneNote, blog post to follow
</blockquote>



What:
SDK providing the complete set of tools needed for interacting with quantum systems and simulators. Access to:
	- Circuits
	- Hardware
		○ C++ simulator backends for execution+noise
	- Algorithms
		○ Grover (Search)
		○ VQE (minimum eigenvalue)
		○ QAOA (Optimization)
		○ QSVM (Classification)
	- Noise Mitigation

Install:
 conda
	- open conda env
	pip install qiskit
	pip install 'qiskit[visualization]'
	

	
IBM Qiskit: https://quantum-computing.ibm.com/login
Quantum Glossary: Docs and Resources - IBM Quantum Experience
Operations glossary: https://quantum-computing.ibm.com/docs/iqx/operations-glossary
	
	
Reminder, vector multiplication:

Bit Manipulation:

Tensor Product:

Multiple cbit representation


Math qbit:
[■(a@b)]   where a  and  b are Complex numbers and |(|a|)|^2+ |(|b|)|^2=1
With superposition this means ,that there is an |(|a|)|^2 probability to result in 0 and a |(|b|)|^2 probability to result in 1

Dirac vector notation (2 values of 1 bit)[think of it as array, indexed from 0:  [0,1,2,3,4,5…]]


Unitary matrix: (real unitary  = orthogonal matrix)
	Has: -colums form orthonormal vectors (conjugate[imaginary *-1] transpose [1x3 => 3x1] = inverse) -- or 
	
	Preserves norms  => probability amplitudes
	Complex, Hermitian, and Unitary Matrices
	
	
	

Gates:

        NOT: 000 => 001
X q[0];


        (H)adamard gate: 000 => 000, 001
h q[0];
This gate is a pi rotation about the X+Z axis, and has the effect of changing computation basis from |0⟩,|1⟩|0⟩,|1⟩ to |+⟩,|−⟩|+⟩,|−⟩ and vice-versa.


Hadamard Initialization: Spread probability equally across all states: Quantum Instruction Set - Computerphile



Phase

T

CNOT (Quantum assembly)
If control is 1, flip target:
C =[■(1&0&0&0@0&1&0&0@0&0&0&1@0&0&1&0)]

Example:
C|10> =C((■8(0@1))  ⨂▒〖 (■8(1@0)) 〗)=[■(1&0&0&0@0&1&0&0@0&0&0&1@0&0&1&0)]∗[■(0@0@1@0)]= [■(0@0@0@1)]= (■8(0@1))  ⨂▒〖 (■8(0@1))=|11>〗






        Barrier:
barrier q;
Stops compiler from optimizing across

Real life application:
Variation eigensolver: https://www.youtube.com/watch?v=Xtye-b5HphEc
	- To solve chemical system force between molecules
	- State description of molecules => simulation



Continue: https://quantum-computing.ibm.com/docs/iqx/guide/introducing-qubit-phase & https://quantum-computing.ibm.com/docs/iqx/build-circuits

References:
Qiskit - https://qiskit.org/
Qiskit Documentation - https://qiskit.org/documentation/
Qiskit IBM Dev - https://developer.ibm.com/depmodels/quantum-computing/projects/qiskit/
Introduction to Quantum computing - https://csferrie.medium.com/introduction-to-quantum-computing-df9e1182a831



Resources:
Qiskit - YouTube - https://www.youtube.com/channel/UClBNq7mCMf5xm8baE_VMl3A
Quantum Computing for Computer Scientists (21:24) - https://www.youtube.com/watch?v=F_Riqjdh2oM



