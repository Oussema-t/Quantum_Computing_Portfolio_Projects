Exercise 1: Mathematical Foundations for Quantum Computing
1. Objective
This Jupyter Notebook contains solutions to a series of exercises focused on the fundamental linear algebra concepts that underpin quantum mechanics and quantum computing. The purpose is to demonstrate a practical and applied understanding of vector spaces, matrix operations, and decompositions using Python with the NumPy and SciPy libraries.

2. Key Concepts Demonstrated
This notebook covers the implementation and verification of several core mathematical principles:

Vector Spaces and Bases: Validating if a set of vectors forms a basis for a vector space.

Inner Products and Norms: Calculating the inner product (⟨x|y⟩) and norm (‖|x⟩‖) for complex vectors.

Gram-Schmidt Orthonormalization: Constructing an orthonormal basis from a given set of linearly independent vectors.

Eigenvalue Problems: Finding eigenvalues and their corresponding normalized eigenvectors for various matrices.

Spectral Decomposition: Decomposing a matrix into the product of its eigenvectors and eigenvalues (A = VΛV⁻¹).

Properties of Unitary Matrices: Demonstrating that the eigenvalues of a unitary matrix are unimodular (|λ| = 1).

Matrix Exponentiation: Calculating the exponential of a matrix (exp(iA)).

Singular Value Decomposition (SVD): Decomposing a matrix into its singular values and singular vectors (A = UΣV*).

3. Structure of the Notebook
The notebook is organized by exercise number, with each section addressing a specific problem:

1.1: Checks for linear independence of vectors by calculating the determinant of the matrix they form.

1.2 & 1.3: Computes vector norms and inner products for complex vectors and verifies the conjugate symmetry property (⟨x|y⟩ = ⟨y|x⟩*).

1.4: Calculates the coefficients to express a vector as a linear combination of an orthonormal basis.

1.5 & 1.6: Implements the Gram-Schmidt process to find an orthonormal basis for given sets of vectors, including complex vectors.

1.8 - 1.14: Solves multiple eigenvalue problems for 2x2 and 3x3 matrices. This includes:

Finding eigenvalues and eigenvectors.

Verifying eigenvector orthogonality.

Performing spectral decomposition and using it to find the inverse of a matrix.

1.16: Performs Singular Value Decomposition (SVD) on a complex matrix and verifies the result.

4. Technologies Used
Language: Python

Libraries:

NumPy: For numerical operations, linear algebra, and matrix manipulation.

SciPy: For specialized functions like matrix exponentiation (expm).

5. How to Use
This file is a Jupyter Notebook (.ipynb). It can be viewed directly on GitHub or downloaded and run locally in an environment with Jupyter Notebook/JupyterLab installed. It can also be opened and run on cloud platforms like Google Colab.
