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
    <p class="hero__meta">San Diego, CA &middot; <a href="mailto:xit026@ucsd.edu">xit026@ucsd.edu</a> &middot; <a href="files/CV_Xinyu_Tian.pdf">CV (PDF)</a></p>
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

## Vision–Language Model Interpretability

**Causal Alignment of Human Gaze and Vision–Language Model Attention** · UC San Diego · 2026 · *group leader*
- Tested whether human fixation causally drives model attention in [LLaVA](https://llava-vl.github.io/) and [Qwen2-VL](https://github.com/QwenLM/Qwen2-VL), patching activations at gaze-peak tokens against ground-truth fixations from the [VQA-MHUG](https://aclanthology.org/2021.conll-1.3/) corpus
- Ablating gaze-peak tokens produced a significantly larger effect than matched random ablation (preliminary; *p* < 0.01, N = 120); the result is being re-run at higher power
- Implemented in [TransformerLens](https://github.com/TransformerLensOrg/TransformerLens), following the [ARENA 3.0](https://www.arena.education/) mechanistic-interpretability methodology

## Brain–Computer Interfaces for Real-Time Control

**Low-Fatigue Stimulus Design for SSVEP Spellers** · Tsinghua University, Gao Lab · 2025.02 – 2026.01 · *group leader*
- Replaced high-depth brightness flicker with low-depth and text-based stimuli, targeting the flicker sensation that limits how long a speller can be used rather than its peak accuracy
- Encoded three levels of Chinese linguistic structure — *zi* (character), *ci* (word) and *chengyu* (phrase) — to improve decoding robustness across units of different length
- Benchmarked FBCCA, TDCA and TRCA on accuracy and runtime across EEG from ten subjects; the low-depth study was conducted independently

**Real-Time Wheelchair Navigation via a Text-Based SSVEP Interface** · Tsinghua University, Gao Lab · 2025.06 – 2025.09 · *group member*
- Built a closed-loop interface issuing seven directional commands — forward, back, left, right, two rotations and stop — at 0.5 s decision intervals using calibrated TDCA
- Presented text-coded stimuli through an AR headset, trading peak decoding accuracy for stimuli a user can tolerate across a full session
- Validated and debugged the deployed system for the World Robot Contest

## Computer Vision and Signal Processing for Clinical Assessment

**Automatic Detection of SPES Artifacts in ECoG** · King's College London · 2026.01 – 2026.03 · *group leader*
- Built an [EEGLAB](https://eeglab.org/) plugin that flags single-pulse electrical stimulation artifacts for seizure-onset-zone identification, replacing exhaustive visual inspection with a human-in-the-loop review step
- Across the five clinical recordings available, tuned detection caught every artifact with under 5% false positives and cut review time by roughly 80% (approximate figures on a small sample)
- Deliberately rule-based rather than learned, so a clinician can predict and audit its behaviour

**Stereo Vision-Based ARAT Automation as Paralysis Rehabilitation Benchmark** · Tsinghua University, Hong Lab · 2025.08 – present · *group leader*  
*Part of EBR, a minimally invasive BCI rehabilitation system funded as a key project by the Tsinghua Innovative Research Commission*
- Designed the system architecture for scoring the Action Research Arm Test from stereo camera video, combining binocular stereo vision with CAD-based 6D pose estimation; implementation is ongoing
- Proposed tensor decomposition for dimensionality reduction in motor-imagery decoding
- Supported ECoG data collection from patients

# 💬 Talks and Seminars

- *2026.06.03*, \[Journal Club\] [**Active Use of Latent Tree-Structured Sentence Representation in Humans and Large Language Models**](https://www.nature.com/articles/s41562-025-02297-0), Gao Lab Meeting
- *2025.11.22*, \[Journal Club\] [**NetFormer: An Interpretable Model for Recovering Dynamical Connectivity in Neuronal Population Dynamics**](https://openreview.net/forum?id=bcTjW5kS4W), Hong Lab Meeting
- *2025.10.18*, \[Symposium\] **Dream Engineering: From Targeted Memory Reactivation to Visual Reconstruction**, Tsinghua Academy Elite Scholars Program
- *2025.08.23*, \[Journal Club\] **From Psychoacoustic Category Boundaries to Cortical Feature-Tuned Ensembles: Edward Chang's Research on Speech Perception**, Hong Lab Meeting
- *2025.03.21*, \[Symposium\] **Boolean Network Models: Toward Interpretable and Robust Biomodeling** (with Zezhao Wu), Tsinghua Academy Elite Scholars Program

<p class="site-credit">Built with the <a href="https://github.com/RayeRen/acad-homepage.github.io">AcadHomepage</a> template by Yi Ren (RayeRen), used under the MIT License.</p>
