---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am a senior-year undergraduate student from Tsinghua University, Zhili College. Currently I'm a visiting student at UCSD. Prior to this, I was a research intern of brain–computer interfaces (BCIs) supervised by Xiaorong Gao and Bo Hong. I also spent a happy winter as a research intern at King's College Hospital supervised by Antonio Valentín in 2026.

My research interest has shifted from brain–computer interfaces (BCIs) to embodied intelligence and robotics. I believe my experience in decoding the intelligence of *homo sapiens* (computational neuroscience and biomedical engineering) would prove useful in encoding the intelligence of embodied agents! Currently I'm curious about the potential of using human data as a training signal or design inspiration in robot learning. Is the ideal robotic system supposed to be humanoid (either in embodiment or in intelligence), or has its own trajectory of development and evolution?

# 🔬 Research Projects

## Vision-Language Interpretability & Embodied Perception

**Causal Gaze-Attention Alignment in Vision-Language Models** · UC San Diego, 2026
- Applied activation patching to LLaVA and Qwen2-VL to test whether human gaze fixation causally predicts model attention allocation and failure modes
- Drew ground-truth fixations from the VQA-MHUG eye-tracking corpus
- Gaze-peak-targeted ablation shows a preliminary effect (*p* < 0.01, N = 120); result currently under further powering
- Implemented in TransformerLens, with methodology grounded in the ARENA 3.0 mechanistic-interpretability curriculum

**Spatially-Grounded Gaze & Scene Pipeline — Meta Aria Glasses** · UC San Diego, 2026
- Fused egocentric RGB, depth, and calibrated gaze-ray streams into a spatially-registered perception pipeline
- SAM 2 segmentation with VLM object recognition for semantically-grounded, object-level gaze tokenization
- I-DT fixation detection and scanpath-graph construction from raw gaze traces, at both fine and coarse granularity
- Toward an attention foundation model and, from it, agents that allocate perceptual resources to task-relevant information

## Real-Time Neural Control Systems

**EBR (Enhancing, Boosting and Repairing): A Paralysis Rehabilitation System Based on Minimally Invasive BCI** · Tsinghua, Hong Lab, 2025.08 – present  
*Key project funded by the Tsinghua Innovative Research Commission — an upgrade of NEO, China's first wireless invasive BCI clinical trial*
- **Leader of group R**: architected a CV-based dual-camera pipeline automating the Action Research Arm Test (ARAT), using binocular stereo vision and CAD-based 6D pose estimation
- **Key member of group B**: proposed a tensor-decomposition method for dimensionality reduction in motor-imagery decoding, and assisted ECoG signal collection from patients

**AR Wheelchair Navigation Using Text-Based SSVEP-BCI** · Tsinghua, Gao Lab, 2025.06 – 2025.09
- Decoded 7 directional intentions (forward, backward, left, right, clockwise and counter-clockwise rotation, stop) at 0.5 s intervals via calibrated TDCA
- Traded decoding accuracy against user comfort by presenting text-coded stimuli through an immersive AR headset
- Handled system debugging and report writing for the World Robot Contest

## Signal Decoding Foundations

**An SSVEP-BCI System Using Low-Depth Flickering Stimuli** · Tsinghua, Gao Lab, 2025.10 – 2026.01 · *independent research*
- Replaced conventional high-depth brightness flicker with medium- and low-depth flicker to reduce flickering sensation without compromising decoding performance
- Processed EEG from 10 subjects to extract temporal, spatial and spectral response characteristics across stimulus frequency and luminance
- Compared FBCCA, TDCA and TRCA on both accuracy and runtime to validate the system

**A Text-Based SSVEP-BCI Speller: 3-Level Hierarchical Encoding on Chinese Linguistic Units** · Tsinghua, Gao Lab, 2025.02 – 2025.07
- Encoded at three levels of Chinese linguistic structure — *zi* (character), *ci* (word) and *chengyu* (phrase) — to improve decoding robustness
- Substituted text-based flickering stimuli for brightness flicker to improve user comfort
- Collected and processed EEG from 10 subjects in frequency-sweeping experiments
- Validated the hierarchical encoding by showing involvement of both ventral and dorsal visual pathways, with distinct response patterns per level

**Automatic Detection of SPES Artifacts in ECoG for SOZ Identification** · King's College London, 2026.01 – 2026.03
- Built a clinical-assistant plugin for EEGLAB in MATLAB, designed as human-in-the-loop tooling that speeds clinicians up rather than replacing their judgement
- Worked with standardized but noisy clinical data, in direct communication with the people collecting it

# 📖 Educations

- *2023.09 – 2027.06 (expected)*, B.S., Zhili College, Tsinghua University, Beijing — Advisors: Prof. Xiaorong Gao and Prof. Bo Hong
- Visiting Student, University of California San Diego

# 💬 Talks and Seminars

- *2025.11.24*, Reported on my ARAT automation project at Bo Hong Lab's weekly meeting — deep model fusion for arm-landmarking accuracy, the remote tracking architecture, and the ARAT automation system design.
- *2025.11.22*, Presented *NetFormer: An Interpretable Model for Recovering Dynamical Connectivity in Neuronal Population Dynamics* at Bo Hong Lab's weekly meeting.
- *2025.10.18*, Organized a symposium on dream decoding and BCI, discussing visual reconstruction from dream brain activity and what recent work on inner-speech decoding and privacy protection suggests for it.
- *2025.08.23*, Introduced Edward F. Chang's work on speech perception at Bo Hong Lab's weekly meeting — the shift from phonemes to acoustic-phonetic features as basic units, single-neuron selectivity, and why first-hand ECoG and single-neuron data matter in speech decoding.

# 💻 Internships

- *2026.01.11 – 2026.03.11*, Research Intern, Antonio Valentín's Lab (neuromodulation in epilepsy), King's College Hospital, London, UK
