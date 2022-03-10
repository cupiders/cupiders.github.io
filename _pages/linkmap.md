---
layout: archive
title: "Related Websites"
permalink: /linkmap/
author_profile: false
feature_row:
  - image_path: /assets/images/SALOME_screenshot.png
    alt: "SALOME screenshot"
    title: "Preprocessor: SALOME"
    excerpt: '**SALOME** is an open-source software that provides a generic Pre- and Post-Processing platform for numerical simulation. As a preprocessor, SALOME provides versatile functionalities for creation, visualization and modification of geometric CAD models. **SMESH**(Mesh module in SALOME) is to create meshes on the basis of geometrical models created or imported into SALOME. It uses a set of meshing algorithms and their corresponding conditions (hypotheses) to compute meshes. In addition, a new mesher can be easily connected to this module by using the existing plugin mechanism.'
    url: "https://www.salome-platform.org/?page_id=15"
    btn_label: "Go to Downloads"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/paraview_image.jpeg
    alt: "PARAVIEW screenshot"
    title: "Postprocessor: PARAVIEW"
    excerpt: '**ParaView** is an open-source, multi-platform data analysis and visualization application. CUPID users can quickly build visualizations to analyze their data based on ParaView post processing. The data exploration can be done interactively in 3D or programmatically using ParaView’s batch processing capabilities.'
    url: "https://www.paraview.org/download/"
    btn_label: "Go to Downloads"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/KAERI_logo.png
    alt: "KAERI image"
    title: "Organization: KAERI"
    excerpt: 'The Korea Atomic Energy Research Institute (KAERI), a government-funded research institute established in accordance with "the Act on the Establishment, Operation and Fostering of Government-funded Science and Technology Research Institutes, etc.," contributes to academic advancement, energy acquisition, and utilization of nuclear energy through active research and development in related fields.'
    url: "https://www.kaeri.re.kr/eng/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/KINS_logo.png
    alt: "KINS image"
    title: "Cooperation: KINS"
    excerpt: 'KINS is a dedicated technical expert organization for nuclear safety regulation established to protect the public from radiation disasters arising from production and utilization of nuclear energy and to contribute to public safety and environment conservation.'
    url: "https://www.kins.re.kr/en/index"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

<!-- {% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %} -->

<!-- {% include feature_row id="intro" type="center" %} -->

{% include feature_row type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}