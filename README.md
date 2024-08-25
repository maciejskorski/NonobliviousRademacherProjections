# Optimal Rademacher Projections

## Summary

The repository associated with the paper "Non-Oblivious Performance of Rademacher Random Embeddings".

The results improve accuracy guarantees in a data-dependent (non-oblivious) way using majorization and Schur concavity.

The more spread out the input data, the more distorted are the embeddings.

## Empirical Comparison

Monte Carlo simulations (N=1000 traces) were performed on random projections (dimension D=50) for several datasets from the SuiteSparse Matrix Collection (formerly known as the University of Florida Sparse Matrix Collection). In this context, sparsity is defined as the fraction of zero entries in a dataset. The following table summarizes the sparsity of each analyzed dataset:

| Dataset | Sparsity |
|---------|----------|
| Glass_10NN | 0.936168 |
| Ecoli_10NN | 0.960298 |
| micromass_10NN | 0.970683 |
| plantstexture_10NN | 0.991220 |
| mnist_test_norm_10NN | 0.998542 |

The following plot shows the distortion distribution tail (empirical CDF) for each dataset. 

It is seen that the higher data sparisty, the more accurate (less dispersed) projections.

<img src="./comparison (1).svg">
