---
title: "Orthogonalized Fourier Polynomials for Signal Approximation and Transfer"
collection: publications
category: manuscripts
permalink: /publication/2021-06-04-orthoprods
date: 2021-06-04
venue: 'Computer Graphics Forum - EUROGRAPHICS'
paperurl: '/files/2021-06-04-orthoprods.pdf'
supmaturl: '/files/2021-06-04-orthoprods-supmat.pdf'
bibtexurl: '/files/2021-06-04-orthoprods.bib'
codeurl: 'https://github.com/filthynobleman/orthogonalized-fourier-polynomial'
teaser: '/images/publications/orthoprods.jpg'
doi: 'https://doi.org/10.1111/cgf.142645'
citation: 'Maggioli, Filippo, et al. "Orthogonalized fourier polynomials for signal approximation and transfer." <i>Computer Graphics Forum</i>. Vol. 40. No. 2. 2021.'
---

## Abstract
We propose a novel approach for the approximation and transfer of signals across 3D shapes. The proposed solution is based on taking pointwise polynomials of the Fourier-like Laplacian eigenbasis, which provides a compact and expressive representation for general signals defined on the surface. Key to our approach is the construction of a new orthonormal basis upon the set of these linearly dependent polynomials. We analyze the properties of this representation, and further provide a complete analysis of the involved parameters. Our technique results in accurate approximation and transfer of various families of signals between near-isometric and non-isometric shapes, even under poor initialization. Our experiments, showcased on a selection of downstream tasks such as filtering and detail transfer, show that our method is more robust to discretization artifacts, deformation and noise as compared to alternative approaches.


## BibTeX
```bibtex
@inproceedings{maggioli2021orthogonalized,
  title={Orthogonalized fourier polynomials for signal approximation and transfer},
  author={Maggioli, Filippo and Melzi, Simone and Ovsjanikov, Maksim and Bronstein, Michael M and Rodol{\`a}, Emanuele},
  booktitle={Computer Graphics Forum},
  volume={40},
  number={2},
  pages={435--447},
  year={2021},
  organization={Wiley Online Library}
}
```