---
title: "ReMatching: Low-Resolution Representations for Scalable Shape Correspondence"
collection: publications
category: conferences
permalink: /publication/2024-12-02-rematching
date: 2024-12-02
venue: 'European Conference on Computer Vision'
paperurl: '/files/2024-12-02-rematching.pdf'
arxivurl: 'https://arxiv.org/abs/2305.09274'
bibtexurl: '/files/2024-12-02-rematching.bib'
codeurl: 'https://github.com/filthynobleman/rematching'
teaser: '/images/publications/rematching.jpg'
doi: 'https://doi.org/10.1007/978-3-031-72913-3_11'
citation: 'Filippo Maggioli, Daniele Baieri, Emanuele Rodolà, and Simone Melzi. "Rematching: Low-resolution representations for scalable shape correspondence". <i>European Conference on Computer Vision (ECCV) 2024. Lecture Notes in Computer Science, vol 15095.</i> Springer, Cham. 2025.'
---

## Abstract
The multiplication of a matrix by its transpose, $$A^TA$$, appears as an intermediate operation in the solution of a wide set of problems. In this paper, we propose a new cache-oblivious algorithm (ATA) for computing this product, based upon the classical Strassen algorithm as a sub-routine. In particular, we decrease the computational cost to $$2/3$$ the time required by Strassen's algorithm, amounting to $$14/3n^{\mathrm{log}_2 7}$$ floating point operations. ATA works for generic rectangular matrices, and exploits the peculiar symmetry of the resulting product matrix for saving memory. In addition, we provide an extensive implementation study of ATA in a shared memory system, and extend its applicability to a distributed environment. To support our findings, we compare our algorithm with state-of-the-art solutions specialized in the computation of $$A^TA$$, as well as with solutions for the computation of the general $$A^TB$$ product applied to this problem. Our experiments highlight good scalability with respect to both the matrix size and the number of involved processes, as well as favorable performance for both the parallel paradigms and the sequential implementation when compared with other methods in the literature.


## BibTeX
```bibtex
@inoroceedings{maggioli2024rematching,
    author={Maggioli, Filippo and Baieri, Daniele and Rodol{\`a}, Emanuele and Melzi, Simone},
    title={ReMatching: Low-Resolution Representations for Scalable Shape Correspondence},
    booktitle={Computer Vision -- ECCV 2024},
    year={2025},
    publisher={Springer Nature Switzerland},
    address={Cham},
    pages={183--200},
    isbn={978-3-031-72913-3}
}
```