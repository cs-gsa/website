+++
title = "Continuous Object Representation Networks: Novel View Synthesis without Target View Supervision"
date = 2021-04-02

[extra]
speaker = "Nicolai Haeni"
+++

{{ image(image="participants.png") }}

# Abstract
Novel View Synthesis (NVS) is concerned with synthesizing views under camera viewpoint transformations from one or multiple input images. NVS requires explicit reasoning about 3D object structure and unseen parts of the scene to synthesize convincing results. As a result, current approaches typically rely on supervised training with either ground truth 3D models or multiple target images. We propose Continuous Object Representation Networks (CORN), a conditional architecture that encodes an input image's geometry and appearance that map to a 3D consistent scene representation. We can train CORN with only two source images per object by combining our model with a neural renderer. A key feature of CORN is that it requires no ground truth 3D models or target view supervision. Regardless, CORN performs well on challenging tasks such as novel view synthesis and single-view 3D reconstruction and achieves performance comparable to state-of-the-art approaches that use direct supervision.

# Bio
I am a fifth-year Ph.D. student in the Robotic Sensor Networks Laboratory, advised by Prof. Volkan Isler. My current research interest lies in computer vision and robotics. Namely, I am interested in developing visual prospection in robots - the way of learning to visually simulate future states of our environment. This ability to "pre-experience" events in memory is simple for humans; most people would agree that chocolate desserts taste better with cinnamon than parmesan without having to try both options, but this mental simulation of events is currently impossible for AI. My goal is to enable robotic agents to reason about our world from visual observations and simulate possible future scenarios based on the agent's actions.
