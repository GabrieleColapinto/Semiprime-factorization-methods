# Semiprime factorization methods
This is the final project of the exam "Formal languages and compilers" from the faculty of computer engineering of the Polytechnic University of Bari (Poliba).

This project contains the following algorithms to factorize semiprime numbers:
- Brute force algorithm
- Fermat's factorization algorithm
- Quadratic sieve algorithm
- Shor's algorithm

These algorithms are implemented in Python using [Jupyter](https://jupyter.org/) as a development environment.
The pdf file in this repository contains the exposition of the algorithms and the concepts of quantum computing necessary to understand the implementation of Shor's algorithm.
These concepts are:
- Qubits
- Superposition of qubits
- Measuring a qubit
- Quantum Fourier transform (QFT)
- Quantum Fourier inverse transform (QFT†, QFT dagger)
- QFT and QFT† using matrices
- QFT circuit
- QFT† circuit
- Quantum phase estimation

## Content of the repository
This repository contains the code and the essay of the project.
The code is organized in different folders named after the script they contain. Some folders contain more than one script:
- The folder "Quadratic sieve algorithm" contains two versions of the same algorithm: one vesion is not optimized to allow the user to understand every step, the other version is optimized to minimize the execution time of the algorithm;
- The folder "Plots" contains the scripts used to print the plots used in the essay;
- The folder "Shor's algorithm" contains three scripts:
    - period_finder.ipynb: This is the script used to find the period of the function used in the exposure of Shor's algorithm.
    - qft.ipynb: This is the script used to draw the QFT circuit used in the essay.
    - scalable_Shor.ipynb: This script contains the implementation of the scalable version of Shor's algorithm.

## Installation
In order to use this code on your machine it is preferable for you to use [Python 3.11.3](https://www.python.org/downloads/release/python-3113/) because it is the version used to develop the project.

After installing Python you can download the repository, open a prompt inside of it and create a virtual environment:
```
py -3.11 -m venv .\venv
```
Now you have to access the virtual environment and install the required Python modules:
```
.\venv\Scripts\activate
pip install .\requirements.txt
```

## Usage
After you have installed the required modules you have to open Jupyter Lab in order to see the code and its output. To open Jupyter Lab type the following command in the prompt:
 ```
jupyter lab
```
Now you should see Jupyter Lab in your browser and be able to explore the content of the repository, run the scripts and edit them if you want to. 