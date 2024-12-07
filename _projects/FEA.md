---
layout: page
title: computational hip modeling
description: two HSS FEA studies.
img: assets/img/FEA_background.png
importance: 1
category: work
related_publications: false
---


One of the most difficult complications to address in revision total hip arthroplasties is large bone loss in the pelvis. Due to the size and variability of the defects, it is hard to use conventional, off-the-shelf implants.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA1.png" title="FEA1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

Patient-specific flanged acetabular components (FACs) are designed for such complex cases. However, it is difficult to determine the optimal combination of design and surgical decisions because there are many parameters at play.
 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA2.png" title="FEA2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

For the <a href='https://pubmed.ncbi.nlm.nih.gov/38669091/'>first study</a>, we aimed to build a novel finite element (FE) model that can predict the location and method of implant failure by determining the biomechanical effects of different variables. We chose a representative patient and utilized Mimics to reconstruct the bone geometry and obtain the materials. With insight from our team of experienced orthopaedic surgeons, we chose to model a common superomedial defect. With CAD, we created the defect in the reconstructed hip and designed a patient-specific FAC for this particular defect bone geometry.
 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA3.png" title="FEA3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

We meshed the model into ~3.6 million linear tetrahedral elements. We assumed boundary conditions and transformed implant load forces from the open-source <a href='https://orthoload.com/'>Orthoload</a> database and applied two loads on the model. For the first study, we examined the biomechanical effects of lateralizing the hip center by an additional 1 cm. For the second study, we examined the effects of different cortical shell thicknesses and ischial cancellous bone densities.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA4.png" title="FEA4" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA5.png" title="FEA5" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

We looked at the strains in the bone, the strains at the bone-implant interfaces, and the micromotions of the implant relative to the bone. In the first study, we found that additional lateralization worsened the load on the bone but it was not a catastrophic difference. In the second study, we found that a thinner cortical shell also nominally worsened the load on the bone, but the poor ischial bone quality had the most impact on risk of failure at the ischial screws. This is where clinicians often see FACs failing, so future iterations of these studies that include increasingly more realistic parameters would make this model and pipeline feasible for clinical use. With a highly robust model, the current Paprosky classification of hip defects could also be updated to account for biomechanical effects due to significant bone loss.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA6.png" title="FEA6" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEA7.png" title="FEA7" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


