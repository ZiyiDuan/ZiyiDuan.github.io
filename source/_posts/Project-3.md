---
title: Putting visual working memory to work
date: 2025-11-12 22:00:00
layout: post
categories: Research
tags: Working Memory
---

Goal-directed behavior depends on the ability to flexibly change mental representations in working memory (WM). WM has not only storage but also control component. While largely neglected, these control components are essential for goal-directed behaviors as they transform visual representations into codes that can facilitate or ‘work’ to support behavior. Here, we asked whether and how do task demands change WM representations in the brain?

<!-- more -->

## Temporal dynamics
### 1. Spatial recostruction based on BOLD activities weighted by population Receptive Fields (pRFs)
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video spMaps_1_no_cued_all_V123_15subjs.mp4 100% "Baseline task: V1-V3" %}</div>
  <div>{% video spMaps_1_no_cued_all_IPS_15subjs.mp4 100% "Baseline task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video spMaps_1_rotate_cued_all_V123_15subjs.mp4 100% "Rotate task: V1-V3" %}</div>
  <div>{% video spMaps_1_rotate_cued_all_IPS_15subjs.mp4 100% "Rotate task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video spMaps_1_rotate+remap_cued_all_V123_15subjs.mp4 100% "Rotate+remap task: V1-V3" %}</div>
  <div>{% video spMaps_1_rotate+remap_cued_all_IPS_15subjs.mp4 100% "Rotate+remap task: IPS0-3" %}</div>
</div>


### 2. Principle Component Analysis (PCA) for BOLD activities
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video PCA_no_cued_V123_all_avg_15subjs.mp4 100% "Baseline task: V1-V3" %}</div>
  <div>{% video PCA_no_cued_IPS_all_avg_15subjs.mp4 100% "Baseline task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video PCA_rotate_cued_V123_all_avg_15subjs.mp4 100% "Rotate task: V1-V3" %}</div>
  <div>{% video PCA_rotate_cued_IPS_all_avg_15subjs.mp4 100% "Rotate task: IPS0-3" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px;">
  <div>{% video PCA_rotate+remap_cued_V123_all_avg_15subjs.mp4 100% "Rotate+remap task: V1-V3" %}</div>
  <div>{% video PCA_rotate+remap_cued_IPS_all_avg_15subjs.mp4 100% "Rotate+remap task: IPS0-3" %}</div>
</div>



### 3. Orientation reconstructions using Inverted Encoding Model (IEM)
<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px;">
  <div>{% video circ_no_cued_V123_contra_15subjs.mp4 100% "Baseline: V1-V3, contra" %}</div>
  <div>{% video circ_no_cued_V123_ipsi_15subjs.mp4 100% "Baseline: V1-V3, ipsi" %}</div>
  <div>{% video circ_no_cued_IPS_contra_15subjs.mp4 100% "Baseline: IPS0-3, contra" %}</div>
  <div>{% video circ_no_cued_IPS_ipsi_15subjs.mp4 100% "Baseline: IPS0-3, ipsi" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px;">
  <div>{% video circ_rotate_cued_V123_contra_15subjs.mp4 100% "Rotate: V1-V3, contra" %}</div>
  <div>{% video circ_rotate_cued_V123_ipsi_15subjs.mp4 100% "Rotate: V1-V3, ipsi" %}</div>
  <div>{% video circ_rotate_cued_IPS_contra_15subjs.mp4 100% "Rotate: IPS0-3, contra" %}</div>
  <div>{% video circ_rotate_cued_IPS_ipsi_15subjs.mp4 100% "Rotate: IPS0-3, ipsi" %}</div>
</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px;">
  <div>{% video circ_rotate+remap_cued_V123_contra_15subjs.mp4 100% "Rotate+remap: V1-V3, contra" %}</div>
  <div>{% video circ_rotate+remap_cued_V123_ipsi_15subjs.mp4 100% "Rotate+remap: V1-V3, ipsi" %}</div>
  <div>{% video circ_rotate+remap_cued_IPS_contra_15subjs.mp4 100% "Rotate+remap: IPS0-3, contra" %}</div>
  <div>{% video circ_rotate+remap_cued_IPS_ipsi_15subjs.mp4 100% "Rotate+remap: IPS0-3, ipsi" %}</div>
</div>