---
layout: single
title: "Thesis"
permalink: /thesis/
author_profile: true
---
## Undergraduate Thesis

**Spectral Graph Theory and Sign Invariant Structures for Graph Transformers**
*Department of ECE, RUET &nbsp;|&nbsp; Supervised by [Md. Faysal Ahamed](https://scholar.google.com/citations?user=PLACEHOLDER)*

---
### The Sign Invariance Problem

A fundamental challenge in spectral GNNs and graph transformers is **sign ambiguity**: the eigenvectors of the Laplacian are only defined up to a sign flip — if $u_i$ is an eigenvector, so is $-u_i$. When these eigenvectors are used as **positional encodings** (PEs) for nodes, the resulting representations are not deterministic across different computations of the same graph, breaking the consistency required for learning.

This thesis addresses the problem of constructing **sign invariant** positional encodings that remain stable under this ambiguity, focusing on:
- Theoretical characterization of sign equivariant and sign invariant functions on Laplacian eigenvectors
- Analysis of spectral attention mechanisms in graph transformers through the lens of sign invariance
- Extension of the framework introduced in *"Rethinking Graph Transformers with Spectral Attention"* (MILA Canada)

---
<div style="max-width: 900px; margin: 30px auto;">
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe
      src="https://www.youtube.com/embed/Y9cl32J1zVA"
      title="A Sign Invariant and Efficient Spectral Positional Encoding for Graph Transformers"
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen>
    </iframe>
  </div>
</div>
---
