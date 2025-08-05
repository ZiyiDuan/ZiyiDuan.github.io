---
title: Project-3
date: 2025-08-04 22:24:20
layout: post
categories: Research
tags: Working Memory
---

Goal-directed behavior depends on the ability to flexibly change mental representations in working memory (WM). WM has not only storage but also control component. While largely neglected, these control components are essential for goal-directed behaviors as they transform visual representations into codes that can facilitate or ‘work’ to support behavior. Here, we asked whether and how do task demands change WM representations in the brain?

## Temporal dynamics
### 1. Spatial recostruction based on each voxel's BOLD activities weighted by its population Receptive Field (pRF)
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video /assets/videos/Project3/spMaps_baseline_V123_15subjs.mp4 100% "Baseline task: V1-V3" %}</div>
  <div>{% video /assets/videos/Project3/spMaps_baseline_IPS_15subjs.mp4 100% "Baseline task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video /assets/videos/Project3/spMaps_rotate_V123_15subjs.mp4 100% "Rotate task: V1-V3" %}</div>
  <div>{% video /assets/videos/Project3/spMaps_rotate_IPS_15subjs.mp4 100% "Rotate task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video /assets/videos/Project3/spMaps_rotate+remap_V123_15subjs.mp4 100% "Rotate+remap task: V1-V3" %}</div>
  <div>{% video /assets/videos/Project3/spMaps_rotate+remap_IPS_15subjs.mp4 100% "Rotate+remap task: IPS0-3" %}</div>
</div>


### 2. Principle Component Analysis (PCA) for BOLD activities separated by task-related locations
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% image fancybox group:gifs /assets/videos/Project3/PCA_baseline_V123_15subjs.gif "Baseline task: V1-V3" %}</div>
  <div>{% image fancybox group:gifs /assets/videos/Project3/PCA_baseline_IPS_15subjs.gif "Baseline task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% image fancybox group:gifs /assets/videos/Project3/PCA_rotate_V123_15subjs.gif 100% "Rotate task: V1-V3" %}</div>
  <div>{% image fancybox group:gifs /assets/videos/Project3/PCA_rotate_IPS_15subjs.gif 100% "Rotate task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% image fancybox group:gifs /assets/videos/Project3/PCA_rotate+remap_V123_15subjs.gif 100% "Rotate+remap task: V1-V3" %}</div>
  <div>{% image fancybox group:gifs /assets/videos/Project3/PCA_rotate+remap_IPS_15subjs.gif 100% "Rotate+remap task: IPS0-3" %}</div>
</div>


### 3. Orientation reconstructions based on Inverted Encoding Model (IEM)
<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px;">
  <div>{% video /assets/videos/Project3/circ_baseline_V123_contra_15subjs.mp4 100% "Baseline task: V1-V3, contra" %}</div>
  <div>{% video /assets/videos/Project3/circ_baseline_V123_ipsi_15subjs.mp4 100% "Baseline task: V1-V3, ipsi" %}</div>
  <div>{% video /assets/videos/Project3/circ_baseline_IPS_contra_15subjs.mp4 100% "Baseline task: IPS0-3, contra" %}</div>
  <div>{% video /assets/videos/Project3/circ_baseline_IPS_ipsi_15subjs.mp4 100% "Baseline task: IPS0-3, ipsi" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px;">
  <div>{% video /assets/videos/Project3/circ_rotate_V123_contra_15subjs.mp4 100% "rotate task: V1-V3, contra" %}</div>
  <div>{% video /assets/videos/Project3/circ_rotate_V123_ipsi_15subjs.mp4 100% "rotate task: V1-V3, ipsi" %}</div>
  <div>{% video /assets/videos/Project3/circ_rotate_IPS_contra_15subjs.mp4 100% "rotate task: IPS0-3, contra" %}</div>
  <div>{% video /assets/videos/Project3/circ_rotate_IPS_ipsi_15subjs.mp4 100% "rotate task: IPS0-3, ipsi" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px;">
  <div>{% video /assets/videos/Project3/circ_rotate+remap_V123_contra_15subjs.mp4 100% "rotate+remap task: V1-V3, contra" %}</div>
  <div>{% video /assets/videos/Project3/circ_rotate+remap_V123_ipsi_15subjs.mp4 100% "rotate+remap task: V1-V3, ipsi" %}</div>
  <div>{% video /assets/videos/Project3/circ_rotate+remap_IPS_contra_15subjs.mp4 100% "rotate+remap task: IPS0-3, contra" %}</div>
  <div>{% video /assets/videos/Project3/circ_rotate+remap_IPS_ipsi_15subjs.mp4 100% "rotate+remap task: IPS0-3, ipsi" %}</div>
</div>