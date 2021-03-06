# ADMM on Memristor Crossbar Arrays
A Memristor-Based Optimization Framework via ADMM

Memristors have recently received significant attention as ubiquitous device-level components for building a novel generation of computing systems. These devices have many promising features, such as non-volatility, low power consumption, high density, and excellent scalability. The ability to control and modify biasing voltages at the two terminals of memristors make them promising candidates to perform matrix-vector multiplications and solve systems of linear equations. In this article, we discuss how networks of memristors arranged in crossbar arrays can be used for efficiently solving optimization and machine learning problems. We introduce a new memristor-based optimization framework that combines the computational merit of memristor crossbars with the advantages of an operator splitting method, alternating direction method of multipliers (ADMM). Here, ADMM helps in splitting a complex optimization problem into subproblems that involve the solution of systems of linear equations. The capability of this framework is shown by applying it to linear programming, quadratic programming, and sparse optimization. In addition to ADMM, implementation of a customized power iteration (PI) method for eigenvalue/eigenvector computation using memristor crossbars is discussed. The memristorbased PI method can further be applied to principal component analysis (PCA). The use of memristor crossbars yields a significant speed-up in computation, and thus, we believe, has the potential to advance optimization and machine learning research in artificial intelligence (AI).

See details in our paper "A Memristor-Based Optimization Framework for AI Applications, IEEE Circuits and Systems Magazine, 2018." https://arxiv.org/pdf/1710.08882.pdf

Software: Matlab package

Authors: Sijia Liu, Yangzhi Wang, Makan Fardad, Pramod K. Varshney

For questions, please contact lsjxjtu@gmail.com


