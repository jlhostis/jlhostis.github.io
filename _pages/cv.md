---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[PDF version](http://jlhostis.github.io/files/CV/CV_jlh_20250501.pdf) (05/2025)

Education
======
* **Ph.D in Materials Science,** Centrale Lille, France, 2025
  * "Microstructure evolution during wire-arc additive manufacturing of a martensitic stainless steel: coupling between experience and modelisation" ([theses.fr](https://theses.fr/s306187))
  * Under supervision of Marie-Noëlle Avettand-Fènoël and Ludovic Thuinet at [UMET](http://https://umet.univ-lille.fr/) lab
* **Dipl. Ing. in Materials Science,** Polytech Lille, France, 2021

Work experience
======
<!-- * *06/2025-present:* Post-Doc at Laboratoire George Friedel (LGF, École des Mines de Saint-Étienne) **"Development of C and N-doped high entropy alloys and comparison between the conventional and LPBFed microstructure and mechanical properties"**
  * Optimization of equilibrium alloy composition with TC-Python
  * Comparison of microstructures and mechanical properties between cast/wrought and LPBFed Co-free HEAs with C, N and C/N doping -->

* *10/2021-04/2025:* PhD at Unité Matériaux et Transformations, (UMET, Centrale Lille) **"Microstructure evolution during wire-arc additive manufacturing of a martensitic stainless steel: coupling between experience and modelisation"**
  * Complete multiscale characterization of WAAMed thin walls to understand the microstructure formation mechanisms during the building process: microstructure overview, post-processing of EBSD maps, mechanical testing
  * FORTRAN phase-field code adaptation and development for the coupled modeling of the martensite transformation and the diffusion of carbon during AM thermal cycles: 2 Bain variants martensitic transformation simulation, full CALPHAD description of phases for temperature and composition dependencies
  * Teaching and supervision
  * Scientific communication

* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======

* **Languages:**
  * **English:** fluent, C1 level, 960/990 TOEIC score in 2020
  * **Spanish:** basic proficiency, A2 level
  * **French:** native, maternal **language**

* **Computer Skills:**
  * **Software & tools:** LATEX (+++), Office suite (+++), GIMP/Photoshop (+++), Inkscape/Illustrator (+++), Gnuplot (+++), Fiji (ImageJ) (++), Matplotlib (++), MATLAB (+)
  * **CAD & Materials Science:** Aztec Channel 5 (+++), MTEX/ORTools (+++), Thermo-Calc (+++), TC-Python (++), DICTRA (+) CATIA V5 (++), Fusion 360 (++), GRANTA (+), ANSYS Workbench (+), Fullprof (+)
  * **Programming Languages:** Python (+++), FORTRAN (++), Bash (++), C (+)

* **Technical skills in Materials Science:**
  * **Microsctructural characterization:** OM (metallography), XRD, SEM (BSE, EDX), EBSD (sample preparation, post-processing with MTEX), TEM (STEM, EDX-STEM, sample preparation via electropolishing)
  * **Mechanical characterization:** Vickers micro-hardness, tensile testing, Charpy testing


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
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
