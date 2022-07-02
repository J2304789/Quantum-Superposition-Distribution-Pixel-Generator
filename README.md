# Quantum Superposition Distribution Pixel Generator

### Developed by:

 - Muhammad Jawwad Javeed Iqbal [[Linkedin](https://linkedin.com/in/jawwad-javeed/)]


## 📚 Table of Contents

* [Project Purpose](#-project-purpose)
* [About](#-about)
* [Required Environment Installations](#-required-environment-installations)

## 📘 Project Purpose

The ability to specify Quantum Superposition Distributions (P(|0>) and P(|1>)) of a Qubit is effective for representing multiple complex states, an important attribute of Quantum computing that allows it to perform certain calculations more efficiently than a classical computer.

Currently however, it is difficult to specify a given probability distribution; for example, if the set distribution of P(|0>) and P(|1>) is selected to be 74%-26%,it would require trial and error in order to achieve the specific controlled rotation that would result in this Quantum Superposition Distribution(A demonstration of why simply entering a controlled rotation of a given percentage about a non-eigenstate axis would not work is available at [`Juypter_Notebook_Quantum_Superposition_Distribution_Generator_Demo.ipynb`](https://github.com/J2304789/Quantum-Superposition-Distribution-Generator/blob/main/Juypter_Notebook_Quantum_Superposition_Distribution_Generator/Juypter_Notebook_Quantum_Superposition_Distribution_Generator_Demo.ipynb))

This project aims to resolve this problem by using different Polynomial equations in order to predict the controlled rotations required for the specified Quantum Superposition Distribution and plot the visualization of the corresponding probabilities.

## 📄 About

Qiskit Program that can generate a specified Quantum Superposition distribution (P(|0>) and P(|1>)) by utilizing Polynomial equations and plot the visualization of the corresponding probabilities.

For this project it is recommended to use one of IBM's Quantum computers instead of a simulator in order to generate truly random numbers, however for testing purposes the [QASM Simulator](https://qiskit.org/documentation/stubs/qiskit.providers.aer.QasmSimulator.html#qasmsimulator) is the most accurate and similar to a real-life Quantum Simulator and is used as a proof of concept.


## 💻 Required Environment Installations

```
$ pip install Qiskit

``` 
