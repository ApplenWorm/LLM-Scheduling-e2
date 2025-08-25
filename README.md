# GPU Configuration Optimization Algorithms

This repository contains three optimization algorithms for finding optimal GPU configurations to create efficient processing islands for Large Language Model (LLM) request handling.

## Overview

The project implements three distinct optimization strategies for GPU configuration management:

1. **Throughput Optimization Algorithm** - Maximizes system throughput by finding the best GPU configuration
2. **Latency Optimization Algorithm** - Minimizes response latency by optimizing GPU configurations
3. **Constrained Throughput-Latency Optimization Algorithm** - Optimizes latency while maintaining throughput constraints

## Project Structure

```
result_git/
├── README.md                 # This file
├── plan.md                   # Detailed project plan and methodology
├── results/
│   ├── throughput_optimization/     # Results for throughput optimization
│   ├── latency_optimization/        # Results for latency optimization
│   └── constrained_optimization/    # Results for constrained optimization
├── src/                      # Source code for algorithms
├── data/                     # Input data and configurations
├── docs/                     # Documentation
└── tests/                    # Test files
```

## Algorithms

### 1. Throughput Optimization Algorithm
- **Objective**: Maximize system throughput
- **Method**: Find GPU configurations that maximize request processing capacity
- **Output**: Optimal GPU island configurations for maximum throughput
- **Results Location**: `results/throughput_optimization/`

### 2. Latency Optimization Algorithm
- **Objective**: Minimize response latency
- **Method**: Optimize GPU configurations to reduce processing time
- **Output**: Optimal GPU island configurations for minimum latency
- **Results Location**: `results/latency_optimization/`

### 3. Constrained Throughput-Latency Optimization Algorithm
- **Objective**: Optimize latency while maintaining throughput constraints
- **Method**: Find GPU configurations that minimize latency given throughput requirements
- **Output**: Optimal GPU island configurations balancing both metrics
- **Results Location**: `results/constrained_optimization/`

## Configuration Parameters

GPU configurations include parameters such as:
- Number of GPUs per island
- GPU types and specifications
- Memory allocation
- Network topology
- Load balancing strategies
- Request routing patterns

## Getting Started

1. Clone this repository
2. Review the `plan.md` file for detailed methodology
3. Navigate to the `src/` directory for algorithm implementations
4. Check `results/` directories for optimization outcomes

## Results

All optimization results are publicly available in the respective `results/` subdirectories. Each algorithm's results include:

- Configuration matrices
- Performance metrics
- Optimization convergence data
- Comparative analysis
- Visualization plots

## Contributing

This is a public repository for sharing optimization algorithm results. Feel free to:

- Review and analyze the results
- Suggest improvements to algorithms
- Contribute additional optimization strategies
- Report issues or inconsistencies

## License

This project is open source and available under the MIT License.

## Contact

For questions or contributions, please open an issue or submit a pull request.
