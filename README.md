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

I build speech systems that hear **how** something is said, not just **what** is said.

I am a Postdoctoral Scholar and NSTC Fellow at the Signal Analysis and Interpretation Laboratory (SAIL), University of Southern California, working with Prof. Shrikanth S. Narayanan. I earned my Ph.D. in Electrical Engineering from National Tsing Hua University under Prof. Chi-Chun Lee, where my dissertation on speech emotion recognition under subjectivity received the **ACLCLP Doctoral Dissertation Award (Honorable Mention)**.

I have shipped speech and ML systems from research through deployment as an Applied Scientist Intern at **Amazon Alexa Speech**, and in applied DSP roles at **RealTek** and **ITRI**.

**Open to speech AI / applied scientist / research engineer roles.**

## Research Themes

| Theme | What I work on |
|---|---|
| **Subjective &amp; ambiguous SER** | Multi-label learning, annotator disagreement, soft labels, calibration — systems that respect emotion ambiguity instead of collapsing it into one "ground truth" |
| **Open evaluation &amp; benchmarks** | Reproducible evaluation contracts: splits, metrics, prompts, parsing, diagnostics (EMO-SUPERB, VoxEmo, EMO-Reasoning) |
| **Fairness &amp; robustness** | Subgroup disparity, debiasing without fragile demographic shortcuts, confidence-oriented augmentation |
| **Assistant speech systems** | Unified ASR + multi-label SER, on-device SER/KWS under compute budgets, emotional-speech ASR analysis |
| **Speech LLMs &amp; low-resource speech** | Large audio language models, expressive TTS evaluation, codec emotion preservation, Taiwanese Hokkien speech resources |
| **Conversational social signals** | Deception in dialogue, group belongingness, dyadic clinical affect |

## Featured Work

**[EMO-SUPERB](https://github.com/EMOsuperb/EMO-SUPERB-submission)** — Reproducible speech emotion recognition benchmark
Only 19% of SER papers release reproducible results. EMO-SUPERB evaluates **15 speech self-supervised models across 6 open datasets** with standardized partitions that remove data leakage, plus an online leaderboard. We also use ChatGPT to recover the 2.58% of annotations written as free-form natural language that classification models normally discard, yielding a 3.08% average relative gain.
Leaderboard: [emosuperb.github.io](https://emosuperb.github.io/) · Paper: [IEEE SLT 2024](https://ieeexplore.ieee.org/abstract/document/10832296) · [arXiv](https://arxiv.org/pdf/2402.13018)

**[Embracing Multi-Label SER](https://github.com/ag027592/Embracing-Multi-Label)** — All-inclusive aggregation rule
Emotion perception is genuinely ambiguous, yet majority/plurality voting throws away minority annotator views. This work formalizes an all-inclusive aggregation rule for building and evaluating multi-label SER systems across IEMOCAP, MSP-IMPROV, MSP-PODCAST, and BIIC-PODCAST.
Paper: [IEEE SLT 2024](https://doi.org/10.1109/SLT61566.2024.10832302)

**[Stimulus Modality Matters](https://github.com/EMOsuperb/Stimulus-Modality-Matters)** — Does the annotator's modality change your model?
Labels collected from audio-only, video-only, and audio-visual stimuli are not interchangeable. We quantify how the perceptual modality used during annotation propagates into SER system performance.
Paper: [ICASSP 2025](https://doi.org/10.1109/ICASSP49660.2025.10890558) · [arXiv](https://arxiv.org/abs/2409.10762)

**[Do You Hear What I Mean?](https://huangchengchou.com/Do-You-Hear-What-I-Mean/)** — Quantifying the instruction-perception gap in expressive TTS
You can prompt a TTS system to "sound excited," but does a listener actually hear excitement? We quantify the gap between the instruction given to instruction-guided expressive TTS systems and what human listeners perceive.
Paper: *ICASSP 2026* · [Live project page](https://huangchengchou.com/Do-You-Hear-What-I-Mean/) · [Source](https://github.com/ag027592/Do-You-Hear-What-I-Mean)

**[EDL-LRL](https://github.com/ag027592/EDL-LRL)** — Facial emotion distribution learning by exploiting low-rank label correlations locally

## Selected Publications

First-author unless noted. Full list on [Google Scholar](https://scholar.google.com/citations?user=_d7pcs4AAAAJ&hl=en).

- **Minority Views Matter: Evaluating Speech Emotion Classifiers with Human Subjective Annotations by an All-Inclusive Aggregation Rule** — *IEEE Transactions on Affective Computing*, 2024
- **Open-Emotion: A Reproducible EMO-SUPERB for Speech Emotion Recognition Systems** — *IEEE SLT 2024*
- **Embracing Ambiguity and Subjectivity Using the All-Inclusive Aggregation Rule for Evaluating Multi-Label SER Systems** — *IEEE SLT 2024*
- **Stimulus Modality Matters: Impact of Perceptual Evaluations from Different Modalities on SER System Performance** — *ICASSP 2025*
- **A Tiny Whisper-SER: Unifying Automatic Speech Recognition and Multi-Label Speech Emotion Recognition Tasks** — *APSIPA ASC 2024*
- **The Importance of Calibration: Rethinking Confidence and Performance of Speech Multi-Label Emotion Classifiers** — *INTERSPEECH 2023*
- **Every Rating Matters: Joint Learning of Subjective Labels and Individual Annotators for Speech Emotion Classification** — *ICASSP 2019*
- **DeSTA2.5-Audio: Toward General-Purpose Large Audio Language Model with Self-Generated Cross-Modal Alignment** — *IEEE TASLP 2026* (co-author)
- **TaigiSpeech: A Low-Resource Real-World Speech Intent Dataset** — *INTERSPEECH 2026* long paper (co-author)
- **Do You Hear What I Mean? Quantifying the Instruction-Perception Gap in Instruction-Guided Expressive TTS** — *ICASSP 2026* (co-author)

## Experience

| Period | Role |
|---|---|
| 2025 – Present | Postdoctoral Scholar (NSTC Fellow), **USC SAIL** — Prof. Shrikanth Narayanan |
| 2024 – 2025 | Independent Researcher, collaborating with **NTU SPML Lab** — Prof. Hung-yi Lee |
| 2024 | Applied ML / DSP Intern, **RealTek** — Emerging Tech / Advanced DSP |
| 2023 | Applied Scientist Intern, **Amazon AGI** — Alexa Speech / ASR |
| 2016 – 2024 | Ph.D., Electrical Engineering, **NTHU BIIC Lab** — Prof. Chi-Chun Lee |

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

Speech SSL models (WavLM, HuBERT, wav2vec 2.0, XLS-R, Whisper), speech LLMs, multi-label and multi-task learning, model compression for edge deployment, large-scale perceptual annotation pipelines.

## Selected Awards

NSTC Postdoctoral Research Abroad Fellowship (2025–2026) · ACLCLP Doctoral Dissertation Award, Honorable Mention (2024) · APSIPA ASC Best Regular Paper Award (2019) · Merry Electronics Electroacoustics Thesis Award, Silver (2025) &amp; Bronze (2021) · NOVATEK Ph.D. Excellence Scholarship (2022–2023)

---

<p align="center">
  <i>Reach out if you are working on speech AI, voice assistants, or affective computing.</i>
</p>
