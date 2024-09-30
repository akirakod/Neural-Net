# Neural Network-based Approximation for HPC Applications

---

## Project Overview

This project explores the use of Neural Networks in High Performance Computing (HPC) to approximate computationally intensive operations, specifically focusing on the **Newton-Raphson Method** for root finding and **Lennard-Jones (LJ) Potential** computations in molecular dynamics simulations using the LAMMPS software.

The goal is to reduce computation time without compromising accuracy by replacing code regions with neural network approximations. Various neural network architectures were tested and compared for their performance in different scenarios.

---

## Contents

- [Abstract](#abstract)
- [Details of the Organisation](#details-of-the-organisation)
- [Information Acquired](#information-acquired)
  - [General Machine Learning Concepts](#general-machine-learning-concepts)
  - [Newton-Raphson Method](#newton-raphson-method)
  - [Lennard-Jones (LJ) Potential in LAMMPS](#lennard-jones-lj-potential-in-lammps)
- [Conclusion](#conclusion)

---


## Abstract

High-Performance Computing (HPC) leverages parallelism to significantly reduce computation time for complex applications. Neural Networks, integrated into HPC, help model and predict results, effectively balancing speed and accuracy. This project investigates the use of Neural Networks to approximate computational regions like the **Newton-Raphson Method** and **Lennard-Jones Potential** in simulations, achieving high efficiency with minimal error.

---

## Details of the Organisation

**Hewlett Packard Enterprise (HPE)** is a global IT company focusing on servers, storage, networking, and consulting services. With a strong focus on innovation, HPE leads numerous research initiatives in High-Performance Computing and Artificial Intelligence.

---

## Information Acquired

### General Machine Learning Concepts

Machine Learning (ML) helps model complex, non-linear relations between input features and predicted output variables. The project focuses on using ML-based Neural Networks to optimize specific time-intensive code regions in HPC applications.

### Newton-Raphson Method

The **Newton-Raphson Method** is a root-finding algorithm, traditionally used in computational science. In this project, neural networks were used to approximate the method’s behavior to reduce execution time while maintaining accuracy. Various neural network architectures were tested, such as:
- 3x5x1
- 3x3x2x1
- 3x11x8x5x1

Performance metrics like **Mean Absolute Error (MAE)** and training time were analyzed.

### Lennard-Jones (LJ) Potential in LAMMPS

The **Lennard-Jones (LJ) Potential** models interactions between particle systems in molecular dynamics simulations. In this project, we approximated the LJ potential calculations using Neural Networks to enhance the simulation performance in LAMMPS (Large-scale Atomic/Molecular Massively Parallel Simulator).

---

## Conclusion

This project demonstrated that neural network-based approximations can significantly speed up specific calculations in High Performance Computing while maintaining acceptable accuracy. Different neural network architectures were evaluated, and the study suggests that deep neural networks can effectively replace time-consuming code regions in HPC applications.

---

## References

1. Ali Kashmar, “Solving Transcending Equations,” Numerical Analysis, 2018.
2. Shweta Shaw, “RMSprop: A Better Way to Optimize Your Model,” Medium, 2020.

---

### License

This project is open-source under the MIT License. Feel free to use and modify for educational purposes.
