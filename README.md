# MPI-RainbowTables-Experiment-Data

This repository contains experimental data supporting the study titled **"Parallelization of Rainbow Tables Generation Using Message Passing Interface: A Study on NTLMv2, MD5, SHA-256 and SHA-512 Cryptographic Hash Functions"**, and published in MDPI Applied Sciences.

## Overview

The experiments focus on evaluating the performance of parallel rainbow table generation using the Message Passing Interface (MPI) across various cryptographic hash functions. The primary metrics assessed include execution time, speedup, and efficiency, with variations in the number of computing nodes and table sizes.

## Data Description

The repository includes the following CSV files, each representing a specific experimental scenario:

- **first_experiment_case1_10000x20000.csv**  
  Data from the first experiment, Case 1, analyzing the impact of varying the number of nodes on execution time, speedup, and efficiency for a table size of 10,000 x 20,000.

- **first_experiment_case2_50000x40000.csv**  
  Data from the first experiment, Case 2, focusing on a larger table size of 50,000 x 40,000, assessing similar performance metrics as in Case 1.

- **second_experiment.csv**  
  Results from the second experiment, which examines the influence of chain count on the execution time.

- **third_experiment.csv**  
  Data from the third experiment, exploring the The influence of chain length on the execution time.

## Citation
**Vainer, M.**, Kačeniauskas, A., & Goranin, N. (2025). Parallelization of Rainbow Tables Generation Using Message Passing Interface: A Study on NTLMv2, MD5, SHA-256 and SHA-512 Cryptographic Hash Functions. Applied Sciences, 15(15), 8152. https://doi.org/10.3390/app15158152
