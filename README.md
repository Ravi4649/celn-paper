# CELN: Deterministic Logical Reasoning on CPU Without Backpropagation

**Author:** Flavio Oliveira Venturini (Independent Researcher)

## Abstract
We propose CELN (C. Elegans Learning Network), an architecture that performs first-order logical reasoning using vector algebra, without backpropagation. We develop a non-commutative binding operator (Projective Resonance) that eliminates the need for explicit role-filler binding to represent logical rules. This allows deductive chaining to occur directly via reversible matrix unbinding, reducing the complexity of logical inference in Vector Symbolic Architectures (VSA). With this foundation, we demonstrate that Q·K^T attention emerges naturally from matrix binding, without gradients. Furthermore, the system's associative memory rejects contradictions as a formal guarantee, not a statistical likelihood. We tested the architecture on the ProofWriter benchmark. CELN achieved 100% accuracy (500/500) on a standard CPU, with 34.7ms latency per deduction. The most important result lies in the "Unknown" class. While Transformer-based models force answers and hallucinate, CELN admits ignorance deterministically, without bias.

## Status
- **Pre-print Date:** June 23, 2026
- **Code:** Will be released upon acceptance.
- **Paper Submission:** Submitted to arXiv (pending endorsement).

## Citation
If you find this work useful in your research, please consider citing:

```bibtex
@article{venturini2026celn,
  title={CELN: Deterministic Logical Reasoning on CPU Without Backpropagation},
  author={Venturini, Flavio Oliveira},
  year={2026}
}
```

## Copyright
© 2026 Flavio Oliveira Venturini. All rights reserved. 
Licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0).
