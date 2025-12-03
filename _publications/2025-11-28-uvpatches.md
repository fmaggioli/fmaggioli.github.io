---
title: "UV Parametrization via Topological Disk Segmentation of Surfaces"
collection: publications
category: conferences
permalink: /publication/2025-11-28-uvpatches
date: 2025-11-28
venue: 'Smart Tools and Applications in Graphics'
paperurl: '/files/2025-11-28-uvpatches.pdf'
bibtexurl: '/files/2025-11-28-uvpatches.bib'
codeurl: 'https://github.com/filthynobleman/disk-segmentation'
teaser: '/images/publications/uvpatches.jpg'
doi: 'https://doi.org/10.2312/stag.20251323'
citation: 'Maggioli Filippo, et al. "UV Parametrization via Topological Disk Segmentation of Surfaces". <i>Smart Tools and Applications in Graphics-Eurographics Italian Chapter Conference</i>. 2025.'
---

## Abstract
We present a reliable method for UV mapping that leverages a Voronoi-based decomposition of a triangulated surface mesh. Given a sparse set of sample points on the input shape, we construct the corresponding Voronoi partition and iteratively refine it to ensure that all regions are topologically equivalent to disks. The refinement proceeds in two stages: first, Voronoi cells are subdivided until disk-like topology is guaranteed; then, adjacent regions sharing substantial boundary portions are merged to reduce both their total number and perimeter-to-area ratio, while preserving disk equivalence. This topological guarantee enables straightforward and reliable UV parameterization. Our method exhibits an extremely low failure rate, making it suitable for practical use. In quantitative experiments on standard UV mapping benchmarks, we achieve performance comparable to state-of-the-art techniques. Furthermore, we analyze robustness and efficiency across different sampling densities, providing insights into the computational cost of each step of the pipeline.


## BibTeX
```bibtex
@inproceedings{maggioli2025uv,
booktitle = {Smart Tools and Applications in Graphics - Eurographics Italian Chapter Conference},
editor = {Comino Trinidad, Marc and Mancinelli, Claudio and Maggioli, Filippo and Romanengo, Chiara and Cabiddu, Daniela and Giorgi, Daniela},
title = {{UV Parametrization via Topological Disk Segmentation of Surfaces}},
author = {Maggioli, Filippo and Melzi, Simone},
year = {2025},
publisher = {The Eurographics Association},
ISSN = {2617-4855},
ISBN = {978-3-03868-296-7},
DOI = {10.2312/stag.20251323}
}
```