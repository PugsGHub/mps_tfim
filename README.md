# Tensor Networks
### Project for the Computational Physics Course
### Pugazharasu A D and Rishi Kumar S
## Project
Matrix product states (MPS) are an efficient way to approximate the ground states
of low-dimensional local gapped Hamiltonians [2]. Moreover, techniques based on
such a representation such as the Density Matrix Renormalization Group (DMRG)
i.e. a variational method for computing the groundstate for a Hamiltonian in
an MPS representation, have been shown to be the most efficient method for 1-
dimensional systems [1]. In this project, by using these techniques we will examine
the properties of the transverse field Ising model,
$$\hat{H}=-\sum_{i=1}^{L-1} \hat{S}_i^z \hat{S}_{i+1}^z-g \sum_{i=1}^L \hat{S}_i^x$$
by means of constructing a MPS for its ground state and using DMRG methods
to determine the critical point and central charge.

## Tasks
- Show that a long-range order exists by computing the squared magnetization $\expval{m^{2}}$ as a function of $g$ 
- Determine the critical point $g_c$ by means of using the binder cumulant,
$$U_L=1-\frac{\left\langle{m}_z^4\right\rangle_L}{3\left\langle{m}_z^2\right\rangle_L^2}$$
- Determine the value of the binder cumulant critical exponent $\nu$ by performing a scaling collapse of the Binder cumulant. Does this gap close at $g = g_c$?
- Use a DMRG routine to compute the excitation energy gap $\Delta E$ as a function of the transverse field
- Determine the central charge by probing the scaling relation of the half-chain entropy with respect to system size

## References
[1]. N. Nakatani. Matrix product states and density matrix renormalization group
algorithm. In Reference Module in Chemistry, Molecular Sciences and Chem-
ical Engineering. Elsevier, 2018. {#ref1}

[2].