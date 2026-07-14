# Shivank Nigam

Physics-engineer building AI systems for the physical world. Currently exploring differentiable physics, inverse design, and ML for hardware control.

## Background

- **Dirac Labs** — Founding Systems Engineer. Built sensor pipelines, Kalman filtering, and neural denoising for quantum magnetometry at 10-100 Hz real-time.
- **ETH Zürich** — Thesis in theoretical molecular quantum dynamics. Accelerated nuclear-dynamics propagation 10x using tensor-network methods.
- **EPFL** — Thesis in quantum photonics. Simulated and fabricated diamond photonic integrated circuits for quantum sensing.
- **BITS Pilani** — B.E. Manufacturing + M.Sc. Physics.

## Portfolio

### [pic-autotune-control](https://github.com/stannum13/pic-autotune-control)
Photonic IC autotuning virtual lab. Controllers (coordinate descent, Kalman, Bayesian optimization, MPC, particle filter), fabrication variation, fault primitives, RL environment wrapper, actor-critic superloop. 681 tests.

**Currently building:** calibration benchmark comparing controllers under drift, crosstalk, and measurement budgets.

### [photon-link-lab](https://github.com/stannum13/photon-link-lab)
Silicon-photonic optical link simulator: PAM4/NRZ symbols through modulator, channel, photodiode, equalization, BER estimation, calibration, WDM, yield Monte Carlo, ML surrogate, and CPO benchmarks. Connects to my EPFL thesis work on photonic IC design.

**Currently building:** Fourier Neural Operator surrogate for inverse link design.

### [latent-future-vla](https://github.com/stannum13/latent-future-vla)
Experiment scaffold for testing whether action-conditioned latent future prediction improves VLA policy robustness under OOD perturbations at fixed latency. Paired baseline/treatment rollout design, latency-gated evaluation, LIBERO/OpenVLA bridge hooks.

### [adapter-cache-tradeoffs](https://github.com/stannum13/adapter-cache-tradeoffs)
Benchmark harness for adapter specialization, KV-cache locality, and serving tradeoffs in causal-transformer systems. Compares semantic routing, cache-aware routing, sticky routing, and activated-LoRA-style late specialization.

### [tnview](https://github.com/stannum13/tnview)
Terminal-first telemetry and diagnostics tool for tensor-network runs (DMRG, TEBD). quimb/tenpy adapters, live watch mode, replay, diagnostics. v1.1.0 released.

## Currently Building

- **Differentiable quantum control pulse optimization** — JAX-based gradient optimization through Schrödinger evolution, comparing gradient-based methods against Bayesian optimization and standard swept calibration for qubit gate fidelity. Targets Conductor Quantum / Oratomic.
- **FNO surrogate for photonic inverse design** — Training a Fourier Neural Operator to replace expensive EM simulation in photonic device optimization. Targets PhysicsX / Periodic Labs.

## Contact

shivanknigam@gmail.com · [LinkedIn](https://linkedin.com/in/shivanknigam)
