---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

<img src="https://raw.githubusercontent.com/payamsash/ANT/main/docs/source/_static/ANT_Logo_Horizontal.svg"
     alt="ANT Logo" width="260" style="float:right; margin: 0 0 1em 2em;"/>

[ANT](https://payamsash.github.io/ANT/)

ANT is an open-source Python package for real-time closed-loop M/EEG neurofeedback, built on [MNE-Python](https://mne.tools) and the [Lab Streaming Layer (LSL)](https://labstreaminglayer.org). It covers the full pipeline — from amplifier to 3D brain display — in a single, researcher-friendly API:

- 20+ neural features in sensor and source space: band power, ERD/ERS, laterality, Hjorth parameters, spectral centroid, slow cortical potentials, CFC, functional connectivity, graph Laplacian
- Adaptive reward protocols: z-score, threshold, percentile, staircase, operant, reinforcement learning, sham, and transfer — evaluated inside the acquisition loop on every analysis window
- Real-time artifact correction: ASR, adaptive LMS, GEDAI (GED-based spatial filters), ORICA (online ICA), Riemannian covariance detection
- Real-time Maxwell filtering: pre-computed SSS/tSSS projector for zero-latency MEG denoising, numerically equivalent to offline MNE
- Three live displays: raw stream viewer, NF signal monitor, and 3D cortical activation map
- External output via OSC (Max/MSP, SuperCollider, Pure Data) and LSL outlet (PsychoPy, OpenViBE) for reward delivery
- Command-line interface: `ANT info` · `ANT demo` · `ANT baseline` · `ANT run` — no Python required

<div style="clear:both;"></div>

[TIDE](https://github.com/payamsash/TIDE)

 TIDE focuses on the identification and validation of a biomarker for tinnitus, providing a personalized, data-driven approach to chronic tinnitus diagnosis:
- Full and semi-automatic preprocessing and analysis of EEG data
- Unified file management for data collected from multiple sites and paradigms
- Tools specifically designed for tinnitus biomarker discovery
  

[Neurograph](https://github.com/payamsash/Neurograph)
  
  Neurograph enables graph learning from smooth signals derived from M/EEG or fMRI data, supporting advanced analyses of brain connectivity and network dynamics.
