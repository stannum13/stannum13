# Shivank Nigam

Physics engineer working on ML systems, scientific computing, and hardware
control.

I like projects where models have to respect measurement budgets, device
constraints, and noisy physical systems: tensor-network diagnostics, photonic
calibration loops, and efficient inference experiments.

## Selected Work

### [adapter-cache-tradeoffs](https://github.com/stannum13/adapter-cache-tradeoffs)

Small-model serving experiment harness for measuring adapter specialization,
routing policy behavior, and KV-cache locality tradeoffs.

Current public state: routing-metric semantics corrected, SGLang/Vidur/vLLM
upstream pins recorded, E001 preregistered, smoke and canonical configs checked
in. Canonical SGLang results are not claimed yet.

### [TNView](https://github.com/stannum13/tnview)

Terminal-first telemetry for long-running tensor-network jobs.

Current public state: append-only `RunLogger`, run-log schema validation,
`tail`/`watch`/`replay`/`diagnose`/`compare` commands, Quimb/TeNPy upstream pins,
and preregistered diagnostics E001. Diagnostics are deterministic heuristics
until validated on the canonical corpus.

### [pic-autotune-control](https://github.com/stannum13/pic-autotune-control)

Virtual photonic-control lab for measurement-budgeted reacquisition experiments.

Current public state: controller-facing `LabSession`, actuator/detector/drift/
crosstalk/fault models, controller baselines and primitives, SAX upstream pin,
and preregistered PhotonLock E001. The SAX adapter and canonical evidence are
pending.

## Background

- **Dirac Labs** - Founding Systems Engineer. Built sensor pipelines, Kalman
  filtering, and neural denoising for quantum magnetometry at 10-100 Hz
  real-time.
- **ETH Zurich** - Thesis in theoretical molecular quantum dynamics.
  Accelerated nuclear-dynamics propagation using tensor-network methods.
- **EPFL** - Thesis in quantum photonics. Simulated and fabricated diamond
  photonic integrated circuits for quantum sensing.
- **BITS Pilani** - B.E. Manufacturing + M.Sc. Physics.

## Working Direction

- Evidence-bound ML systems experiments for efficient inference and scientific
  tooling.
- Hardware-aware control loops with explicit budgets, public observations, and
  reproducible baselines.
- Scientific software that is small enough to inspect and reproducible enough
  to extend.

## Contact

shivanknigam@gmail.com · [LinkedIn](https://linkedin.com/in/shivanknigam)
