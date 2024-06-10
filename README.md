# ACGRIME: Enhanced RIME Algorithm

## Overview

ACGRIME is an enhanced version of the RIME optimization algorithm. It integrates chaos theory, adaptive chaotic weighting, and Gaussian mutation to address the limitations of the original RIME algorithm, including issues with population diversity and local optima. ACGRIME demonstrates superior performance in global optimization and feature selection tasks.
Dataset link: https://archive.ics.uci.edu/datasets

## Performance

Extensive comparative experiments have shown that ACGRIME outperforms the original RIME algorithm, other recently proposed RIME variants (WHRIME, CCRIME), and 11 advanced algorithms across multiple dimensions (10, 30, 50, 100) using the CEC 2017 benchmark functions. ACGRIME has also been tested against 11 advanced algorithms, demonstrating superior global optimization capabilities through statistical tests like the Wilcoxon signed-rank test and the Friedman test, as well as balance and diversity analyses.

## Results

- **Global Optimization:** ACGRIME achieved better convergence speed and stability across various benchmark functions.
- **Feature Selection:** The binary form of ACGRIME (bACGRIME) demonstrated superior classification accuracy with fewer features on 22 UCI datasets compared to six well-known algorithms.


1. Clone the repository:

```sh
git clone https://github.com/batis1/ACGRIME.git
cd ACGRIME
