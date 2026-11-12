---
layout: page
title: Soft Sensors
description: Optical fiber tactile sensors, force myography sensors, and self-sensing actuators
img: assets/img/publication_preview/poftac_ral2026.png
importance: 1
related_publications: true
---

<link rel="stylesheet" href="{{ '/assets/style/custom.css' | relative_url }}">

I develop soft sensors that are thin and flexible enough to be worn on the body or mounted on a robot. Most of them use light guided in optical fibers as the sensing signal. Pressing or bending the fiber changes how much light reaches the detector, which makes the sensors immune to electromagnetic interference.

### Optical fiber fingertip tactile sensors

**PofTac** is a plastic optical fiber-based tactile sensor that measures contact location, force magnitude, and force distribution over the fingertip. It is built to work the same way on a human fingertip and on a robot fingertip {% cite chung2026poftac chung2026robotac %}.

<div class="cy-videos">
<figure><div class="cy-yt"><iframe src="https://www.youtube.com/embed/XlU9wEiy45c" title="PofTac: plastic optical fiber-based tactile sensor" allowfullscreen loading="lazy"></iframe></div><figcaption>PofTac: plastic optical fiber-based tactile sensor</figcaption></figure>
</div>

### Optical fiber force myography (FMG) sensors

Force myography reads hand motion and grip from the small pressure changes that forearm muscles produce on the skin. I designed thin and flexible FMG sensors made of weaved optical fiber, in which light loss through controlled fiber-polymer contact encodes the applied force. The work started from a proof-of-concept sensor {% cite chung2024ur %} and a sleeve-type system {% cite chung2024haptics %}, and was then optimized for higher sensitivity and robustness {% cite chung2025fmg chung2025whc chung2025whcdemo %}.

<div class="cy-videos">
<figure><div class="cy-yt"><iframe src="https://www.youtube.com/embed/6uTLwym47BM" title="Sleeve-type FMG system with weaved optical fiber sensors (Haptics Symposium 2024)" allowfullscreen loading="lazy"></iframe></div><figcaption>Sleeve-type FMG system (Haptics Symposium 2024)</figcaption></figure>
</div>

### Self-sensing soft actuators

An electrohydraulic actuator can also act as its own sensor. Using a capacitance sensing circuit, I made an EPIC actuator that detects touch and estimates force without an external sensor {% cite chung2022ur %}.

<div class="cy-videos">
<figure><div class="cy-yt"><video src="{{ '/assets/video/epic_selfsensing_voltage.mp4' | relative_url }}" controls muted playsinline preload="metadata"></video></div><figcaption>Self-sensing EPIC actuator: sensing voltage output under touch</figcaption></figure>
<figure><div class="cy-yt"><video src="{{ '/assets/video/epic_selfsensing_force.mp4' | relative_url }}" controls muted playsinline preload="metadata"></video></div><figcaption>Self-sensing EPIC actuator: calibrated force estimation</figcaption></figure>
</div>
