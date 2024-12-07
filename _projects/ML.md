---
layout: page
title: time series analysis
description: MEng ML study.
img: assets/img/ML_background.png
importance: 3
category: work
---

Background: For patients with advanced heart failure, heart transplants are ideal but rare due to the scarcity of organ donors. Ventricular assist devices (VADs) are the only alternative but can cause hemostatic complications, such as thrombosis (blood clotting). A tool that can predict the behavior of platelet aggregates at a later point in time could be crucial to helping prevent thrombosis from becoming fatal. As thrombosis is a complex biological phenomenon with nonlinear spatiotemporal characteristics, we simplified the problem to determine whether it was feasible to develop a deep learning model to reasonably predict the size and location of moving ellipses.

Methodology: My wonderful lab colleague created MATLAB algorithms to generate videos of moving and/or shrinking/expanding ellipses.

I conducted background research in particle tracking, time series analysis, and commonly used deep learning models (DFFNN, CNN, RNN, hybrid) in biomedical imaging applications. I chose the LSTM RNN as the most suitable model and developed it predict the size and location of the ellipses at a later point in time. The model was trained on <a href='projects/pc'>suitable hardware</a>.

Results: The root mean squared percentage errors (RMSPEs) were, on average, about 8% and all less than 10%, indicating accurate forecasting. The loss curves had some noise at times, suggesting that the algorithm can be further improved.

Limitations: Since this was a feasibility study, the LSTM RNN was a standard model and was trained on a small dataset. However, the study showed that developing such deep learning tools for simulated biomedical applications could be done and creating an algorithm from start to finish was an invaluable experience.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ML1.png" title="ML1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ML2.png" title="ML2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ML3.jpg" title="ML3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ML4.png" title="ML4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption.
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption.
</div>

    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```
{% raw %}
{% endraw %}
