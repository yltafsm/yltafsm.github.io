---
layout: post
title: Helicopter Model and Computational Domain
date: 2024-11-22 12:00:00
description: A toy helicopter model
tags: helicopter
---

The model is purchased from [3dmodel.org](https://3dmodels.org/3d-models/airbus-helicopters-h160/#reviews).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/helicopters/HeliGeometry/heliblade.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/helicopters/HeliGeometry/helicopter.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Helicopter Model
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/helicopters/HeliGeometry/helirotor.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/helicopters/HeliGeometry/heliball.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/helicopters/HeliGeometry/helifuture.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

Computational domain. Slip interface (SI) for high-resolution mesh representation of boundary layer (_Green_), and SI for rotor and helicopter motion (_Transparent_)

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/helicopter/202307-blade-onboard.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/helicopter/202307-blades.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/helicopter/202307-rotor.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/helicopter/202311-mesh.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

Cyclic control. The videos show pitch angle changes at different azimuth angles during one rotation.
