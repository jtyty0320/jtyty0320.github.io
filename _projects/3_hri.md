---
layout: page
title: HRI Systems
description: Human-to-robot skill transfer, wearable interfaces, and assistive robots
img: assets/img/publication_preview/origami_ral2024.png
importance: 3
related_publications: true
---

<link rel="stylesheet" href="{{ '/assets/style/custom.css' | relative_url }}">

I build systems in which people and robots physically interact: robots that learn touch from people, wearables that read human intention, and robots that assist the human body.

### Human-to-robot manipulation skill transfer

Transferring human manipulation skills to robot hands needs more than hand kinematics. The robot also needs to know where contact happens, how strong it is, and how the force is distributed over the fingertip. With PofTac, the same tactile sensor is worn on a human fingertip during demonstration and mounted on a robot fingertip during execution, so the tactile data from both sides are directly comparable {% cite chung2026poftac chung2026robotac %}. This is the topic of my Ph.D. thesis, and ongoing work extends the idea to robot hands with sensing fingernails.

<div class="cy-videos">
<figure><div class="cy-yt"><iframe src="https://www.youtube.com/embed/XlU9wEiy45c" title="PofTac: shared human-robot tactile sensing" allowfullscreen loading="lazy"></iframe></div><figcaption>PofTac: shared human-robot tactile sensing</figcaption></figure>
</div>

### Wearable interfaces for reading human intention

A wearable FMG sleeve with optical fiber sensors recognizes hand gestures and estimates joint angles and grasping force in real time, providing a robust input channel for human-robot interaction {% cite chung2025fmg chung2025whc chung2025whcdemo %}.

<div class="cy-videos">
<figure><div class="cy-yt"><iframe src="https://www.youtube.com/embed/YMKC96zAIB0" title="FMG: elbow flexion angle estimation" allowfullscreen loading="lazy"></iframe></div><figcaption>FMG: elbow flexion angle estimation</figcaption></figure>
<figure><div class="cy-yt"><iframe src="https://www.youtube.com/embed/CdubvCknPfM" title="FMG: wrist motion recognition using multiple sensors" allowfullscreen loading="lazy"></iframe></div><figcaption>FMG: wrist motion recognition using multiple sensors</figcaption></figure>
</div>

### Wearable assistive and rehabilitation robots

Wearable robots have to follow natural joint motion while staying light enough to wear. For shoulder abduction, we first proposed a four-bar linkage-based support mechanism {% cite hyeon2022shoulder %}. I then designed an origami-inspired double-petal mechanism that follows the scapulohumeral rhythm and verified its assistance with surface electromyography {% cite chung2023ur chung2024origami %}. A soft wearable robot for elbow flexion and forearm supination/pronation was evaluated with patients with stroke and spinal cord injuries {% cite jeong2022elbow %}.

### Prosthetics

A lightweight prosthetic wrist mimics the wrist bones and muscles to reach a functional range of motion {% cite hyeon2023wrist %}, and sEMG signals from the user can be used to control it {% cite chung2023roman %}.

<div class="cy-videos">
<figure><div class="cy-yt"><video src="{{ '/assets/video/wrist_ral2023.mp4' | relative_url }}" controls muted playsinline preload="metadata"></video></div><figcaption>SMA prosthetic wrist: active range of motion</figcaption></figure>
</div>

### Wearable thermal feedback

A skin-mountable, stretchable heater array can deliver localized thermal patterns to the skin, which opens a thermal channel for wearable haptic interaction {% cite kim2024pvcgel %}.

<div class="cy-videos">
<figure><div class="cy-yt"><iframe src="https://www.youtube.com/embed/lhzQe8pozws" title="Stretchable, transparent and multifunctional PVC-gel heater" allowfullscreen loading="lazy"></iframe></div><figcaption>Stretchable, transparent and multifunctional PVC-gel heater</figcaption></figure>
</div>
