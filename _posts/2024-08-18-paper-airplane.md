---
layout: post
title: 紙飛行機
date: 2024-09-10 12:00:00
description: A Paper airplane simulation for high school education
tags: kamihikouki
categories: ST-SI IGA
thumbnail: "https://userdir.tafsm.org/~yliu/website/images/kamihikouki/kamihikouki-manufactured.png"
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/kamihikouki/computational-domain.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The computational domain consists of two key regions designed to enhance simulation accuracy and accommodate the movement of the paper airplane. The inner region is a cube that encloses the paper airplane, serving as a mesh refinement zone to ensure high-resolution computations in the vicinity of the object. Surrounding this cube is a spherical domain that also encloses the paper airplane. The sphere provides the spatial framework necessary for simulating its aerodynamic behavior, including pitch, yaw, and roll motions, by accounting for the unbounded nature of the surrounding fluid.

<div class="row mt-3">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/kamihikouki/kamihikouki-mesh.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/kamihikouki/kamihikouki-mesh-y0.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://userdir.tafsm.org/~yliu/website/images/kamihikouki/kamihikouki-mesh-zoom.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

The paper airplane in the computation is modeled with zero-thickness wings, body, and tail (_left_), while the boundary layer mesh (_right_) ensures accurate resolution of the flow near the surface.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/kamihikouki/kamihikouki-trans.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true loop=true %}
    </div>
</div>

The computation is done with the [Space--time Slip Interface Method](https://www.jp.tafsm.org/en/method/space-time-slip-interface-st-si-method).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/kamihikouki/glide-low-initial-speed-fsi.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true loop=true %}
    </div>
</div>

The paper airplane is launched at a relatively low initial speed, achieved by carefully controlling the length of the stretched rubber band. This mechanism ensures consistent and controlled launches for testing. During flight, the wings of the paper airplane exhibit flapping motion due to fluid--structure interaction, where aerodynamic forces from the airflow interact dynamically with the thin paper wings. It demonstrates a coupling between the paper airplane's structure and fluid flow. The video capturing this process was taken in a laboratory environment to minimize external disturbances, allowing for accurate observation.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://userdir.tafsm.org/~yliu/website/videos/kamihikouki/experiment-1.mp4" class="img-fluid rounded z-depth-1" class="img-fluid rounded z-depth-1" controls=true loop=true %}
    </div>
</div>

This video was recorded at Waseda University's [Toyama Campus](https://www.yamashitasekkei.co.jp/project/story/04.php), which is my favorite campus because of its distinctive architectural design. In this video, we observe the same aeroelastic behavior of the wing as seen in the first video, where the aerodynamic forces interact with the wing's structure, causing oscillations that affect its stability. As the paper plane glides through the air, it quickly loses speed due to aerodynamic drag, leading to a rapid loss of lift. Eventually, the paper airplane enters a [spin](https://learntoflyblog.com/aerodynamics-spins/) state, a phenomenon where one wing stalls before the other, causing the plane to rotate uncontrollably. This spin behavior is a critical aspect of understanding the limits of flight stability and control in low-speed regimes. I thought it is a good material for education.
