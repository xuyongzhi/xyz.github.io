---
layout: page
title: Short-and long-term performance of TTC floor system
description: 
img: assets/img/publication_preview/TTC-pushout.png
importance: 1
category: work
---
In this project, short-term pushout tests were performed on LVL/GLT beam to CLT slab joints (with
coach screw shear connectors) to characterise the load-slip, peak load, and failure mode
of the joints.Furthermore, material tests were conducted on timber and the screws, and
the results were used to build a versatile beam on inelastic foundation finite element (FE)
model and predict the full range load-slip response of the TTC joints.

To assess the long-term performance of the TTC system, twelve TTC joints and eight
full-scale TTC beams were fabricated by connecting LVL/GLT beams to CLT slabs. The
TTC joints and beams were subjected to sustained (constant) loads and monitored under
an indoor uncontrolled environment for over 500 days. The test results revealed the major
influence of the CLT slab thickness and orientation (crosswise or lengthwise), shear
connector types/sizes and CLT slab continuity (segmentation) on the long-term
performance of the TTC joints and beams. 

Lastly, a 3D fully coupled finite element (FE) model implemented as user-defined subroutines in ABAQUS/Standard was
validated against the TTC joints and beams long-term test results and accordingly input
parameters for long-term FE simulations of the LVL-CLT and GLT-CLT composites
(with screw shear connectors) are recommended.


## Short-term 


<div class="row">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Configuration-geometry-of-TTC-pushout.png" title="Configuration, geometry, and dimensions of the TTC push out joints" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/failure-modes-TTC.png" title="Failure modes of pushout test" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Configuration, geometry, and dimensions of the TTC push out joints. Right: Failure modes of pushout test.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Beam-on-elastic-foundation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Beam on elastic/inelastic foundation model for a dowel connector in a TTC joint loaded lengthwise.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TTC-FE-Test-Compare.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Comparison of FE model and EC5 model predictions with experimental results.
</div>

## Long-term

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/long-term-FE-pushout.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/long-term-pushout-result.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Outline of the FE model. Right:Slip versus time obtained from the FE simulations and long-term tests (over 420 days).
</div>


The 3D coupled FE models can adequately capture the long-term behaviour of TTC joints with screw shear connectors under sustained load and variable environmental condition.

