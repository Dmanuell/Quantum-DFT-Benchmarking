# Quantum DFT Benchmarking ⚛️

Welcome to the **Quantum-DFT-Benchmarking** repository! This project focuses on quantum-classical density functional theory (DFT) benchmarking, specifically targeting covalent bond formation in CDK12 inhibitor mechanisms. Our goal is to provide a comprehensive toolkit for researchers in computational chemistry, drug discovery, and quantum computing.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen)](https://github.com/Dmanuell/Quantum-DFT-Benchmarking/releases)

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

---

## Introduction

The study of covalent bond formation is crucial in understanding drug interactions and molecular behavior. This repository provides tools and datasets for benchmarking DFT methods against quantum mechanics (QM) calculations. By comparing different methods, we aim to improve the accuracy and efficiency of simulations in drug discovery.

This project uses several computational techniques, including molecular dynamics simulations and variational quantum eigensolver (VQE) algorithms, to analyze the properties of CDK12 inhibitors. 

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/Dmanuell/Quantum-DFT-Benchmarking.git
cd Quantum-DFT-Benchmarking
```

Next, install the required dependencies. We recommend using Python's package manager, pip:

```bash
pip install -r requirements.txt
```

Make sure you have ORCA installed on your system for quantum chemistry calculations. You can download it from the [ORCA website](https://orcaforum.kofo.mpg.de/app.php/portal).

## Usage

After installation, you can begin benchmarking DFT methods. The main script is located in the `src` directory. To run the benchmarking analysis, execute:

```bash
python src/benchmark.py
```

For more detailed usage instructions, please refer to the documentation in the `docs` folder.

## Methodology

Our benchmarking approach involves the following steps:

1. **Data Preparation**: Gather molecular structures and relevant parameters for CDK12 inhibitors.
2. **Quantum Calculations**: Use ORCA to perform high-level quantum calculations.
3. **DFT Calculations**: Implement various DFT methods to evaluate their performance against quantum results.
4. **Analysis**: Compare energies, geometries, and other properties to assess accuracy.

### Key Topics

- **Benchmarking**: Evaluating the performance of different computational methods.
- **Computational Chemistry**: The use of computer simulations to solve chemical problems.
- **Density Functional Theory (DFT)**: A quantum mechanical method used to investigate the electronic structure of many-body systems.
- **Drug Discovery**: The process of discovering new medications based on the knowledge of biological targets.
- **Molecular Dynamics Simulation**: A computer simulation method for analyzing the physical movements of atoms and molecules.
- **Quantum Chemistry**: The study of how quantum mechanics applies to chemical systems.
- **Quantum Computing**: The area of computing focused on developing computers that use quantum bits (qubits).

## Results

The results section provides insights into the performance of different DFT methods. You can find detailed results in the `results` directory. The data includes:

- Energy comparisons
- Geometric optimizations
- Benchmarking graphs

For visual representation, we have included plots generated using Matplotlib. These plots help illustrate the differences between methods and their effectiveness in predicting molecular behavior.

### Sample Results

Here is a brief overview of some results obtained:

| Method      | Average Error (kcal/mol) | Time Taken (s) |
|-------------|---------------------------|-----------------|
| B3LYP       | 1.5                       | 10              |
| PBE0        | 1.2                       | 12              |
| M06-2X     | 1.8                       | 15              |

These results indicate that PBE0 shows the least average error while maintaining reasonable computational time.

## Contributing

We welcome contributions to enhance this project. If you want to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

Before contributing, please check the existing issues to see if your idea is already being discussed.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries, please reach out via the following channels:

- Email: [your-email@example.com](mailto:your-email@example.com)
- GitHub Issues: [Open an Issue](https://github.com/Dmanuell/Quantum-DFT-Benchmarking/issues)

You can also visit our [Releases section](https://github.com/Dmanuell/Quantum-DFT-Benchmarking/releases) for the latest updates and downloads.

---

We hope this repository serves as a valuable resource for your research in quantum-classical DFT benchmarking. Thank you for your interest!