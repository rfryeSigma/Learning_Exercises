# Learning_Excercises
Notes about and quantum computing books and tutorials
including code for exercises

## Ike & Mike
The encyclopedic book
```
    Quantum Computation and Quantum Information
    Michael A. Nielsen & Isaac L. Chuang
    CAMBRIDGE UNIVERSITY PRESS
    First published 2000
    10th Anniversary edition published 2010
```
remains the bible for everything about quantum computing and information.

It contains exercises and problem sets.

## Frank Zickert
Folder
`
Frank_Zickert_Hands-On Quantum Machine Learning With Python
`

contains my `Jupyter` notebooks for exercises related to chapters of
```
    Hands-On Quantum Machine Learning With Python
    Volume 1: Get Started by Dr. Frank Zickert
    Copyright © 2021 Dr. Frank Zickert, pyqml.com
```
The book is an outgrowth of Zickert's informative blog at
[https://pyqml.medium.com/](https://pyqml.medium.com/)

The second volume has been published, but I have not read it yet.
```
Hands-On Quantum Machine Learning With Python Volume 2: Combinatorial Optimization
```

## Jack Hidary
The book
```
    Quantum Computing: An Applied Approach
    By Jack D. Hidary
    Springer Nature
    Second edition, 2021
```
gives a thorough treatment and contains examples in
- `Cirq` Google’s quantum computing development library
- `Qiskit` IBM's Quantum Information Science Kit written in `Qiskit` and `OpenQASM`,
- `Forest` Rigetti's development library written in `Quil` and `pyQuil`,
- `QDK` Microsoft's Quantum Development Kit written in `Q#`.

The companion website
[https://github.com/jackhidary/quantumcomputingbook](https://github.com/jackhidary/quantumcomputingbook)
gives supporting information, problem sets, and sample code.

I have used the examples to experiment with `Cirq`.

## O'Reilly
The book
```
    Programming Quantum Computers
    Essential Algorithms and Code Samples
    by Eric R. Johnston, Nic Harrigan, and Mercedes Gimeno-Segovia
    Copyright © 2019 Eric R. Johnston, Nic Harrigan, and Mercedes Gimeno-Segovia.
    Published by O’Reilly Media, Inc.,
```
simplifies examples by avoiding complex numbers and restricting to the real plane of the Bloch sphere.

The companion web site [https://oreilly-qc.github.io/](https://oreilly-qc.github.io/)
allows running of all of the code samples in a very useful interpretive environment
called `QCEngine` and coversion of the code to `Qiskit`, `OpenQASM`, `Q#`, or `Cirq`.

I used the site extensively to experiment with my own scripts.

## IBM Quantum
IBM offers free access to simulators and several 5 and 7 qubit computers with superb documentation.

IBM Composer lets you drag-and-drop circuit components or manipulate OpenQASM code and see the effect of running a circuit. It is an excellent tool for experimentation.

IBM Quantum Lab lets you develop and run `Jupyter` notebooks for running on simulators or IBM quantum computers.

Compute Resources shows the status of IBM quantum computers including qubit layout and performance at last calibration.

## MITRE Tutorial
The MITRE course tutorial at
[https://stem.mitre.org/quantum/quantum-concepts/qubits.html](https://stem.mitre.org/quantum/quantum-concepts/qubits.html]
offers clear explanations of quantum concepts and access to the `Quirk` webapp for graphically constructing and simulating quantum circuits.

## ZX Calculus
The ZX calculus simplifies the understanding of quantum circuits with category theory. The calculus is described in this book
```
    Quantum In Pictures)
    by Bob Coecke and Stefano Gogiosos
    Quantinuum (2023), 202 pages
```

and in this more complete and technical version
```
    Picturing Quantum Processes
    A First Course in Quantum Theory and Diagrammatic Reasoning
    by Bob Coecke and Aleks Kissinger
    Cambridge University Press (2017), 847 pages
```

This article by Ali Hussein, Peter Sigrist, and Ilyas Khan gives an overview

[How ZX-calculus reveals the logic and processes of quantum mechanics to everyone](https://medium.com/quantinuum/how-zx-calculus-reveals-the-logic-and-processes-of-quantum-mechanics-to-everyone-944fc3bbbb2c)
![image](https://user-images.githubusercontent.com/40242095/220784301-f0ad6ced-99b9-43a6-87ca-4f89f880761b.png)

Some links to other quantum graphs resources:
- YouTube videos including [Coecke applying graphs to NLP](https://www.youtube.com/watch?v=oXpndBKssTk)
- Wikipedia article [ZX-calculus](https://en.wikipedia.org/wiki/ZX-calculus)
- Extension to [ZW calculi](https://cs.ioc.ee/~amar/files/talk-lap-zwcalculi.pdf)
- arxiv articles including [Graphical quantum Clifford-encoder compilers from the ZX calculus](https://arxiv.org/pdf/2301.02356.pdf)
- [Quantomatic diagrammatic proof assistant](http://quantomatic.github.io)

## Other Useful Books
The book
```
    Quantum Computing
    by Mika Hirvensalo
    Springer Verlag (2001), 191 pages
```
covers the usual quantum algorithms from a more mathematical perspective.

The book
```
    Numerical Recipes in Quantum Information Theory and Quantum Computing
    An Adventure in FORTRAN 90
    by M. S. Ramkarthik and Payal D. Solanki
    CRC Press, 2022
```
gives `FORTRAN 90` code for simulating quantum components and algorithms.

## Other Resources

#### Playgrounds
Several other companies offer playgrounds for implementing and running quantum algorithms
- [Xanadu](https://www.xanadu.ai/)
- [QuTech](https://www.quantum-inspire.com/)

#### Zoos
Several sites link to publications about quantum algorithms
- [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org/)
- [Error Correction Zoo](https://errorcorrectionzoo.org/list/single)

#### Stack Exchange
The [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/)
is a great resource for common questions with expert answers.

#### Quantum Open Source Foundation
The [QOSF and Unitary Foundation](https://qosf.org/)
is a great resource for learning, contributing, meetups, etc.
They support many useful projects.

The companion [QOSF GitHub site](https://github.com/qosf) has repositories for
- Quantum benchmarks
- Peter Wittek's MOOC
- Monthly Challenges
- Links to awesome open source quantum softare projects
- ...

The companion [Unitary Fund GitHub site](https://github.com/unitaryfund) has
repositories for several projects including
 - `mitiq` implementation of error mitigation techniques
 - `pyqrack` OpenCL simulator library
 - `qrack` GPU accelerated simulator framework

#### QuEST
The [Quantum Exact Simulation Toolkit](https://quest.qtechtheory.org/)
is a high performance simulator of
quantum circuits, state-vectors and density matrices. QuEST uses
multithreading, GPU acceleration and distribution.

#### Preskill's Quantum Computation Course
Lecture notes from [John Preskill's course](http://theory.caltech.edu/~preskill/ph219/index.html#lecture)

#### ORNL Mailman
Oak Ridge National Lab publishes weekly updates on conferences, calls for papers, jobs, and academic positions.
[QCI External Email List](https://elist.ornl.gov/mailman/listinfo/qci-external)

## Omitted
There are many other areas that a very interesting, and I would like to learn more about but have not had time to explore.

#### Quantum Annealing
D-Wave developed, and now several other companies are exploring, adiabatic evolution via quantum and simulated annealing. They can achieve quantum supremacy by letting the Hamiltonian for a combinatorial optimization problem relax to the ground state.

#### Topological Fibonacci Anyons
Microsoft's Azure Quantum has invested in the search for Majorana non-Abelian anyons that can maintain stable qubits in braids. These topological approaches are mathematically intriguing but so far elusive.
