---
title: Three and a half proofs of the Riemannian Penrose inequality
date: 2023-04-22 06:06:36 +/-0800
categories: [Differential Geometry, General relativity]
tags: [math.DG, gr-qc]     # TAG names should always be lowercase
---
<h2>Introduction</h2>
<p>Most of the physicists I've talked to consider the Penrose inequality of being a rather dull subject, while on the contrary, most of the mathematicians I have talked to, view this as a very neat thing in differential geometry. And this is what this <i>chirp</i> is about -- the Riemannian Penrose inequality.</p>
<p>The initial data prescription here is $\left(\Sigma , \gamma _{ij}, K _{ij}, \rho , J_{i} \right)$, where $(\Sigma , \gamma _{ij})$ is a Riemannian manifold, $K _{ij}$ is a symmetric two-tensor, and $\rho , J_{i}$ are the energy-density and the energy-flux. For this initial data set, we have the following constraint equations:</p>

$$\mathrm{Ric}^{\gamma}-\mathbf{K}+K^{2}=16\pi\rho , \quad \nabla_{j}K_{k}^{j}-\nabla_{k}\mathrm(tr)k_{\gamma}=-8\pi J_{k}$$

<p>where $\mathbf{K}$ represents $(K)_{ij}(K)^{ij}$. Schoen and Yau's seminal work on the positive mass theorem showed that unless the slice is that of a Minkowskian spacetime and the energy-density and flux are vanishing, the ADM mass of a spacetime is always positive. The asymptotic definition of a flat initial data set is straightforward, so that if a topology $A\sqcup M_{\infty}$ is given by the initial data set and $M_{\infty}\cong \mathbb{R}\backslash \mathbb{B}$, it is asymptotically flat. Further, we say that the dominant energy condition is satisfied if in some sense $\rho\geq\sqrt{\mathbf{J}}$, which we will assume throughout the <i>chirp</i>.
