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
citation: 'Maggioli Filippo, et al. "Rematching: Low-resolution representations for scalable shape correspondence". <i>European Conference on Computer Vision (ECCV) 2024. Lecture Notes in Computer Science, vol 15095.</i> Springer, Cham. 2025.'
---

## Abstract
We introduce ReMatching, a novel shape correspondence solution based on the functional maps framework. Our method, by exploiting a new and appropriate re-meshing paradigm, can target shape-matching tasks even on meshes counting millions of vertices, where the original functional maps does not apply or requires a massive computational cost. The core of our procedure is a time-efficient remeshing algorithm which constructs a low-resolution geometry while acting conservatively on the original topology and metric. These properties allow translating the functional maps optimization problem on the resulting low-resolution representation, thus enabling efficient computation of correspondences with functional map approaches. Finally, we propose an efficient technique for extending the estimated correspondence to the original meshes. We show that our method is more efficient and effective through quantitative and qualitative comparisons, outperforming state-of-the-art pipelines in quality and computational cost.


## BibTeX
```bibtex
@inproceedings{maggioli2024rematching,
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