# Entanglement
---

Interested in contributing to this project? 
- Reach out via email to: thesingularity.research@gmail.com
- Be sure to include "Hacking the Universe" in the subject line, so that the email doesn't get overlooked. 
- Write a paragraph or two about how you would like to contribute.
- Ask to Join the Discord server. 
- Ask to Join the Slack Channel.

This is course material for a course on linear algebra and mathematical prerequisites for quantum computing. It contains Jupyter notebooks that can be downloaded as part of the course or opened in Binder as an online interactive notebook. 

[Become a Sponsor of The Singularity](https://github.com/sponsors/The-Singularity-Research)


---

## What is...Entanglement?
Entanglement can be thought of as a correlation between states of systems of particles. The state of one particle can be statistically correlated with the state of another particle. The simplest example of this are the **Bell States**. Bell states are states describing a pair of entangled particles, where if one measures the state of one of the particles, then one *automatically* knows the state of the second particle without ever measuring it. This have famours physicists like Einstein, Podolsky, and Rosen great pause and disturbed them at times. Einstein at one point call entanglement a "**spooky action at a distance**". At first it was thought this might provide some way of communicating information faster than light. However, this is now known to not be possible. There are however phenomena such as **quantum teleportation** that use Bell states to transmit quantum information. 

## Lectures


### Bell States
Bell states are also sometimes called **EPR-states** after Einstein, Podolsky, and Rosen. There are four Bell states which involve two qubits. They correspond to the input state that is prepared before running the circuit that prepares a Bell state. These input states correspond to 00, 01, 10, and 11. Depending on which input state is prepared, the Bell states will behave slightly differently. The interesting behavior that is exhibited by the Bell states is *entanglement*. Measuring only one of the qubits immediately tells us what state the second qubit is in, without measuring it. This kind of state correlation is one of the fundamental properties of quantum computing.  

### Quantum Teleportation
**Quantum teleportation** is a way of transmitting quantum information using a quantum circuit and measurement. This allows one to transport an unknown quantum state to another location without violating the **No-Cloning Theorem**. 

### Quantum Teleportation in Qiskit
We will explore how to construct the quantum teleportation circuit in [Qiskit](https://qiskit.org/), IBM's quantum computing software library. 

### W-States
**W-states** are one of the most basic examples of something called **multipartite entanglement**. W-states exhibit the same kind of statistical behavior as Bell states, which shows that local **hidden variables theories** are impossible. Local hidden variables theories were advocated for by people such as Einstein and John von Neumann, who had issues with the **measurement problem** of quantum physics. They hoped that quantum physics was somehow an incomplete theory so that there must be some *hidden variables* at play, determining the outcome of measurements performed in the context of quantum mechanics. 

### GHZ-States
**GHZ-states**, named after Greenberger, Horne, and Zeilinger, are another class of quantum states that have **multipartite entanglement**. They are interesting because they are the second kind of state that exhibits *tripartite* entanglement. They, like many other multipartite entanglement states have applications to **quantum cryptography**. 

### Graph States
Graph states are a more general class of multipartite entangled systems of particles. They have entanglement properties that can be expressed as graphs, i.e. with sets of nodes connected by edges. These highly complex entangled states have several notions of entanglement and can be used for many applicatons such as **quantum cryptography**, **one-way quantum computing**, and as a way of expressing **stabilizer codes** for **quantum error correction**. 

### Quantikz
If you are a Donald Knuth fan and love LaTeX too, check out the TikZ library [quantikz](https://ctan.org/pkg/quantikz?lang=en). It is used in many of the lectures to render quantum circuit diagrams. 
