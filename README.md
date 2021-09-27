# QOSF screening tasks

This repository holds my code for the screening tasks of the Quantum Open Software Foundation's Mentorship Program. You can read more about the QOSF and the Mentorship Program here: <https://qosf.org/qc_mentorship/>.

Although I've only done task 2, which is the one I'm submitting, I plan to try the other three tasks someday. If I do so, they'll be uploaded here.

## Task 2

Task 2 contains a variational quantum circuit I made on Qiskit that maps a randomly generated set of four 4-qubit input states to four 4-qubit output states, creating a parameterized circuit whose parameter values are improved over time. There's lots of room for improvement, if you try the code and find something that could make it better feel free to open a pull request.

This circuit is based on the hybrid quantum-classical framework DDQCL (Data-Driven Quantum Circuit Learning) designed by Benedetti et al. in '*A generative modeling approach for benchmarking and training shallow quantum circuits*' which can be accessed here: <https://www.nature.com/articles/s41534-019-0157-8>.
