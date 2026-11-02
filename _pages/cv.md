---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<style>
#conferences-i-attended + ul li {
  margin-top: 0.3em !important;
  margin-bottom: 0.3em !important;
}

#conferences-i-attended + ul ul,
#conferences-i-attended + ul p {
  margin-top: 0.3em !important;
  margin-bottom: 0.3em !important;
}

#conferences-i-attended + ul > li {
  margin-bottom: 0.3em !important;
}
</style>

Education
======
* Junior high school: NanJing 29th Middle School Junior High School, 2019-2022
* Learn German, 2022-2023
* High School: Stiftung Louisenlund, 2023-2027

Work experience
======
* Spring 2023: Math teaching assistant
  * NanJing
  * Duties includes: Providing Math help and Math instruction
  * Supervisor: Nobody

* Summer 2025: Research Intern – Real Algebraic Geometry
  * Institute of Geometry, Faculty of Mathematics, TU Dresden (Dresden University of Technology)
  * Duties includes: [A project about real algebraic geometry](https://nimoseminov.github.io/publication/2025-07-05-topologische-klassifikation-kubischer-flaechen-julia)
  * Supervisor: [Prof. Mario Kummer](https://tu-dresden.de/mn/math/geometrie/kummer) ([mario.kummer@tu-dresden.de](mailto:mario.kummer@tu-dresden.de))

Journal Articles / Preprints / Project Reports
======

<ul>
{% assign article_posts = site.publications | where_exp: "post", "post.path contains '_publications/Journal_Preprint/'" %}
{% for post in article_posts reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

{% assign report_posts = site.publications | where_exp: "post", "post.path contains '_publications/Project_Report/'" %}
{% for post in report_posts reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>


Projects
======
* Summer 2025 - Topological Classification of Real del Pezzo surfaces of degree 3 and 4 in $$\mathbb{RP}^3$$ and $$\mathbb{RP}^4$$ via Counting Real Lines Using Julia
  * Project Page: [Topological Classification of Cubic Surfaces in Three-Dimensional Real Projective Space based on Julia Implementations: 5 Case Studies (German)](https://nimoseminov.github.io/publication/2025-07-05-topologische-klassifikation-kubischer-flaechen-julia)
  * Code and Github repository: [Julia Code](https://github.com/nimoseminov/Real-Lines-on-Del-Pezzo-Surfaces-of-Degree-3-and-4-in-RP3-and-RP4)


Upcoming Activities
======
- [Research Seminar on Algebraic Topology](https://www.math.uni-hamburg.de/forschung/bereiche/az/topologie/lehre/research-seminar.html),
  Universität Hamburg, Germany, Summer Semester 2027
  (Seminar talk; exact date to be confirmed).
  
Conferences I attended
======
- [Positive Geometry Beyond Physics](https://www.mis.mpg.de/events/series/positive-geometry-beyond-physics), October 2026.
- [Interactions between operator algebras, K-theory and homotopy theory](https://www.uni-muenster.de/MathematicsMuenster/events/2026/interactions-between-operator-algebras-k-theory-homotopy-theory.shtml), September 2026.
- [Conference on "New Perspectives on Stable Homotopy and Beyond"](https://www.mpim-bonn.mpg.de/nps60), September 2026.
- [Stratifying Kiel: Stratified Spaces from Higher Category Theory to Applied Topology](https://www.math.uni-kiel.de/geometrie/de/essig/stratKiel2026/), September 2026.
- [International Conference on Geometry, Integrability and Quantization](https://geometry.imbm.bas.bg/conference/), June 2026.
  

  
Service and leadership
======
* No, but may be in the future.


Skills and interests
======
* Mathematics / Mathematik / Mатематика
  * [Hochschild-Kostant-Rosenberg theorem](https://ncatlab.org/nlab/show/Hochschild-Kostant-Rosenberg+theorem), [De Rham cohomology](https://en.wikipedia.org/wiki/De_Rham_cohomology), Algebraic Topology, Algebraic Geometry, and Derived Geometry
* Programming & Computational Tools
  * Julia, C++, MATLAB, Mathematica, LaTeX
* language
  * English (fluent; used in academic writing and international competitions)
  * German (fluent; schooling and academic communication)
  * Russian (informal and reading)
  * Chinese (native)
* Play the violin / Geige spielen / скрипки
