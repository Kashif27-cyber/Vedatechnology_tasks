# NumPy Random Sampling

**Data Science Track — Task 13**

Generate random numbers and samples using NumPy and explore reproducibility using random seeds.

## Objective

Understand random data generation and its importance in data science experiments.

## Contents

- [`numpy_random_sampling.ipynb`](./numpy_random_sampling.ipynb) — the main notebook, containing:
  - Random integer and floating-point number generation
  - Random sampling from an array (with/without replacement, weighted sampling, shuffling)
  - Demonstration of reproducible results using a random seed
  - A small simulated "student marks" dataset
  - Answers to the interview questions below

## Tools

- Python
- NumPy
- Jupyter Notebook

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/numpy-random-sampling.git
   cd numpy-random-sampling
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook numpy_random_sampling.ipynb
   ```

## Deliverables

- [x] Examples of random integers and floating-point numbers
- [x] Random samples from an array
- [x] A demonstration of reproducible results using a seed

## Interview Questions

**Q1. Why are random numbers useful in data science?**
Random numbers are used to simulate data when real data isn't available, split datasets
into train/validation/test sets, initialize model parameters, run bootstrapping and
cross-validation, perform Monte Carlo simulations, and shuffle data to avoid learning
spurious ordering patterns.

**Q2. What is a random seed?**
A random seed is the starting value given to a pseudo-random number generator. Since
computers generate deterministic sequences that only look random, the seed fixes the
starting point, so the same seed always reproduces the same sequence of numbers.

**Q3. Why is reproducibility important?**
Reproducibility ensures that an experiment, when re-run under the same conditions,
produces the same results — allowing others to verify findings, debug reliably, fairly
compare models, and trust reported results.

## License

This project is licensed under the MIT License — see [LICENSE](./LICENSE) for details.
