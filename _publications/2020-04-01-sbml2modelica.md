---
title: "SBML2Modelica: integrating biochemical models within open-standard simulation ecosystems"
collection: publications
category: manuscripts
permalink: /publication/2020-04-01-sbml2modelica
date: 2020-04-01
venue: 'Bioinformatics'
paperurl: '/files/2020-04-01-sbml2modelica.pdf'
arxivurl: 'https://arxiv.org/abs/2106.02609'
bibtexurl: '/files/2020-04-01-sbml2modelica.bib'
codeurl: 'https://bitbucket.org/mclab/sbml2modelica/src/master/'
teaser: '/images/publications/sbml2modelica.jpg'
citation: 'Maggioli Filippo et al. "SBML2Modelica: integrating biochemical models within open-standard simulation ecosystems." <i>Bioinformatics</i> 36.7 (2020): 2165-2172.'
---

Beginning with the abstract is maybe the issue?  

## Abstract
SBML is the most widespread language for the definition of biochemical models. Although dozens of SBML simulators are available, there is a general lack of support to the integration of SBML models within open-standard general-purpose simulation ecosystems. This hinders co-simulation and integration of SBML models within larger model networks, in order to, e.g. enable in silico clinical trials of drugs, pharmacological protocols, or engineering artefacts such as biomedical devices against Virtual Physiological Human models. Modelica is one of the most popular existing open-standard general-purpose simulation languages, supported by many simulators. Modelica models are especially suited for the definition of complex networks of heterogeneous models from virtually all application domains. Models written in Modelica (and in 100+ other languages) can be readily exported into black-box Functional Mock-Up Units (FMUs), and seamlessly co-simulated and integrated into larger model networks within open-standard language-independent simulation ecosystems.
In order to enable SBML model integration within heterogeneous model networks, we present SBML2Modelica, a software system translating SBML models into well-structured, user-intelligible, easily modifiable Modelica models. SBML2Modelica is SBML Level 3 Version 2—compliant and succeeds on 96.47% of the SBML Test Suite Core (with a few rare, intricate and easily avoidable combinations of constructs unsupported and cleanly signalled to the user). Our experimental campaign on 613 models from the BioModels database (with up to 5438 variables) shows that the major open-source (general-purpose) Modelica and FMU simulators achieve performance comparable to state-of-the-art specialized SBML simulators.


## BibTeX
```bibtex
@article{maggioli2020sbml2modelica,
  title={SBML2Modelica: Integrating biochemical models within open-standard simulation ecosystems},
  journal={Bioinformatics},
  volume={36},
  number={7},
  pages={2165--2172},
  year={2020},
  publisher={Oxford University Press}
}
```