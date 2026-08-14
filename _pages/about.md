---
permalink: /
title: ""
excerpt: ""
description: "Xinyu (Catherine) Tian — senior undergraduate at Tsinghua University, Zhili College, and visiting student at UC San Diego. Human data for embodied intelligence and robot learning."
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

<div class="hero">
  <div class="hero__side">
    <p class="hero__eyebrow">Human Data for Robot Learning</p>
    <h1 class="hero__name">Xinyu (Catherine) Tian</h1>
    <img class="hero__portrait" src="images/profile.jpg" alt="Xinyu (Catherine) Tian">
    <p class="hero__meta">San Diego, CA &middot; <a href="mailto:xit026@ucsd.edu">xit026@ucsd.edu</a></p>
  </div>
  <div class="hero__bio">
    <p>I am a senior undergraduate from <a href="https://www.tsinghua.edu.cn/en/">Tsinghua University</a>, <a href="https://www.zlc.tsinghua.edu.cn/EN/en.htm">Zhili College</a>. Currently I'm a visiting student at <a href="https://ucsd.edu/">UCSD</a>. Prior to this, I worked as a research intern under Xiaorong Gao and Bo Hong on non-invasive and invasive <strong>brain-computer interfaces</strong>.</p>
    <p>I also spent a happy spring as a research intern at <a href="https://www.kch.nhs.uk/">King's College Hospital</a> supervised by Antonio Valent&iacute;n in 2026. My research interest has since shifted from <strong>decoding biological intelligence</strong> to <strong>encoding artificial embodied intelligence</strong>.</p>
    <p>Currently I'm curious about the potential of using <strong>human data</strong> as a training signal in robot learning.</p>
    <p class="hero__q">Is the ideal robotic system supposed to be humanoid (either in embodiment or in intelligence), or has its own trajectory of development and evolution?</p>
  </div>
</div>

# 📖 Educations

- *2023.09 – 2027.06 (expected)*, B.S., [Zhili College](https://www.zlc.tsinghua.edu.cn/EN/en.htm), [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing — Advisors: Prof. Xiaorong Gao and Prof. Bo Hong
- Visiting Student, [University of California San Diego](https://ucsd.edu/)

# 💻 Internships

- *2026.01.11 – 2026.03.11*, Research Intern, Antonio Valentín's Lab (neuromodulation in epilepsy), [King's College Hospital](https://www.kch.nhs.uk/), London, UK

# 🔬 Research Projects

## Vision-Language Interpretability & Embodied Perception

**Causal Gaze-Attention Alignment in Vision-Language Models** · UC San Diego, 2026
- Applied activation patching to [LLaVA](https://llava-vl.github.io/) and [Qwen2-VL](https://github.com/QwenLM/Qwen2-VL) to test whether human gaze fixation causally predicts model attention allocation and failure modes
- Drew ground-truth fixations from the [VQA-MHUG](https://aclanthology.org/2021.conll-1.3/) eye-tracking corpus
- Gaze-peak-targeted ablation shows a preliminary effect (*p* < 0.01, N = 120); result currently under further powering
- Implemented in [TransformerLens](https://github.com/TransformerLensOrg/TransformerLens), with methodology grounded in the [ARENA 3.0](https://www.arena.education/) mechanistic-interpretability curriculum

**Spatially-Grounded Gaze & Scene Pipeline — [Meta Aria Glasses](https://www.projectaria.com/)** · UC San Diego, 2026
- Fused egocentric RGB, depth, and calibrated gaze-ray streams into a spatially-registered perception pipeline
- [SAM 2](https://ai.meta.com/sam2/) segmentation with VLM object recognition for semantically-grounded, object-level gaze tokenization
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
- Built a clinical-assistant plugin for [EEGLAB](https://eeglab.org/) in MATLAB, designed as human-in-the-loop tooling that speeds clinicians up rather than replacing their judgement
- Worked with standardized but noisy clinical data, in direct communication with the people collecting it

# 💬 Talks and Seminars

- *2026.06.03*, \[Journal Club\] [**Active Use of Latent Tree-Structured Sentence Representation in Humans and Large Language Models**](https://www.nature.com/articles/s41562-025-02297-0), Gao Lab Meeting
- *2025.11.22*, \[Journal Club\] [**NetFormer: An Interpretable Model for Recovering Dynamical Connectivity in Neuronal Population Dynamics**](https://openreview.net/forum?id=bcTjW5kS4W), Hong Lab Meeting
- *2025.10.18*, \[Symposium\] **Dream Engineering: From Targeted Memory Reactivation to Visual Reconstruction**, Tsinghua Academy Elite Scholars Program
- *2025.08.23*, \[Journal Club\] **From Psychoacoustic Category Boundaries to Cortical Feature-Tuned Ensembles: Edward Chang's Research on Speech Perception**, Hong Lab Meeting
- *2025.03.21*, \[Symposium\] **Boolean Network Models: Toward Interpretable and Robust Biomodeling** (with Zezhao Wu), Tsinghua Academy Elite Scholars Program
