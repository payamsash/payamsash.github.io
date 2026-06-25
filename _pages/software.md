---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

[MNE-RT](https://mne-rt-org.github.io/mne-rt/)

<p>
<img src="https://github.com/mne-rt-org/mne-rt/raw/main/docs/source/_static/mne_rt_logo.svg" alt="MNE-RT Logo" width="260" style="float: right; margin: 0 0 1em 2em;"/>
<a href="https://mne-rt-org.github.io/mne-rt/">MNE-RT</a> is a high-level neurofeedback and BCI application framework built on top of <a href="https://mne.tools">MNE-Python</a> and <a href="https://mne.tools/mne-lsl/stable/index.html">MNE-LSL</a>. It adds the full closed-loop pipeline that neither of the above provides: neural feature extraction modalities spanning sensor and source space; adaptive feedback protocols; online artifact correction methods; and live visualisation windows. It also handles feature combining, external feedback output via OSC and LSL outlets, BIDS-compatible session saving, and a full CLI.
</p>

<div style="clear:both;"></div>

[ANTARES](https://github.com/payamsash/antares)

ANTARES is a closed-loop EEG neurofeedback system designed for tinnitus research. It runs an adaptive multi-session protocol: automatically selecting the best EEG feature to train per subject, monitoring feature quality across sessions, and adjusting the training target when necessary. 
- The operator controls everything from a single GUI. 
- A separate full-screen display runs on the participant's monitor.
- The real-time visualisation engine renders the neurofeedback animation.

[TIDE](https://github.com/payamsash/TIDE)

 TIDE focuses on the identification and validation of a biomarker for tinnitus, providing a personalized, data-driven approach to chronic tinnitus diagnosis:
- Full and semi-automatic preprocessing and analysis of EEG data
- Unified file management for data collected from multiple sites and paradigms
- Tools specifically designed for tinnitus biomarker discovery
  

[Neurograph](https://github.com/payamsash/Neurograph)
  
  Neurograph enables graph learning from smooth signals derived from M/EEG or fMRI data, supporting advanced analyses of brain connectivity and network dynamics.
