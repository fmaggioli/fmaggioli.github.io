---
title: "Geometric aware local optimization for robust primitive fitting"
collection: publications
category: conferences
permalink: /publication/2025-11-28-superquadrics
date: 2025-11-27
venue: 'Smart Tools and Applications in Graphics'
paperurl: '/files/2025-11-28-superquadrics.pdf'
bibtexurl: '/files/2025-11-28-superquadrics.bib'
teaser: '/images/publications/superquadrics.jpg'
doi: 'https://doi.org/10.2312/stag.20251321'
citation: 'Ferraris Andrea, et al. "Geometric aware local optimization for robust primitive fitting". <i>Smart Tools and Applications in Graphics-Eurographics Italian Chapter Conference</i>. 2025.'
---

## Abstract
The decomposition of 3D point clouds into meaningful geometric primitives is a longstanding challenge in Computer Vision and Computer Graphics. While recent advances in data-driven methods and neural representations have achieved significant progress in 3D reconstruction and abstraction, traditional primitive-based representations remain invaluable for tasks requiring interpretability, compactness, and robustness. This work introduces a novel framework for primitive decomposition in 2D and 3D point clouds, designed to cope with noise, outliers, and overlapping structures. Building upon traditional RANSACbased approaches, the proposed method integrates geometric priors to enhance its effectiveness in identifying interpretable and meaningful geometric primitives within complex data. Central to our approach is a novel geometric-aware inlier refinement step, which incorporates geometric constraints such as surface completeness and normal consistency. This refinement step is formulated as an optimization problem solved through the GRAPH-CUT algorithm. This optimization process penalizes excessive surface extensions and promotes coherence in normal orientations, ensuring that the refined inlier sets closely match the geometric structures the point cloud represents. Experiments on synthetic and real-world datasets validate the robustness and accuracy of the proposed method, demonstrating its ability to outperform state-of-the-art techniques in terms of both result quality and computational efficiency.


## BibTeX
```bibtex
@inproceedings{ferraris2025geometric,
booktitle = {Smart Tools and Applications in Graphics - Eurographics Italian Chapter Conference},
editor = {Comino Trinidad, Marc and Mancinelli, Claudio and Maggioli, Filippo and Romanengo, Chiara and Cabiddu, Daniela and Giorgi, Daniela},
title = {{Geometric aware local optimization for robust primitive fitting}},
author = {Ferraris, Andrea and Leveni, Filippo and Baieri, Daniele and Maggioli, Filippo and Melzi, Simone and Magri, Luca},
year = {2025},
publisher = {The Eurographics Association},
ISSN = {2617-4855},
ISBN = {978-3-03868-296-7},
DOI = {10.2312/stag.20251321}
}
```