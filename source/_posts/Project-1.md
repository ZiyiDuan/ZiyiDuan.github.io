---
title: Visual working memories are abstractions of percepts
date: 2025-08-04 20:00:00
tags: Working Memory
layout: post
categories: Research
---

Decoding working memory (WM) contents from visual cortex has been widely found in human neuroimaging studies, demonstrating the idea that visual WM storage uses similar encoding mechanism as visual perception in the visual cortex. However, researchers have found evidence both support and against this hypothesis. Most of these studies, no matter for or against the hypothesis, relied on decoding the orientation of gratings with fMRI voxel responses. 

<!-- more -->
Orientation tuning is one of the fundemantal mechanisms for sensory neurons in visual cortex. However, the neural mechanism underlying orientation decoding is complicated. Rather than just a reflection of fine-scale sampling of orientation tuned neurons, orientation decoding also relies on complex interactions between the stimulus’s orientation, its bounding aperture, and topographic inhomogeneities across the visual field map. In spite of its importance, it is unknown how WM decoding might be affected by these coarse-scale biases.

Here, we directly address this gap by testing how aperture biases affect WM decoding, as well as testing how sensory-like are WM codes. We used two types of stimuli with the same orientation but orthogonal aperture biases (radial vs. angular modulator) to test how these aperture biases described during perception may affect WM decoding.

<br>
{% image fancybox clear group:paper Fig1.png "Population receptive field mapping, trial design, and stimuli generation schema" %}
<br>

Decoding results showed aperture bias during the perceptual task, where orientations can be decoded only within the same kind of modulated gratings but can't be generalized to different types in early visual cortex (V1-V3). However, both within and cross-modulator decoding is successful during the WM task. Moreover, we found that classifiers trained during perception can be used to decode orientation information in WM, but only when the aperture bias is aligned with the orientation of the grating (i.e., radial modulator).

<br>
{% image fancybox clear group:paper Fig2.png "Decoding orientation during WM and perception" %}
<br>

Next, to reveal the representational formats of WM, we constructed the spatial profile of neural activity within visual field maps. Regardless of aperture biases, WM representations of both modulated gratings were recoded into a single-oriented line that matches the remembered orientation but not the aperture bias.

<br>
{% image fancybox clear group:paper Fig3.png "Visualizing WM and perception of radial and angular modulated oriented gratings" %}
<br>

Finally, we simulated model outputs of both types of modulated gratings as well as line-like images at angles matching the orientation. The spatial maps based on model responses matched those in the perception task, while the results for line-like images matched the WM task.

<br>
{% image fancybox clear group:paper Fig4.png "Modeling and reconstructing spatial maps of perceptual and mnemonic representations in V1" %}
<br>

In summary, we found the WM decoding of orientation is immune to the aperture biases that drive decoding during perceptual studies of orientation. Moreover, WM representations are reformatted into efficient abstractions of percepts such that they most closely support memory guided behavior.

[Paper link](https://doi.org/10.7554/eLife.94191.3)
