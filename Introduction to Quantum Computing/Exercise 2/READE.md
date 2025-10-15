# Exercise 2: Density Matrices, Entanglement, and Qubit Representations

## 1. Objective

This Jupyter Notebook provides Python implementations for a series of exercises covering the density matrix formalism, the properties of entangled states, qubit representations on the Bloch sphere, and an introduction to Quantum Key Distribution (QKD). The solutions demonstrate a strong, practical command of quantum information theory concepts using the `NumPy` library.

## 2. Key Concepts Demonstrated

This notebook showcases the ability to model and analyze various quantum systems and protocols:

* **Density Matrix Formalism:**
    * Verifying the purity of a quantum state using the condition `tr(ρ²) = 1`.
    * Validating the properties of a density matrix (Hermiticity, unit trace, and positive semi-definiteness).
    * Calculating the density matrix for a pure entangled state (Bell state).

* **Entanglement and Composite Systems:**
    * Performing the **partial trace** to find the reduced density matrix of a subsystem.
    * Constructing a **purification** of a mixed state into a larger pure state.
    * Defining the **Bell basis** and verifying its properties as a unitary transformation.
    * Calculating the expectation value of tensor product operators (`X ⊗ Z`) for each of the Bell states.

* **Quantum State Distance:**
    * Calculating the **fidelity** between two quantum states to quantify their similarity.

* **Single Qubit Representations:**
    * Converting a general single-qubit state `|Ψ(θ, φ)⟩` into its corresponding density matrix.
    * Representing a density matrix using the **Bloch vector** and Pauli matrices (`ρ = 1/2(I + u·σ)`).
    * Demonstrating that the expectation value of the Pauli operators on a state `ρ` yields the components of its Bloch vector (`⟨σᵢ⟩ = uᵢ`).

* **Quantum Cryptography:**
    * Modeling a simple eavesdropping scenario in a **Quantum Key Distribution (QKD)** protocol to calculate the probability of the eavesdropper's actions being detected.

## 3. Technologies Used

* **Language:** Python
* **Library:** `NumPy` for all numerical computations, matrix operations, and linear algebra.

## 4. How to Use

This file is a Jupyter Notebook (`.ipynb`). It can be viewed directly on GitHub or downloaded and run locally in an environment with Jupyter Notebook/JupyterLab installed. It can also be opened and run on cloud platforms like Google Colab. Each section corresponds to the numbered exercise from the problem set.
