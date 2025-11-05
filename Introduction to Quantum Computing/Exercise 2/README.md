# Quantum States, Density Matrices, and Entanglement — Problem Set Notebook

This notebook presents detailed, step-by-step solutions and implementations of selected problems from *Quantum Information and Quantum Computation* coursework.  
It explores the mathematical properties and computational representations of quantum states using **NumPy**, with an emphasis on **density matrices**, **purity**, **entanglement**, and **quantum communication**.

---

## 🧩 Topics Covered

### **1. Density Matrices and Purity (Problem 1.24 – 1.25)**
- **Objective:** Verify that a quantum state ρ is *pure* if and only if `Tr(ρ²) = 1`.  
- **Implementation:** A simple function checks the purity of a given density matrix.  
- **Extensions:** Validation of a general density matrix ρ₁(p) for different parameter values of *p*, confirming trace, Hermiticity, and positive semi-definiteness.

---

### **2. Entangled States and Partial Trace (Problem 1.27)**
- **Objective:** Construct and analyze the antisymmetric entangled state:  

  **|Ψ′⟩ = (1/√2) · ( |e₁⟩⊗|e₂⟩ − |e₂⟩⊗|e₁⟩ )**

- **Tasks:**
  - Compute the full density matrix **ρ = |Ψ′⟩⟨Ψ′|**.  
  - Perform the **partial trace** to obtain the reduced density matrix of one subsystem.  
  - Verify Hermiticity, normalization, and eigenvalue structure.

---

### **3. Purification of Mixed States (Problem 1.28)**
- **Objective:** Find a **purification** |Ψ⟩ of a mixed density matrix:  

  **ρ₁ = (1/4) · [[1, 0], [0, 3]]**

- **Results:**  
  - Computed eigenvalues and eigenvectors.  
  - Built a valid purified state |Ψ⟩ in an extended Hilbert space.  
  - Verified that tracing out the ancillary system reproduces the original ρ₁.

---

### **4. Fidelity Between Quantum States (Problem 1.31)**
- **Objective:** Compute the **fidelity** *F(ρ₁, ρ₂)* between two density matrices.  
- **Highlights:**
  - Implemented the general fidelity formula using eigen-decomposition.  
  - Verified numerical vs analytical results and confirmed *F(ρ, ρ) = 1*.

---

### **5. Bloch Sphere Representation (Problem 2.2 – 2.3)**
- **Objective:**  
  - Express the pure state  

    **|Ψ(θ, φ)⟩ = cos(θ/2)·|0⟩ + e^(iφ)·sin(θ/2)·|1⟩**

    as a density matrix **ρ = (I + u·σ)/2**.  
  - Verify that the Bloch vector components correspond to the expectation values **⟨σ⟩ = Tr(ρσ) = u**.

- **Key Takeaway:**  
  Demonstrates the equivalence between state vector, density matrix, and Bloch vector formulations.

---

### **6. Bell Basis and Entanglement (Problem 2.4 – 2.5)**
- **Objective:**  
  - Construct the **Bell basis** from the computational basis using a unitary transformation.  
  - Verify orthonormality and unitarity.  
  - Compute expectation values of composite operators (for example, X⊗Z) in Bell states.

- **Output:**  
  Explicit Bell states:  
  - |Φ⁺⟩ = (|00⟩ + |11⟩)/√2  
  - |Φ⁻⟩ = (|00⟩ − |11⟩)/√2  
  - |Ψ⁺⟩ = (|01⟩ + |10⟩)/√2  
  - |Ψ⁻⟩ = (|01⟩ − |10⟩)/√2  

  and verification of their mutual orthogonality.

---

### **7. Quantum Key Distribution (Problem 2.6)**
- **Scenario:**  
  Models the **BB84 QKD protocol** steps:
  - Alice encodes bit 0 as |↑⟩.  
  - Eve intercepts and measures in the rotated basis { |↗⟩, |↘⟩ }.  
  - Bob measures again in { |↑⟩, |↓⟩ }.  

- **Goal:** Compute the probability that Bob obtains 0 after Eve’s interference.  
- **Result:** Demonstrates how measurement disturbance leads to probabilistic outcomes — the core security principle of quantum key distribution.

---

## ⚙️ Technologies Used
- **Python 3**
- **NumPy** for linear algebra and matrix operations
- **Jupyter Notebook** for interactive demonstrations

---

## 📚 Learning Outcomes
Through these implementations, you will:
- Understand how to test quantum state validity (trace, Hermiticity, positivity).  
- Visualize entangled and mixed states computationally.  
- Perform fidelity and purity calculations.  
- Connect matrix algebra with physical concepts such as measurement, decoherence, and entanglement.

---

## 📄 References
- Nielsen & Chuang, *Quantum Computation and Quantum Information*  
- M. A. Nielsen (2000), Cambridge University Press  
- Quantum Computing lectures from the Master in Quantum Engineering program

---

## 👤 Author
**Oussama Turki**  
Quantum Technology Engineer | M.Sc. Quantum Engineering  
🔗 [LinkedIn](Your_LinkedIn_URL) • [GitHub](Your_GitHub_URL)

---

*This notebook is part of my Quantum Engineering Portfolio, showcasing applied problem-solving in quantum information theory.*
