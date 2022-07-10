---
layout: page
title: "Semiconductor Qubits"
---

[Return Home](https://tylerjwhitts.github.io)  

# What is a qubit?

A qubit, short for quantum bit, is a two level system with the quantum properties of superposition and entanglement.
Qubits are the building blocks of quantum computers just as bits are to a classical computer. A successful qubit is 
one that can be initialised, coherently controlled and measured with high fidelity.  

If a qubit has the two states  $$\vert 0\rangle$$ and  $$\vert 1\rangle$$ then superposition requires that the qubit can also be in the state  

$$|\psi\rangle = \cos{\left(\theta/2\right)}|0\rangle + \frac{1}{2}e^{i\varphi}\sin{\theta}|1\rangle$$  

where  $$\theta$$ and  $$\varphi$$ are real numbers that define a point on a 3D unit sphere, called the _Bloch sphere_. The qubit can be in any state on this Bloch sphere. With two axes control e.g. rotation about the  $$z$$ and  $$y$$ axis by  $$\phi_z$$ and  $$\phi_y$$, one can take a qubit in any intial state $$\vert \psi_i\rangle$$ to any target state  $$\vert \psi_t\rangle$$ [1].  

### References  
1. Zhang X. et al. 2019 National Science Review 6, 32-54, DOI: [10.1093/nsr/nwy153](https://doi.org/10.1093/nsr/nwy153)

# ToDo  

- DiVincenzo criteria
- $$T_1$$ and $$T_2$$ times
- Si/SiGe wiggle well
- Use proper referencing system maybe a .bib file somehow
