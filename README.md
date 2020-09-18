In this repository I keep all pieces of code I showed during my speech on International School on Quantum Computing 2020 by RQC.
This repository includes:
1. [Tensors in TensorFlow](https://colab.research.google.com/github/LuchnikovI/RQC_School_Rapid_prototyping/blob/master/1_Tensors_in_TensorFlow.ipynb)
2. [Optimization of spin echo](https://colab.research.google.com/github/LuchnikovI/RQC_School_Rapid_prototyping/blob/master/2_Optimization_of_spin_echo.ipynb)
3. [Ground state search with automatic differentiation](https://colab.research.google.com/github/LuchnikovI/RQC_School_Rapid_prototyping/blob/master/3_Ground_state_of_spin_chain.ipynb)
It aslo includes slides of my presentation.

In the first jupyter notebook I introduce the basics of work with tensors in TensorFlow, including initializations of tensors, indexing, reshaping and transposing of tensors, element wise operations with tensors, linear algebra, broadcasting, etc. The first notebook also includes couple of simple physical examples such as taking of the partial trace of a density matrix and expressing of tensor product by using broadcasting. In the first notebook I also apply TensorFlow to simulate spin echo.

In the second notebook I apply automatic differentiation (AD), that is a part of TensorFlow, to find a control signal that gives a stronger revival of a signal at the end.

In the third notebook I apply AD based optimization to find the ground state of the Transverse Field Ising model.
