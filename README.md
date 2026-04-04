# Neurocampus course 2026

This repository contains scripts and practical materials for the course "The Whole-Brain Signals" (2026). 

This is an introductory course. It is designed for students who are encountering EEG and MEG analysis for the first time. The goal is to build intuition, conceptual clarity, and hands-on familiarity with real electrophysiological data. The course does not assume advanced mathematical background, deep signal processing expertise, or prior experience with neuroimaging toolboxes. 

Lesson 1 (`1. Intro to time series.ipynb`) introduces core time-series concepts. It covers sampling and Nyquist/aliasing intuition, quantization effects, basic frequency-domain representation, and fundamental discrete-time building blocks.

Lesson 2 (`2. First look at MEG and EEG.ipynb`) provides a first practical tour of MNE-Python structures: basic data inspection, sensor layout and EEG reference choices, and montage setup.

Lesson 3 (`3. Artefact correction.ipynb`) introduces practical artefact correction in MNE-Python. It walks through segment annotation, compares PSD across conditions and scalp regions (e.g., eyes open vs eyes closed), demonstrates bad-channel interpolation, and applies SSP to identify and suppress the artefacts in real EEG data.

Lesson 4 (`4. Decomposition methods.ipynb`) introduces decomposition-based analysis for EEG/MEG. It builds intuition for projections and subspaces, demonstrates SVD and PCA as tools for dimensionality reduction and denoising, and introduces ICA for blind source separation and artefact-related component identification. 

Lesson 5 (`5. Evoked and induced activity.ipynb`) introduces event-related and time-frequency analysis in MNE-Python. It covers event extraction from annotations, epoching with baseline correction and rejection criteria, computation/visualization of evoked responses after basic ICA-based cleaning, and a first look at induced activity using time-frequency power maps.