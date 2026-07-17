# Shivank Nigam

Physics engineer working on evidence-bound ML systems, scientific computing, and
hardware-aware control.

I like projects where models and controllers have to make decisions with limited
measurements, messy hardware signals, and held-out tests instead of polished
demo traces.

## Primary Work

### [adapter-cache-tradeoffs](https://github.com/stannum13/adapter-cache-tradeoffs)

Measures a practical serving question: when many fine-tuned adapters share one
base model, can requests be routed so the GPU reuses cached work instead of
starting cold each time? Current work covers routing metrics, upstream pins, and
smoke experiments; canonical SGLang results are not claimed yet.

### [TNView](https://github.com/stannum13/tnview)

Terminal tools for long tensor-network simulations, the kind that can run for
hours before failing. It records structured logs, replays runs, and surfaces
early warning diagnostics; canonical Quimb/TeNPy corpus validation remains
pending.

### [pic-autotune-control](https://github.com/stannum13/pic-autotune-control)

Virtual lab for tuning photonic chips when heaters drift and every measurement
costs time. It has controller baselines, drift/fault models, a SAX upstream pin,
and a preregistered PhotonLock E001; the SAX adapter and canonical evidence are
still future work.

### [episode-lens](https://github.com/stannum13/episode-lens)

Scores robot demonstration files before training, so bad or incomplete episodes
can be filtered instead of silently poisoning a policy dataset. Current evidence
is manifest and quality-feature smoke testing, not a policy-improvement result.

## Focused Experiments

- [marginalia](https://github.com/stannum13/marginalia) - tracks paper searches,
  quotes, citations, and evidence while building budget-aware research briefs.
- [policy-climb](https://github.com/stannum13/policy-climb) - deterministic
  benchmark for comparing small policy-search algorithms under the same
  evaluation budget.
- [linkscope](https://github.com/stannum13/linkscope) - silicon-photonic link
  simulator that counts real Gray-coded bit errors through calibration and drift
  tests.
- [linebreak-uncertainty](https://github.com/stannum13/linebreak-uncertainty) -
  BreakState tests whether small language models encode line position when text
  wraps to a new line.
- [memplex](https://github.com/stannum13/memplex) - Fisher Damping optimizer
  experiments for choosing natural-gradient damping from curvature signals.
- [qgf-autoresearch](https://github.com/stannum13/qgf-autoresearch) - QGF Ledger
  records bounded Q-Guided Flow replication attempts, artifacts, and failure
  modes.

## Background

- **Dirac Labs** - Founding Systems Engineer. Built sensor pipelines, Kalman
  filtering, and neural denoising for quantum magnetometry at 10-100 Hz
  real-time.
- **ETH Zurich** - Thesis in theoretical molecular quantum dynamics.
  Accelerated nuclear-dynamics propagation using tensor-network methods.
- **EPFL** - Thesis in quantum photonics. Simulated and fabricated diamond
  photonic integrated circuits for quantum sensing.
- **BITS Pilani** - B.E. Manufacturing + M.Sc. Physics.

## Contact

shivanknigam@gmail.com - [LinkedIn](https://linkedin.com/in/shivanknigam)
