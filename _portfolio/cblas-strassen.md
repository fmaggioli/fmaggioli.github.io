---
title: "CBLAS-Like Strassen's Algorithm"
excerpt: "An implementation of the Strassen's algorithm with a CBLAS-like interface<br/><img src='/images/portfolio/cblas-strassen.jpg'>"
collection: portfolio
---

A C implementation of the Strassen's algorithm for matrix multiplication.  

The implementation is based on the code of the paper *Efficiently Parallelizable Strassen-Based Multiplication of a Matrix by its Transpose*, and tries to optimize memory management and caching.  

The functions provide an interface that is inspired by the CBLAS routine `cblas_?gemm` for classical matrix multiplication, and tries to match the original signature of the function, up to the extra parameters that are needed for the function.  

The project can be found on a [GitHub repository](https://github.com/filthynobleman/cblas-strassen).
