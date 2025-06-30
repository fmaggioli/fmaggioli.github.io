---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* March 2025 &ndash; Present: **Assistant professor &mdash; tenure track**
  * Pegaso University
  * Department of Computer Science and Information Technologies

* December 2023 &ndash; February 2025: **Postdoctoral researcher**
  * University of Milano-Bicocca
  * Advisor: Prof. Simone Melzi
  * Research activity on computational and spectral geometry.

* April 2024 &ndash; February 2025: **Adjunct professor**
  * Pegaso University
  * Undergrad courses on *Computer Achitecture* and *Networking and Cybersecurity*.

* August 2023 &ndash; November 2023: **Postdoctoral researcher**
  * Sapienza &ndash; University of Rome
  * Advisor: Prof. Emanuele Rodolà
  * Research activity on computational geometry, spectral geometry, and numerical linear algebra.

* September 2022 &ndash; January 2023: **Research internship**
  * King Abdullah University of Science and Technology
  * Advisor: Prof. Dominik L. Michels
  * Research activity on simulation of natural phenomena in agricultural settings.

* March 2021 &ndash; July 2021: **Teaching assistant**
  * Sapienza &ndash; University of Rome
  * Undergrad course on *Introduction to Algorithms*.

Education
======
* November 2019 &ndash; September 2023: Ph.D in Computer Science
  * Sapienza &ndash; University of Rome
  * Advisor: Prof. Emanuele Rodolà
  * Thesis title: *Scalable geometry processing for computer graphics applications*.
  * **Honourable mention at EG-Italy Award for PhD Thesis in Computer Graphics**
* January 2018 &ndash; July 2019: M.Sc. in Computer Science
  * Sapienza &ndash; University of Rome
  * Advisor: Prof. Emanuele Rodolà
  * Thesis title: *Time-efficient function reconstruction via Laplacian eigenproducts*.
* Semptember 2014 &ndash; December 2017: B.Sc. in Computer Science
  * Sapienza &ndash; University of Rome
  * Advisor: Prof. Enrico Tronci
  * Thesis title: *Modeling of biological pathways with systems of differential-algebraic equations*.

Selection of students
======
* Daniele Baieri, Ph.D. &mdash; Internal supervisor (not formal advisor)
* Giulio Viganò, Ph.D. &mdash; Internal supervisor (not formal advisor)
* Francesca Maccarone, Ph.D. &mdash; Internal supervisor (not formal advisor)
* Francesco De Canio, Ph.D. &mdash; Internal supervisor (not formal advisor)
* Giorgio Longari, M.Sc. &mdash; Internal supervisor (not formal advisor)
* Simone Pedico, B.Sc. &mdash; Thesis co-advisor

Publications
======
  <ul>{% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2>
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single-cv.html %}
    {% endfor %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
