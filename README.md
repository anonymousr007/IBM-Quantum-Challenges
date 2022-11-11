## IBM Quantum Challenge Fall 2022

- The challenge will start with an introduction of Qiskit primitives and the programming model it describes, while drawing parallels to its interface with the Qiskit Runtime service and its features.
- This will proceed with the succeeding notebooks that will serve as a guide for constructing and building upon a few common quantum computational algorithms using this primitive construct.
- Each notebook slowly ramps up the complexity of the routines built and introduces features within Qiskit Primitives and the Qiskit Runtime service.
- Each exercise is presented as a Jupyter notebook hosted on the IBM Quantum Lab site. Complete all parts in each lab and pass the graders to complete the exercise.
- The exercises are divided into categories of Foundational, Intermediate and Advanced based on the complexity they entail.
- To recognize your achievement for completing the exercises, you will receive a credly acclaimed digital achievement badge to showcase the skills you have developed
during the challenge! Badges are up for partial and full completion of the exercises!

### Lab 1 - Introduction to Primitives on Qiskit Runtime

- Do you know that there is a way to maximize the quantum workflow in Qiskit? To execute quantum circuits, all of them are going through the cloud environment.
- Especially, there is an obvious delay when you are using an algorithm which requires feedback loops between classical and quantum hardware. In this kind of situation, we can expect a substantial speed-up on primitives with Qiskit Runtime.
- In exercise 1 we are going to learn what Qiskit Runtime and primitives are and how to use them in a proper way. We also comprehend the exact meaning of error mitigation and simple prologues of its techniques.
- As this exercise is including the primitives and the error mitigation techniques, it will be a basement for solving all the following exercises. Please free to explore as much as possible along with your own spaceship!

### Lab 2 - Quantum Kernel Learning with Qiskit Runtime

- Throwing of machine learning into quantum computing creates interest areas of research that use the principles of quantum mechanics to enhance machine learning or vice versa.
- This lab will focus on Qiskit Runtime Sampler and applying the error mitigation technique, matrix-free measurement mitigation (M3) to machine learning application problems, including the quantum kernel learning.
- Your mission is to test whether your repairs of quantum computer with limited resources is successful.

### Lab 3 - Optimization with Qiskit Primitives

- Optimization is required everywhere in fields such as manufacturing, economics, engineering and more.
- Solving higher complexity problems combined with potential massive amounts of data requires more efficiency and scalability of this data-driven technology.
- NP-hard problems including the travelling salesman problem, the max-cut problem and the set cover problem are intractable on the classical computer to be solved.
- This lab, we shall utilise the the newly refactored VQE class on Estimator using Qiskit runtime to approach a model.
- Travelling salesman problem. For this problem, we will build some problem specific PQC’s considering each TSP constraints in an attempt to find a better convergence.
- We shall also be looking into Digital ZNE as our Error Mitigation strategy currently available on Qiskit Runtime as a service.

### Lab 4 - Quantum chemistry with Qiskit Primitives

- One of the most natural use cases of quantum computing is in chemistry applications; quantum computing offers the ability to simulate the behaviour of molecules without the need for large approximations that classical computers currently require.
- In this lab, you will learn how to apply Qiskit Primitives to construct and build routines using VQE to compute the ground state energies of molecules, total reaction energy for a given reaction and calculate the excited energy wavelength spectrum using VQD for multiple excited states.
- You will also be introduced to the prototype-zne module to explore building custom Digital ZNE routines for Error mitigation.
