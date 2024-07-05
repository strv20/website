---
title: "Influence of threshold selection and image sequence in in-vivo segmentation of enlarged perivascular spaces"
subtitle: "M Valdes Hernandez, R Duarte Coello, W Xu, J Bernal, Y Cheng, L Ballerini, SJ Wiseman, FM Chappell, U Clancy, D Jaime Garcia, C Arteaga Reyes, J Zhang, X Liu, W Hewins, MS Stringer, FN Doubal, MJ Thrippleton, ACC Jochems, R Brown and JM Wardlaw"
excerpt: "Enlarged perivascular spaces are a marker of small vessel disease and are of growing interest due to their potential role in brain waste clearance. We evaluate novel approaches to segment PVS using a vesslness filter and compare against an existing gold-standard method."
weight: 5
author: "Michael S. Stringer"
date: 2023-02-06
draft: false
categories:
  - Brain
  - Lacunes
  - MRI
  - Perivascular spaces
  - Small vessel disease
  - Virchow-Robin spaces
  - White matter hyperintensities.
# layout options: single or single-sidebar
layout: single-sidebar
links:
- icon: open-access
  icon_pack: ai
  name: source
  url: https://doi.org/10.1016/j.jneumeth.2023.110037
---



<style type="text/css">
.page-main img {
  box-shadow: 0px 0px 2px 2px rgba( 0, 0, 0, 0.2 );
  #/* ease | ease-in | ease-out | linear */
  transition: transform ease-in-out 1s;
}

.page-main img:hover {
  transform: scale(1.8);
}
</style>

<img src="featured.jpg" data-fig-alt="Common artefacts include: A: blurring; B: effect of motion artefact; C: ghosting effect around the sulci of the right parieto-occipital lobe and effect of truncation artefact; D: noise in the basal ganglia (mainly)." style="width:100.0%" />

<p class="caption" style="text-align:left;">
<b>Figure 1.</b> Axial slices of T2-weighted MRI scans illustrating common imaging artefacts.
</p>

## Abstract

### Introduction

Growing interest surrounds perivascular spaces (PVS) as a clinical biomarker of brain dysfunction given their association with cerebrovascular risk factors and disease. Neuroimaging techniques allowing quick and reliable quantification are being developed, but, in practice, they require optimisation as their limits of validity are usually unspecified.

### Methods

We evaluate modifications and alternatives to a state-of-the-art (SOTA) PVS segmentation method that uses a vesselness filter to enhance PVS discrimination, followed by thresholding of its response, applied to brain magnetic resonance images (MRI) from patients with sporadic small vessel disease acquired at 3 T. Limits of validity to a SOTA PVS segmentation method applied to 3 T MRI with confounding pathology are given.

### Results

The method is robust against inter-observer differences in threshold selection, but separate thresholds for each region of interest (i.e., basal ganglia, centrum semiovale, and midbrain) are required. Noise needs to be assessed prior to selecting these thresholds, as effect of noise and imaging artefacts can be mitigated with a careful optimisation of these thresholds. PVS segmentation from T1-weighted images alone, misses small PVS, therefore, underestimates PVS count, may overestimate individual PVS volume especially in the basal ganglia, and is susceptible to the inclusion of calcified vessels and mineral deposits. Visual analyses indicated the incomplete and fragmented detection of long and thin PVS as the primary cause of errors, with the Frangi filter coping better than the Jerman filter.

### Discussion

Evidence presented reinforces the STRIVE-2 recommendation of using T2-weighted images for PVS assessment wherever possible. The Frangi filter is recommended for PVS segmentation from MRI, offering robust output against variations in threshold selection and pathology presentation.