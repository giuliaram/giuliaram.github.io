---
layout: page
title: Project eWalk
description: Hip exoskeleton to assist walking
permalink: /ewalk/
img: assets/img/ewalk_draw.jpg
importance: 1
category: ongoing
related_publications: true
nav: true
---

## Main Description

**eWalk** is an active hip exoskeleton designed to support walking in healthy individuals. The device assists the flexion–extension motion of the hips using two actuated joints, while two other passive degrees of freedom for accomodating steps width variability. This exoskeleton is designed to help to reduce fatigue and improve endurance and walking efficiency. The concept is simple: offer wearable assistance like an e-bike, but for walking.

Beyond healthy users, the device holds promise for increasing mobility and physical activity in older adults, potentially helping in maintaining an active lifestyle.

<div class="row mt-4">
  <div class="col-sm">
    {% include figure.liquid path="assets/img/ewalk_pref.jpg" title="Treadmill" class="img-fluid rounded z-depth-1" style="height: 220px;" %}
  </div>
  <div class="col-sm">
    {% include figure.liquid path="assets/img/ewalk_stairs.jpg" title="Unstructured 1" class="img-fluid rounded z-depth-1" style="height: 220px;" %}
  </div>
  <div class="col-sm">
    {% include figure.liquid path="assets/img/ewalk_nobkg.jpg" title="Unstructured 2" class="img-fluid rounded z-depth-1" style="height: 220px;" %}
  </div>
</div>

<div class="caption">
  Exoskeleton testing in diversified walking conditions.
</div>

---

## Technical Characteristics

- **Actuation**: Two motors (one per leg) for hip flexion-extension assistance
- **Control**: Custom embedded controller running on a BeagleBoneBlack, and implementing adaptive torque strategies
- **Sensing**: Joint encoders, and inertial sensors
- **Battery**: Wearable battery pack (LiPo - 24 V)
- **Frame**: Lightweight 3D printed and carbon fiber structure
- **Fit**: Adjustable for users of various heights and body types

---

## Open Projects

We are currently exploring and open to collaboration in the following areas:

- **Machine learning for adaptive control**: personalized assistance across terrains and users
- **Sensor fusion and intention detection**: robust sensor fusion for real-time control
- **Human-subject studies**: evaluating impact on fatigue, metabolic cost, and long-term usability
- **Hardware iteration**: lighter, adjustable, and more ergonomic design

If you're interested in working with us on eWalk, please reach out.

---
