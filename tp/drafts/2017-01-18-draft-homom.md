---
layout: post
title: "Sheaf Homomorphisms"
description: ""
category: 
tags: []
---
$\newcommand{\F}{\mathscr{F}}$ $\newcommand{\A}{\mathscr{A}}$ $\newcommand{\sheaf}{(\mathscr{A},\pi,X)}$ $\newcommand{\B}{\mathscr{B}}\newcommand{\G}{\Gamma}$
<!---LaTeX-->
There are two ways of looking at sheaf homomorphisms. At the level of spaces of section $\G(U,\F)$. Or at the level of at every point $p\in X$ and invlolve stalks. 

#### At the level of $\G$:
Here, $\G(U,\A)$ is the group of sections of $\A$ over $U$. 

>**Definition 0.1**. A homomorphism $\phi:\A\rightarrow \B$  is a collection of morphisms $\phi_U:\G(U,\A)\rightarrow \G(U,\B)$ that commute with $\rho^U_V$ for both $\A$ and $\B$. That is, the following diagram is commutative.

#### The Stalk (local) way

>**Definition 0.2**. Let $(\A,p,X)$ and $(\B,\pi,X)$ be sheaves of abelian groups on $X$. Then $h:(\A,p,X)\rightarrow (\B,\pi,X)$ is a sheaf homomorphism if
>
> 1. For all $x\in X$, the map $h_x:\A_x \rightarrow \B_x$ is a group homomorphism.
> 2. Every stalk $\A_x$ is mapped to $\B_x$;i.e., $\pi=ph$ as $\A_x=\pi^{-1}(x)$.
> 3. $h$ is a continuous map from $\A$ to $\B$. 

