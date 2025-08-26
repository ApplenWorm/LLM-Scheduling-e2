# ShallowSim GitHub Repositories

This document contains links to ShallowSim repositories from different contributors.

## Available Repositories

### Zartbot's Implementation
- **Repository**: [zartbot/shallowsim](https://github.com/zartbot/shallowsim)
- **Contributor**: Zartbot

### Icezack12's Implementation  
- **Repository**: [icezack12/shallowsim](https://github.com/icezack12/shallowsim)
- **Contributor**: Icezack12

## About ShallowSim

Shallowsim is a specialist simulator designed to estimate the compute times for different LLM request types. Specifically built for DeepSeek-V3/R1 models, it has native support for simulating MoE architectures. Unlike Vidur, Shallowsim requires no profiling phase, rather a list of device performance metrics is provided e.g. fp8 performance.
These metrics are then used to compute the expected performance for the prefill and decode phase separately