# Aarya Upadhya

4th-year CS (AI/ML) at PES University, Bengaluru.

I work on RL policies for real systems reward signal design, policy evaluation, and what happens when a deployed policy meets a distribution it wasn't trained on. Currently extending Zone-Heal, a deployed RL router for AWS availability zones, to test whether a policy that observes its own entropy can recover more reliably than one that falls back on a fixed rule.

## Publications

- **PAR-VAE: A Physics-Constrained Generative Audit of CT Severity Classification** :  1st author, accepted at MIUA 2026 (Springer LNCS)
- **High-frequency soil hydrothermal observations from a semi-arid monsoon catchment in southern India, 2016–2025** : 2nd author, Nature Portfolio, under revision · [dataset](https://zenodo.org/records/18409640)

## Projects

| | |
|---|---|
| [Zone-Heal](https://github.com/aaryaupadhya12/Z-heal) | RL routing for AWS availability zones : 45-state policy on production trace data, p99 cut 24% under zone degradation, deployed on ECS Fargate |
| [Self-Healing RL Harness](https://github.com/aaryaupadhya12/Z-heal) | Per-regime trust control : detects which region degraded, distinguishes policy breakage from environment shift, repairs only that region |
| [PAR-VAE](https://github.com/aaryaupadhya12/Physics-Attribute-Regularized-VAE) | Physics-regularized VAE for CT imaging : 85-dim latent space tied to 14 interpretable physics attributes, accepted MIUA 2026 |
| [GREM](https://github.com/aaryaupadhya12/GREM) | Multi-agent reasoning distilled into a 22M cross-encoder : zero LLM calls at inference |

## Stack

`PyTorch` · `PyTorch Geometric` · `HuggingFace` · `NumPy` · `Python`

---

aarya.upadhya@gmail.com
