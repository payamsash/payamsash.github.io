---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

# Projects

<p style="color:#6a737d; font-size:0.95em; margin-top:-0.5em;">
Software and tools I've built or maintained for neuroscience research —
neurofeedback, real-time BCI, multi-modal recording, and connectivity analysis.
</p>

---

<div style="display:flex; align-items:flex-start; gap:2em; margin-bottom:0.5em; flex-wrap:wrap;">
  <img src="https://github.com/mne-rt-org/mne-rt/raw/main/docs/source/_static/mne_rt_logo.svg"
       alt="MNE-RT Logo" width="180"
       style="flex-shrink:0; margin-top:0.3em;"/>
  <div style="flex:1; min-width:260px;">

## [MNE-RT](https://mne-rt-org.github.io/mne-rt/)

<a href="https://mne-rt-org.github.io/mne-rt/">MNE-RT</a> is a high-level neurofeedback and BCI framework built on top of
<a href="https://mne.tools">MNE-Python</a> and
<a href="https://mne.tools/mne-lsl/stable/index.html">MNE-LSL</a>.
It provides the complete closed-loop pipeline, including sensor- and source-space
feature extraction, adaptive neurofeedback protocols, online artifact correction,
real-time visualisation, feature combination, OSC and LSL output, BIDS-compatible
session saving, and a comprehensive command-line interface.

<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">Python</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">neurofeedback</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">real-time BCI</span>

  </div>
</div>

---

<div style="display:flex; align-items:flex-start; gap:2em; margin-bottom:0.5em; flex-wrap:wrap;">
  <img src="/images/antares.png"
       alt="ANTARES Logo" width="180"
       style="flex-shrink:0; margin-top:0.3em;"/>
  <div style="flex:1; min-width:260px;">

## [ANTARES](https://github.com/payamsash/antares)

<a href="https://github.com/payamsash/antares">ANTARES</a> is a closed-loop EEG
neurofeedback system developed for tinnitus research. It runs an adaptive
multi-session protocol that automatically selects the most informative EEG feature
for each participant, monitors feature quality across sessions, and adjusts the
training target when necessary.

**Key features**

- Single-GUI operator interface
- Separate full-screen participant display
- Real-time neurofeedback visualisation engine

<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">EEG</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">tinnitus research</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">adaptive protocol</span>

  </div>
</div>

---

<div style="display:flex; align-items:flex-start; gap:2em; margin-bottom:0.5em; flex-wrap:wrap;">
  <img src="/images/mosaic-logo.svg"
       alt="MOSAIC Logo" width="180"
       style="flex-shrink:0; margin-top:0.3em;"/>
  <div style="flex:1; min-width:260px;">

## [MOSAIC](https://github.com/fcbg-platforms/mosaic)

<a href="https://github.com/fcbg-platforms/mosaic">MOSAIC</a> is a synchronized
multi-camera + audio recording suite for research labs, built around Basler GigE
cameras, with live pose/gaze preview, post-recording analysis, and Lab Streaming
Layer (LSL) integration for syncing with external systems (e.g. EEG).

<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">multi-camera</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">LSL</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">pose/gaze tracking</span>

  </div>
</div>

---

<div style="margin-bottom:0.5em;">

## [TIDE](https://github.com/payamsash/TIDE)

<a href="https://github.com/payamsash/TIDE">TIDE</a> focuses on identifying and
validating EEG biomarkers for tinnitus, providing a personalised, data-driven
approach to chronic tinnitus diagnosis.

**Key features**

- Fully and semi-automated EEG preprocessing and analysis
- Unified file management for multi-site and multi-paradigm datasets
- Tools specifically designed for tinnitus biomarker discovery

<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">EEG</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">biomarkers</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">multi-site</span>

</div>

---

<div style="margin-bottom:0.5em;">

## [Neurograph](https://github.com/payamsash/Neurograph)

<a href="https://github.com/payamsash/Neurograph">Neurograph</a> enables graph
learning from smooth signals derived from M/EEG and fMRI data, supporting
advanced analyses of brain connectivity and network dynamics.

<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">graph learning</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">connectivity</span>
<span style="display:inline-block; background:#eef2ff; color:#3730a3; font-size:0.78em; padding:2px 8px; border-radius:12px; margin-top:0.4em;">M/EEG · fMRI</span>

</div>

---

## Open Source Contributions

<p style="color:#6a737d; font-size:0.95em; margin-top:-0.5em;">
Bug fixes, features, and maintenance work contributed to open-source scientific
Python packages I use in my own research.
</p>

<table style="width:100%; border-collapse:collapse; margin-top:0.8em;">
  <tbody>
    <tr style="border-bottom:1px solid #e1e4e8;">
      <td style="padding:0.7em 0.8em 0.7em 0; width:32%; vertical-align:top;">
        <a href="https://mne.tools" style="font-weight:600;">MNE-Python</a>
      </td>
      <td style="padding:0.7em 0; vertical-align:top;">
        Contributed bug fixes and small enhancements to the core signal
        processing and analysis modules used across my EEG/MEG pipelines.
      </td>
    </tr>
    <tr style="border-bottom:1px solid #e1e4e8;">
      <td style="padding:0.7em 0.8em 0.7em 0; vertical-align:top;">
        <a href="https://mne.tools/mne-connectivity/stable/index.html" style="font-weight:600;">mne-connectivity</a>
      </td>
      <td style="padding:0.7em 0; vertical-align:top;">
        Contributed fixes and improvements to connectivity estimation
        functionality used in tinnitus and brain-network research.
      </td>
    </tr>
    <tr>
      <td style="padding:0.7em 0.8em 0.7em 0; vertical-align:top;">
        <a href="https://seaborn.pydata.org" style="font-weight:600;">seaborn</a>
      </td>
      <td style="padding:0.7em 0; vertical-align:top;">
        Contributed a bug fix and minor plotting improvements to the
        statistical visualisation library.
      </td>
    </tr>
  </tbody>
</table>