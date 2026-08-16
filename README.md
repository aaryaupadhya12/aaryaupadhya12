## Aarya Upadhya

4th-year CS (AI/ML) at PES University, Bengaluru.

I work on memory and representation in neural networks — what gets stored, where,
and whether it survives. Currently: whether domain knowledge can live in the
initial recurrent state of a linear-attention model instead of its weights.

---

### Publications

- **PAR-VAE: A Physics-Constrained Generative Audit of CT Severity Classification** — 1st author, accepted at MIUA 2026 (Springer LNCS)
- **High-frequency soil hydrothermal observations from a semi-arid monsoon catchment in southern India, 2016–2025** — 2nd author, Nature Portfolio, under revision · [dataset](https://zenodo.org/records/18409640)

---

### Projects

**[PAR-VAE](https://github.com/aaryaupadhya12/Physics-Attribute-Regularized-VAE)** — physics-regularized VAE for CT imaging
Ties an 85-dim latent space to 14 interpretable physics attributes (density, geometry,
texture). Studies the interpretability/accuracy tradeoff, and finds that much of the
remaining gap to a black-box CNN at milder disease stages appears data-intrinsic
rather than a modelling limitation.

**[GREM](https://github.com/aaryaupadhya12/GREM)** — distilling multi-agent LLM reasoning into a small re-ranker
Gemini agents generate reasoning about multi-hop retrieval failures during training;
verified chains go to MongoDB Atlas; a 22M cross-encoder learns from them and runs
with no LLM calls at inference. Built for the Google Cloud Rapid Agent Hackathon.
README documents what the evaluation does and doesn't establish.

**[KG-EVOLVE](https://github.com/aaryaupadhya12/KG-EVOLVE)** — episodic memory over frozen KG embeddings
Multi-agent reasoning on top of frozen ComplEx embeddings, with writeback gated on
validation. Found a failure mode where early low-quality memories skew later reasoning.

**[BGSAVM](https://github.com/aaryaupadhya12/BGSAVM)** — graph-based patch selection for 3D point clouds
Uses evidential uncertainty and motif participation to choose patches, with a ViG
backbone over unstructured 3D geometry.

---

### Stack

`PyTorch` · `PyTorch Geometric` · `HuggingFace` · `NumPy` · `Python`

---

aarya.upadhya@gmail.com
