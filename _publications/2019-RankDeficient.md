---
title: "A convex relaxation to compute the nearest structured rank deficient matrix"
collection: publications
permalink: /publications/2019-RankDeficient.html
excerpt: 'We propose a novel SDP relaxation for computing rank deficient matrices in an affine subspace'
date: 2019-04-15
venue: 'preprint'
paperurl: 'https://arxiv.org/abs/1904.09661'
citation: 'Diego Cifuentes (2019). &quot;A convex relaxation to compute the nearest structured rank deficient matrix.&quot; <i>arXiv:1904.09661</i>.'
---
Given an affine space of matrices L and a matrix θ in L, consider the problem of finding the closest rank deficient matrix to θ on L with respect to the Frobenius norm. This is a nonconvex problem with several applications in estimation problems. We introduce a novel semidefinite programming (SDP) relaxation, and we show that the SDP solves the problem exactly in the low noise regime, i.e., when θ is close to be rank deficient. We evaluate the performance of the SDP relaxation in applications from control theory, computer algebra, and computer vision. Our relaxation reliably obtains the global minimizer in all cases for non-adversarial noise. 

[Download paper here](https://arxiv.org/abs/1904.09661)

See also:

* [CVX code](../software/stls_sdp.html) for constructing and solving the SDP relaxation
* [Matlab code](../files/rankdeficient.zip) for reproducing the experimental results in the paper
