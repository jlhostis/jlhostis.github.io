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
* **Post-Doc** at Laboratoire George Friedel (LGF, École des Mines de Saint-Étienne) **"Development of C and N-doped high entropy alloys and comparison between the conventional and LPBFed microstructure and mechanical properties"** *(Jun. 2025 - present)*
  * Optimization of equilibrium alloy composition with TC-Python
  * Comparison of microstructures and mechanical properties between cast/wrought and LPBFed Co-free HEAs with C, N and C/N doping

* **PhD Candidate** at Unité Matériaux et Transformations (UMET, Centrale Lille): **"Microstructure evolution during wire-arc additive manufacturing of a martensitic stainless steel: coupling between experience and modelisation"** *(Oct. 2021 - Apr. 2025)*
  * **Complete multiscale characterization of WAAMed thin walls** to understand the microstructure formation mechanisms during the building process:
    * Microstructure overview: OM, XRD, dilatometry, SEM, EBSD, TEM, APT
    * Post-processing of EBSD maps: grain size statistics, parent austenite grain reconstruction with MTEX
    * Mechanical testing: hardness, tensile tests
  * **FORTRAN phase-field code adaptation and development** for the coupled modeling of the martensite transformation and the diffusion of carbon during AM thermal cycles: 
    *  Bain variants martensitic transformation simulation
    *  Full CALPHAD description of phases for temperature and composition dependencies
  * **Teaching and supervision**
    * Supervision of a 5th year engineer intern
    * Teaching assistant at Polytech Lille: delivery of lecture on "Material and energy balances for industrial processes" to 3rd year students (2h), tutoring (6h) and exam grading
    * Participation to the "Fête de la science 2024"
  * **Scientific communication**
    * 2 oral presentations at national and international conferences
    * Writing and submission of an experimental research article, and writing of a simulation research article
    * Organisation and presentations at internal seminars with non-permanent staff
    * Participation in the organization of the *Matériaux 2022* congress in Lille

* **FabLab Manager** at Polytech Lille's FabLab ([the fabricarium](https://fabricarium-fabmanager.polytech-lille.fr/)) *(May 2019 - Apr. 2021)*
  * Teaching machine operation (3D printer, laser cutting machine, digital embroidery machine, workshop tools)
  * Project guidance

* **Intern** at Kherys Group (Tourcoing) *(Jun. 2019 - Jul. 2019)*
  * Realization of the [assembly manual](https://shop.tizyx.fr/telecharger/evy_montage.pdf) 2 and design of structural elements of a 3D printer
  
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
