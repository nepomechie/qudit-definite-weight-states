# Preparing multi-qudit states in a definite-weight subspace  https://arxiv.org/abs/2606.24659 
The file qudit-state-preparation.ipynb contains cirq code for preparing arbitrary multi-qudit states with definite weight.

As examples, the preparation of the following states is considered:

$\bullet$ $SU(d)$ Dicke states

$\bullet$ $SU_q(d)$ Dicke states

$\bullet$ $SU(3)$ Bethe states (eigenstates of the integrable $SU(3)$-invariant Heisenberg Hamiltonian with PBC)

The preparation of $U(1)^{d-1}$-eigenstates with random real or complex amplitudes is also illustrated.

A separate file (su3BetheDescendants.ipynb) focuses on preparing lower-weight descendants of the $SU(3)$ Bethe states, which are $SU(3)$ highest-weight states.

This code can be run on Google colab  ( https://colab.google/ ) or locally, using python (3.12.1) and cirq (1.5.0)
