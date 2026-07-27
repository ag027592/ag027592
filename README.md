<h1 align="center">Huang-Cheng Chou (周惶振)</h1>

<p align="center">
  <b>Speech &amp; Multimodal AI Researcher</b> · Postdoctoral Scholar (NSTC Fellow) at <a href="https://sail.usc.edu/">USC SAIL</a><br>
  Speech emotion recognition · Speech LLMs · Subjective &amp; fair evaluation · Voice assistant systems
</p>

<p align="center">
  <a href="https://huangchengchou.com"><img src="https://img.shields.io/badge/Website-huangchengchou.com-1f6feb?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://scholar.google.com/citations?user=_d7pcs4AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://www.linkedin.com/in/huangchougchou/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://huangchengchou.com/assets/Huang-Cheng_Chou_CV.pdf"><img src="https://img.shields.io/badge/CV-PDF-B31B1B?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="CV"></a>
</p>

---

## About

I build speech systems that model **how** something is said—not only **what** is said. My work focuses on:

- **Reliable speech evaluation** — reproducible benchmarks, calibration, fairness, and leakage-resistant protocols
- **Human-centered speech AI** — annotator disagreement, multi-label emotion, perceptual studies, and HITL tooling
- **Speech systems in the real world** — speech LLMs, voice assistants, low-resource speech, and clinical applications

I am a Postdoctoral Scholar and NSTC Fellow at **USC SAIL**, working with Prof. Shrikanth S. Narayanan. I earned my Ph.D. from **National Tsing Hua University**; my dissertation on subjective speech emotion recognition received an **ACLCLP Doctoral Dissertation Award (Honorable Mention)**.

Previously: Applied Scientist Intern at **Amazon Alexa Speech**, applied ML / DSP at **RealTek**, and speech / DSP engineering at **ITRI**.

> **Open to Speech AI, Applied Scientist, Research Scientist, and Research Engineer roles.**  
> Los Angeles, CA · [Email](mailto:ag027592@gmail.com) · [CV](https://huangchengchou.com/assets/Huang-Cheng_Chou_CV.pdf)

## Featured Work

**[EMO-SUPERB](https://github.com/ag027592/EMO-SUPERB)** — Reproducible speech emotion recognition benchmark
Standardized, leakage-resistant evaluation of **15 speech SSL models across 6 open datasets**, with recoverable splits, metrics, and an online leaderboard.  
[Code](https://github.com/ag027592/EMO-SUPERB) · [Leaderboard](https://emosuperb.github.io/) · [IEEE SLT 2024](https://ieeexplore.ieee.org/document/10832296) · 51+ GitHub stars

**[CGM Contingency Scoring](https://github.com/ag027592/cgm-contingency-scoring)** — HITL platform for clinical interview coding
Bilingual EN/ES annotation UI with a training gate, hidden attention checks, evidence spans, and Cohen/QWK agreement dashboards. The public release contains synthetic demo data only.  
[Code + demo instructions](https://github.com/ag027592/cgm-contingency-scoring) · Python · Streamlit · CI

**[rtMRI Speech Enhancement](https://github.com/ag027592/rtmri-speech-enhancement)** — Does cleaner audio preserve the signals science needs?
Interactive evaluation of DENOISER, PASE, REUSE, and RT-REUSE on scanner-noisy real-time MRI speech, including synchronized video and acoustic probes.  
[Live demo](https://huangchengchou.com/rtmri-speech-enhancement/) · *JASA* manuscript in preparation

**[Do You Hear What I Mean?](https://huangchengchou.com/Do-You-Hear-What-I-Mean/)** — Instruction–perception gap in expressive TTS
Human evaluation of five instruction-guided TTS systems and the **E-VOC** corpus of large-scale perceptual ratings.  
[Project page](https://huangchengchou.com/Do-You-Hear-What-I-Mean/) · [ICASSP 2026](https://doi.org/10.1109/ICASSP55912.2026.11462935) · [Dataset](https://huggingface.co/datasets/wizzzzzzzzz/E-VOC)

**[TaigiSpeech](https://github.com/ag027592/TaigiSpeech)** — Privacy-conscious data collection for low-resource speech
Offline recording app for collecting spontaneous Taiwanese Hokkien commands from older adults in realistic home scenarios; recordings stay local until consent.  
[Code](https://github.com/ag027592/TaigiSpeech) · [Project page](https://kwchang.org/taigispeech) · *INTERSPEECH 2026*

## Selected Research

- **Minority Views Matter** — all-inclusive evaluation under annotator disagreement, *IEEE Transactions on Affective Computing*, 2024
- **Embracing Ambiguity and Subjectivity** — multi-label SER evaluation across four corpora, [IEEE SLT 2024](https://doi.org/10.1109/SLT61566.2024.10832302)
- **Stimulus Modality Matters** — how audio / visual annotation conditions propagate into model performance, [ICASSP 2025](https://doi.org/10.1109/ICASSP49660.2025.10890558)
- **A Tiny Whisper-SER** — unified ASR + multi-label speech emotion recognition, APSIPA ASC 2024

Full publication list: [Google Scholar](https://scholar.google.com/citations?user=_d7pcs4AAAAJ&hl=en)

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![s3prl](https://img.shields.io/badge/s3prl-4B8BBE?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-FF6F00?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Slurm](https://img.shields.io/badge/Slurm-2C3E50?style=flat-square)

Speech SSL (WavLM, HuBERT, wav2vec 2.0, XLS-R, Whisper) · speech LLMs · multi-label / multi-task learning · model compression · perceptual evaluation · Streamlit HITL systems

---

<p align="center">
  <i>Building speech AI that is reproducible, human-centered, and useful outside the lab.</i>
</p>
