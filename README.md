# Cluster_Decoder
Decoder for Cluster Decoding to be used with Qiskit Ignis and Qiskit.

This decoder was theorised by Dr. James Robin Wootton, IBM Researchm, Zurich in his paper "Getting the public involved in Quantum Error Correction" (https://arxiv.org/pdf/1712.09649.pdf)

To use this decoder, follow the steps given below:

1. Clone the qiskit-ignis repository
  ``git clone https://github.com/Qiskit/qiskit-ignis.git``
2. Replace the fitters.py file in qiskit-ignis/qiskit/ignis/verification/topological_codes/ with fitters.py here. 
3. Run ``python setup.py install``.

Check the decoder file for a tutorial on how to use it. 
