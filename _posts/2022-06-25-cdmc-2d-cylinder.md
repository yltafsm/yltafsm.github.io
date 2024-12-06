---
layout: post
title: First 2D Long-Wake Flow Computation
date: 2022-06-25 12:00:00
description: Flow Past a 2D Cylinder
tags: "wake-flow"
categories: CDM ST-Method ST-SUPS ST-VMS IGA
featured: true
related_publications: true
---

<div class="row mt-3">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/cdm/cd-pressure.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/cdm/cd-velocity-u.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/cdm/cd-velocity-v.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
   Pressure (<em>left</em>), streamwise velocity (<em>middle</em>), and crossflow velocity (<em>right</em>) in Carrer-Domain with different sizes. The long domain in the bottom is for comparison purpose 
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/cdm/CDM-C_2K.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

The first 2D long-wake flow carried out with CDM {% cite LiuYang22b %} and [ST-IGA](https://link.springer.com/article/10.1007/s00466-024-02535-8). The computation was for 2D flow past a cylinder at Reynolds number 100, with the long-wake flow computed up to 350 diameters downstream of the cylinder, far enough to see the secondary vortex street. The long-wake domain computed with the [Multi-Domain Method](https://www.researchgate.net/publication/223865289) (MDM) is for comparison purpose. This video won "The Best CFD Graphics Award" in the 37th Fluid Dynamics Symposium held by the Japan Society of Fluid Mechanics (December 14-16, 2022).
