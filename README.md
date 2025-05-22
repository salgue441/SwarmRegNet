# SwarmRegNet

Particle Swarm Optimization for Gene Regulatory Network Inference and Analysis

## Project Overview

SwarmRegNet leverages the collective intelligence of particle swarm optimization (PSO) to infer and optimize gene regulatory networks from expression data. By treating network topology and regulatory parameters as a multi-dimensional optimization problem, this project aims to discover robust gene regulatory relationships that traditional methods might miss.

## Key Motivation

Gene regulatory networks (GRNs) are complex, non-linear systems where traditional gradient-based optimization often gets trapped in local optima. PSO's population-based search and social learning mechanisms make it particularly well-suited for exploring the vast, multi-modal landscape of possible regulatory network configurations.

## Features

- **Multi-objective Network Optimization**: Simultaneously optimize network topology, regulatory strength, and model complexity.
- **Dynamic Swarm Parameters**: Adaptive inertia, cognitive, and social coefficients based on convergence patterns
- **Biological Constraint Integration**: Incorporate prior knowledge about transcription factors, promoter regions, and regulatory motifs
- **Time-series Expression Modeling**: Handle temporal gene expression data for dynamic network inference
- **Network Robustness Analysis**: Evaluate network stability under perturbations using swarm-based sensitivity analysis
- **Visualization Suite**: Interactive network visualization with regulatory strength indicators and particle trajectory plots
