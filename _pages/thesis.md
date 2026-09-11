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

## Graph Neural Networks

Graph Neural Networks (GNNs) are a class of deep learning architectures designed to operate directly on graph-structured data. Unlike standard neural networks that assume i.i.d. input, GNNs exploit the relational structure of graphs — encoding information about nodes, edges, and their neighborhoods — to learn powerful representations.

The central operation in most GNNs is **message passing**: each node aggregates feature information from its local neighborhood, transforms it, and updates its own representation. Stacking multiple such layers allows information to propagate across increasingly large neighborhoods.

### Spectral Graph Theory & GNNs

Spectral GNNs ground their operations in the **eigendecomposition of the graph Laplacian** $L = D - A$, where $D$ is the degree matrix and $A$ is the adjacency matrix. The normalized Laplacian $\tilde{L} = I - D^{-1/2}AD^{-1/2}$ has a full set of real eigenvalues $0 = \lambda_1 \leq \lambda_2 \leq \cdots \leq \lambda_n$ and corresponding eigenvectors $U = [u_1, u_2, \ldots, u_n]$.

Graph convolution in the spectral domain is defined as:

$$g_\theta \star x = U \cdot g_\theta(\Lambda) \cdot U^T x$$

where $g_\theta(\Lambda)$ is a learnable spectral filter applied to the eigenvalues. This formulation connects GNNs to classical signal processing on graphs.

### The Sign Invariance Problem

A fundamental challenge in spectral GNNs and graph transformers is **sign ambiguity**: the eigenvectors of the Laplacian are only defined up to a sign flip — if $u_i$ is an eigenvector, so is $-u_i$. When these eigenvectors are used as **positional encodings** (PEs) for nodes, the resulting representations are not deterministic across different computations of the same graph, breaking the consistency required for learning.

This thesis addresses the problem of constructing **sign invariant** positional encodings that remain stable under this ambiguity, focusing on:

- Theoretical characterization of sign equivariant and sign invariant functions on Laplacian eigenvectors
- Analysis of spectral attention mechanisms in graph transformers through the lens of sign invariance
- Extension of the framework introduced in *"Rethinking Graph Transformers with Spectral Attention"* (MILA Canada)

---

*This page will be updated progressively as the thesis develops.*
