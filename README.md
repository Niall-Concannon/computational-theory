# Computational Theory

## Overview

This repository contains my work for the Computational Theory assessment.

The project focuses on implementing the SHA-256 hashing algorithm using Python. It involves working through the different parts of the algorithm, including data representation, bitwise operations, generating constants, message padding and the compression function.

The aim is to combine these components into a working SHA-256 implementation and test its results against Python's built-in `hashlib` library.

## Repository Contents

| File | Description |
|---|---|
| `problems.ipynb` | Main assessment notebook containing explanations, implementations and tests for Problems 1–6. |
| `AGENTS.md` | Instructions and guidance for the project. |
| `requirements.txt` | Python dependencies required to run the notebook. |
| `.gitignore` | Files and folders excluded from version control. |

## Topics Covered

The assessment is divided into six problems:

- **Problem 1:** Representing SHA-256 Data.
- **Problem 2:** SHA-256 Bitwise Operations.
- **Problem 3:** Generating the SHA-256 Constants.
- **Problem 4:** Padding and Parsing Messages.
- **Problem 5:** The SHA-256 Compression Function.
- **Problem 6:** Complete SHA-256.

## Installation and Usage

Clone the repository:

```bash
git clone https://github.com/Niall-Concannon/computational-theory.git
cd computational-theory
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch the Jupyter notebook:

```bash
jupyter notebook problems.ipynb
```

## Requirements

- Python 3.10+
- NumPy
- Jupyter Notebook

## References

- [NIST – Secure Hash Standard (FIPS 180-4)](https://doi.org/10.6028/NIST.FIPS.180-4)
- [NumPy Documentation](https://numpy.org/doc/stable/)
