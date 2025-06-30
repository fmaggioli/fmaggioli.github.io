---
title: "Implicit-ARAP: Efficient Handle-Guided Deformation of High-Resolution Meshes and Neural Fields via Local Patch Meshing"
collection: publications
category: preprints
permalink: /publication/2024-10-30-implicitarap
date: 2024-10-30
venue: 'arXiv'
paperurl: '/files/2024-10-30-implicitarap.pdf'
arxivurl: 'https://arxiv.org/abs/2405.12895'
bibtexurl: '/files/2024-10-30-implicitarap.bib'
teaser: '/images/publications/implicit-arap.png'
citation: 'Baieri Daniele, et al. "Implicit-ARAP: Efficient Handle-Guided Deformation of High-Resolution Meshes and Neural Fields via Local Patch Meshing." <i>arXiv preprint arXiv:2405.12895</i>. 2024.'
---

## Abstract
In this work, we present the local patch mesh representation for neural signed distance fields. This technique allows to discretize local regions of the level sets of an input SDF by projecting and deforming flat patch meshes onto the level set surface, using exclusively the SDF information and its gradient. Our analysis reveals this method to be more accurate than the standard marching cubes algorithm for approximating the implicit surface. Then, we apply this representation in the setting of handle-guided deformation: we introduce two distinct pipelines, which make use of 3D neural fields to compute As-Rigid-As-Possible deformations of both high-resolution meshes and neural fields under a given set of constraints. We run a comprehensive evaluation of our method and various baselines for neural field and mesh deformation which show both pipelines achieve impressive efficiency and notable improvements in terms of quality of results and robustness. With our novel pipeline, we introduce a scalable approach to solve a well-established geometry processing problem on high-resolution meshes, and pave the way for extending other geometric tasks to the domain of implicit surfaces via local patch meshing.


## BibTeX
```bibtex
@article{baieri2024implicit,
  title={Implicit-ARAP: Efficient Handle-Guided Deformation of High-Resolution Meshes and Neural Fields via Local Patch Meshing},
  author={Baieri, Daniele and Maggioli, Filippo and L{\"a}hner, Zorah and Melzi, Simone and Rodol{\`a}, Emanuele},
  journal={arXiv preprint arXiv:2405.12895},
  year={2024}
}
```