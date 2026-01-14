<div align="center">

# Awesome Affective Computing: Emotion Recognition, Reasoning & Intelligence

[![Awesome](
https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](
https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Yorkson-huang/awesome-affective-computing/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Yorkson-huang/awesome-affective-computing/graphs/commit-activity)
[![GitHub Stars](https://img.shields.io/github/stars/Yorkson-huang/awesome-affective-computing?style=social)](https://github.com/Yorkson-huang/awesome-affective-computing)
[![License](https://img.shields.io/github/license/Yorkson-huang/awesome-affective-computing)](https://github.com/Yorkson-huang/awesome-affective-computing/blob/main/LICENSE)

**"Teaching Machines to Sense, Think, and Feel."**

Curated roadmap for Affective Computing: from signal-level perception to LLM-era emotional intelligence.
</div>

---
> "If we want computers to be genuinely intelligent and to interact naturally with us, we must give them the ability to recognize, understand, even to have and express emotions."
> <div align="right">—— <b>Rosalind Picard</b>, <i>Affective Computing (1997)</i></div>

## 🌟 Introduction

**Affective Computing (AC)** is an interdisciplinary field spanning computer science, psychology, and cognitive science. As AI evolves from discriminative tasks to generative intelligence, the field is undergoing a significant paradigm shift: moving from **Signal-based Perception** (recognizing patterns in face, voice, and physiology) to **LLM-driven Emotional Reasoning** (understanding context, empathy, and causal logic).

This repository is a curated collection of research papers, datasets, and toolkits designed to track this evolution. It serves as a comprehensive roadmap for researchers exploring how Large Language Models (LLMs) and Multimodal models are redefining the boundaries of **Artificial Emotional Intelligence (AEI)**.

---

## 📑 Table of Contents
- [📚 Surveys & Reviews](#surveys-reviews)
- [📊 Datasets and Benchmarks](#datasets-benchmarks)
  - [📁 Datasets](#datasets)
  - [⚖️ Benchmarks](#benchmarks)
- [🤖 Emotional Intelligence in Large Models (LLM/MLLM/ALLM)](#emotional-intelligence)
  - [MLLM / Omni-modal Models](#emotional-intelligence-mllm)
  - [Audio / Speech LLMs (ALLM)](#emotional-intelligence-audio)
  - [Text-centric LLMs](#emotional-intelligence-text)
- [🔍 Emotion Understanding & Reasoning](#emotion-understanding)
- [🧠 Multimodal Emotion Recognition (MER) & Perception](#mer-perception)
  - [MER & MSA (Signal-based Fusion)](#mer-msa)
  - [Facial & Physiological Affective Perception](#facial-physiological)
- [🗣️ Affective Generation & Synthesis](#affective-generation)
- [🛠️ Toolkits & Challenges](#toolkits-challenges)
  - [MuSe Challenge Series](#muse-challenge)
  - [MER Challenge Series](#mer-challenge)

---

<a id="surveys-reviews"></a>
## 📚 Surveys & Reviews

- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **Computational emotion analysis with multimodal LLMs: Current evidence on an emerging methodological opportunity** | [[Paper](https://arxiv.org/pdf/2512.10882v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Intelligent Agents with Emotional Intelligence: Current Trends, Challenges, and Future Prospects** | [[Paper](https://arxiv.org/pdf/2511.20657)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Rethinking Facial Expression Recognition in the Era of Multimodal Large Language Models** | [[Paper](https://arxiv.org/pdf/2511.00389v1)] [[Code](https://github.com/zfkarl/UniFER)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Datasets for Valence and Arousal Inference: A Survey** | [[Paper](https://arxiv.org/pdf/2510.00738v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.09](https://img.shields.io/badge/2025.09-lightgrey?style=flat) **Multimodal Large Language Models Meet Multimodal Emotion Recognition and Reasoning: A Survey** | [[Paper](https://arxiv.org/pdf/2509.24322)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **SarcasmBench: Towards Evaluating Large Language Models on Sarcasm Understanding** | [[Paper](https://arxiv.org/pdf/2408.11319)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **A Review of Human Emotion Synthesis Based on Generative Technology** | [[Paper](https://arxiv.org/pdf/2412.07116)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **A Comprehensive Survey on Datasets for Affective Computing and Mental Disorder** | [[Paper](https://ieeexplore.ieee.org/document/11214492)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **A Systematic Review of Experimental Protocols: Towards a Uniform Framework in Virtual Reality Affective Research** | [[Paper](https://ieeexplore.ieee.org/document/10945786)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Affective Computing Databases: In-Depth Analysis of Systematic Reviews and Surveys** | [[Paper](https://ieeexplore.ieee.org/document/10769002)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Explainable AI for Audio and Visual Affective Computing: A Scoping Review** | [[Paper](https://ieeexplore.ieee.org/document/10766406)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.05](https://img.shields.io/badge/2025.05-lightgrey?style=flat) **Multimodal Emotion Recognition in Conversations: A Survey of Methods, Trends, Challenges and Prospects** | [[Paper](https://arxiv.org/pdf/2505.20511)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.04](https://img.shields.io/badge/2025.04-lightgrey?style=flat) **A Survey on Multimodal Music Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2504.18799v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.09](https://img.shields.io/badge/2024.09-lightgrey?style=flat) **Recent Trends of Multimodal Affective Computing: A Survey from an NLP Perspective** | [[Paper](https://arxiv.org/pdf/2409.07388)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.08](https://img.shields.io/badge/2024.08-lightgrey?style=flat) **Affective computing in the era of large language models: A survey from the nlp perspective** | [[Paper](https://arxiv.org/pdf/2408.04638)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.06](https://img.shields.io/badge/2024.06-lightgrey?style=flat) **Large Language Models Meet Text-Centric Multimodal Sentiment Analysis: A Survey** | [[Paper](https://arxiv.org/pdf/2406.08068)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2023.12](https://img.shields.io/badge/2023.12-lightgrey?style=flat) **A Comprehensive Survey on Multi-modal Conversational Emotion Recognition with Deep Learning** | [[Paper](https://arxiv.org/pdf/2312.05735v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2023.05](https://img.shields.io/badge/2023.05-lightgrey?style=flat) **A Comprehensive Survey on Affective Computing; Challenges, Trends, and Future Directions** | [[Paper](https://arxiv.org/pdf/2305.07665)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2023.05](https://img.shields.io/badge/2023.05-lightgrey?style=flat) **Multimodal Sentiment Analysis: A Survey** | [[Paper](https://arxiv.org/pdf/2305.07611)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2022.03](https://img.shields.io/badge/2022.03-lightgrey?style=flat) **A Systematic Review on Affective Computing: Emotion Models and Databases** | [[Paper](https://arxiv.org/pdf/2203.06935)]
- ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2022](https://img.shields.io/badge/2022-lightgrey?style=flat) **Video-Based Facial Micro-Expression Analysis: A Survey of Datasets and Algorithms** | [[Paper](https://ieeexplore.ieee.org/document/9382112)]
- ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2022](https://img.shields.io/badge/2022-lightgrey?style=flat) **Affective Image Content Analysis: Two Decades Review and New Perspectives** | [[Paper](https://ieeexplore.ieee.org/document/9472932)]

---

<a id="datasets-benchmarks"></a>
## 📊 Datasets and Benchmarks

### 📁 Datasets
*Curated list of multimodal, physiological, and emotional datasets.*

| Source | Dataset Name | Description / Modality | Links |
| :--- | :--- | :--- | :--- |
| ![AAAI](https://img.shields.io/badge/AAAI-brightgreen?style=flat) ![2026](https://img.shields.io/badge/2026-lightgrey?style=flat) | **EmoVid** | Multimodal Emotion Video Dataset for Video Generation | [[Paper](https://arxiv.org/pdf/2511.11002)] [[Code](https://zane-zyqiu.github.io/EmoVid/)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) | **Smile Face, Sad Eyes** | Multimodal Dataset of Eye and Facial Behaviors | [[Paper](https://arxiv.org/abs/2512.16485v1)] [[Code](https://anonymous.4open.science/r/EMER-database)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) | **EM2LDL** | Multilingual Speech Corpus for Mixed Emotion Recognition | [[Paper](https://arxiv.org/abs/2511.20106v1)] [[Code](https://github.com/xingfengli/EM2LDL)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) | **RF-Behavior** | Multimodal Radio-Frequency Dataset for Emotion Analysis | [[Paper](https://arxiv.org/pdf/2511.06020v1)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) | **WELD** | Longitudinal Dataset of Workplace Emotional Dynamics | [[Paper](https://arxiv.org/pdf/2510.15221v1)] |
| ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **SEED-MYA** | A Novel Myanmar Multimodal Dataset for Enhancing Emotion Recognition | [[Paper](https://ieeexplore.ieee.org/document/11072296)] |
| ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **CoAffinity** | A Multimodal Dataset for Cognitive Load and Affect Assessment in Remote Collaboration | [[Paper](https://ieeexplore.ieee.org/abstract/document/10970421)] |
| ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **SEED-VII** | A Multimodal Dataset of Six Basic Emotions With Continuous Labels for Emotion Recognition | [[Paper](https://ieeexplore.ieee.org/document/10731546/)] [[Code](https://github.com/gx123412/SEED-VII/blob/main/README.md)] |
| ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **FEAD** | Introduction to the fNIRS-EEG Affective Database - Video Stimuli | [[Paper](https://ieeexplore.ieee.org/document/10542388)] [[Code](https://github.com/farniadb/dataset/tree/main)] |
| ![MER](https://img.shields.io/badge/MER-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **OV-MERD、MER-Caption+** | Multimodal Emotion Recognition Challenge 2025 | [[Data](https://huggingface.co/datasets/MERChallenge/MER2025)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.06](https://img.shields.io/badge/2025.06-lightgrey?style=flat) | **MMME** | Spontaneous Multi-Modal Micro-Expression (Visual-Physiological) | [[Paper](https://arxiv.org/pdf/2506.09834v2)] [[Code](https://github.com/Mac0504/MMME)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.03](https://img.shields.io/badge/2025.03-lightgrey?style=flat) | **EVA-MED** | Enhanced Valence-Arousal Multimodal Emotion Dataset | [[Paper](https://arxiv.org/pdf/2503.16584v1)] |
| ![ACL](https://img.shields.io/badge/ACL-red?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **ACE** | Akan Cinematic Emotions Dataset for Low-resource Languages | [[Paper](https://arxiv.org/abs/2502.10973)] [[Code](https://github.com/sasudavid/AkaCE)] |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-green?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) | **MERR** | Multimodal Emotion Recognition and Reasoning Dataset | [[Data](https://zebangcheng.github.io/Emotion-LLaMA/dataset/)] |
| ![Year](https://img.shields.io/badge/2024-lightgrey?style=flat) | **MER2024** | Multimodal Emotion Recognition Challenge 2024 | [[Data](https://huggingface.co/datasets/MERChallenge/MER2024)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) | **AffectNet+** | Enhancing Facial Expression Recognition with Soft-Labels | [[Paper](https://arxiv.org/pdf/2410.22506v1)] |
| ![TVCG](https://img.shields.io/badge/TVCG-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) | **An Immersive and Interactive VR Dataset to Elicit Emotions** | |[[Paper](https://ieeexplore.ieee.org/document/10670431)] |
| ![Year](https://img.shields.io/badge/2023-lightgrey?style=flat) | **MER2023** | Multimodal Emotion Recognition Challenge 2023 | [[Data](https://huggingface.co/datasets/MERChallenge/MER2023)] |
| ![TVCG](https://img.shields.io/badge/TVCG-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) | **HEADSET** | Human Emotion Awareness under Partial Occlusions | [[Paper](https://ieeexplore.ieee.org/document/10269730)] |
| ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) | **EgoCom** | Multi-Person Multimodal Egocentric Communications Dataset | [[Paper](https://ieeexplore.ieee.org/document/9200754)] |
| ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) | **CAS(ME)3** | Spontaneous Micro-Expression Database with Depth Information | [[Paper](https://doi.org/10.1109/TPAMI.2022.3174895)] |
| ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2022](https://img.shields.io/badge/2022-lightgrey?style=flat) | **MAFW** | Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild | [[Paper](https://arxiv.org/pdf/2208.00847)] [[Code](https://github.com/MAFW-database/MAFW)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2022.09](https://img.shields.io/badge/2022.09-lightgrey?style=flat) | **CH-SIMS v2.0** | Chinese Single- and Multi-modal Sentiment Dataset | [[Paper](https://arxiv.org/pdf/2209.02604)] [[Code](https://github.com/thuiar/ch-sims-v2)] |
| ![CVPR](https://img.shields.io/badge/CVPR-blue?style=flat) ![2022](https://img.shields.io/badge/2022-lightgrey?style=flat) | **FERV39k** | : A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos | [[Paper](https://arxiv.org/pdf/2203.09463)] [[Code](https://wangyanckxx.github.io/Proj_CVPR2022_FERV39k.html)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2022.05](https://img.shields.io/badge/2022.05-lightgrey?style=flat) | **M3ED** | Multi-modal Multi-scene Multi-label Emotional Dialogue | [[Paper](https://arxiv.org/abs/2205.10237)] |
| ![Year](https://img.shields.io/badge/2020-lightgrey?style=flat) | **CH-SIMS** | Chinese Single- and Multi-modal Sentiment Dataset | [[Paper](https://aclanthology.org/2020.acl-main.343/)] [[Code](https://github.com/thuiar/MMSA)] |
| ![Year](https://img.shields.io/badge/2019-lightgrey?style=flat) | **MUStARD** | Multimodal Utterances for Sarcasm and Irony | [[Paper](https://aclanthology.org/P19-1455/)] [[Code](https://github.com/Himanshu-sudo/MUStARD-dataset)] |
| ![Year](https://img.shields.io/badge/2018-lightgrey?style=flat) | **CMU-MOSEI** | Large-scale Dataset for Sentiment and Emotion Intensity | [[Data](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/)][[Paper](https://aclanthology.org/P18-1208.pdf)] |
| ![Year](https://img.shields.io/badge/2018-lightgrey?style=flat) | **MELD** | Multimodal EmotionLines Dataset (Friends TV show) | [[Paper](https://arxiv.org/pdf/1810.02508)] [[Code](https://github.com/declare-lab/MELD)] |
| ![Year](https://img.shields.io/badge/2018-lightgrey?style=flat) | **PMEmo** | Music Emotion Recognition with Physiological Signals | [[Paper](https://dl.acm.org/doi/10.1145/3206025.3206037)] [[Code](https://github.com/HuiZhangDB/PMEmo)] |
| ![Year](https://img.shields.io/badge/2017-lightgrey?style=flat) | **CMU-MOSI** | Large-scale Dataset for Sentiment and Emotion Intensity  | [[Data](https://github.com/CMU-MultiComp-Lab/CMU-MultimodalSDK)][[Paper](https://aclanthology.org/D17-1115.pdf)] |
| ![Year](https://img.shields.io/badge/2017-lightgrey?style=flat) | **AffectNet** | Facial Expression, Valence, and Arousal Computing in the Wild  | [[Data](https://mohammadmahoor.com/pages/databases/affectnet/)][[Paper](https://arxiv.org/pdf/1708.03985v4)] |
| ![Year](https://img.shields.io/badge/2017-lightgrey?style=flat) | **SEED-IV** | EEG Dataset for Emotion Recognition (SJTU) | [[Code](https://bcmi.sjtu.edu.cn/~seed/seed.html)] |
| ![Year](https://img.shields.io/badge/2015-lightgrey?style=flat) | **SEED** | EEG Dataset for Emotion Recognition (SJTU) | [[Code](https://bcmi.sjtu.edu.cn/~seed/seed.html)] |
| ![Year](https://img.shields.io/badge/2011-lightgrey?style=flat) | **DEAP** | Dataset for Emotion Analysis using Physiological signals | [[Paper](https://ieeexplore.ieee.org/document/5871728)] |
| ![Year](https://img.shields.io/badge/2008-lightgrey?style=flat) | **IEMOCAP** | Interactive Emotional Dyadic Motion Capture | [[Code](https://sail.usc.edu/iemocap/)] |
| ![Year](https://img.shields.io/badge/2008-lightgrey?style=flat) | **DFEW** | Dynamic Facial Expression in-the-Wild | [[Data](https://dfew-dataset.github.io/)][[Paper](https://arxiv.org/pdf/2008.05924)] |
| ![Year](https://img.shields.io/badge/2000-lightgrey?style=flat) | **emoDB** | German database of emotional utterances| [[Data](http://emodb.bilderbar.info/docu/)] |


### ⚖️ Benchmarks
*Holistic evaluation benchmarks for LLMs, MLLMs, and Emotional Reasoning.*

| Source | Benchmark Name | Evaluation Focus | Links |
| :--- | :--- | :--- | :--- |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) | **AV-EMO-Reasoning** | Emotional Reasoning in Omni-modal LLMs with Audio-visual Cues | [[Paper](https://arxiv.org/pdf/2510.07355v1)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) | **SEER** | The Span-based Emotion Evidence Retrieval Benchmark | [[Paper](https://arxiv.org/pdf/2510.03490v1)] [[Code](https://github.com/chailab-umich/SEER)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) | **MME-Emotion** | A Holistic Evaluation Benchmark for Emotional Intelligence in MLLMs | [[Paper](https://www.arxiv.org/pdf/2508.09210)] [[Code](https://mme-emotion.github.io/)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) | **MTMEUR** | A Multi-Turn Multimodal Emotion Understanding and Reasoning Benchmark | [[Paper](https://arxiv.org/pdf/2508.16859v1)] [[Code](https://github.com/MindIntLab-HFUT/MTMEUR)] |
| ![MER](https://img.shields.io/badge/MER-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **MER-UniBench** | A Comprehensive Evaluation for MLLM-based Emotion Understanding | [[Code](https://github.com/zeroQiaoba/AffectGPT)] |
| ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **ECDaily** | A Large-scale Benchmark for Emotion Cause Extraction in Conversations | [[Paper](https://ieeexplore.ieee.org/document/10830477)] [[Code](https://github.com/xiangju2017/ECDaily-realtime)] |
| ![ACL](https://img.shields.io/badge/ACL-red?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **ToMEmoReason** | Emotion Reasoning as a Theory of Mind Benchmark for LLMs | [[Paper](https://arxiv.org/pdf/2506.00334)] [[Code](https://github.com/GerardYeo/ToMEmoReason)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.05](https://img.shields.io/badge/2025.05-lightgrey?style=flat) | **EmotionHallucer** | Evaluating Emotion Hallucinations in MLLMs | [[Paper](https://arxiv.org/pdf/2505.11405v1)] [[Code](https://github.com/xxtars/EmotionHallucer)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.02](https://img.shields.io/badge/2025.02-lightgrey?style=flat) | **EmoBench-M** | Benchmarking Emotional Intelligence for Multimodal LLMs | [[Paper](https://arxiv.org/pdf/2502.04424v1)] [[Code](https://emo-gml.github.io/)] |
| ![ICML](https://img.shields.io/badge/ICML-brightgreen?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) | **EMMA** | An Enhanced MultiModal ReAsoning Benchmark | [[Paper](https://arxiv.org/pdf/2501.05444v1)] [[Code](https://emma-benchmark.github.io/)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.02](https://img.shields.io/badge/2024.02-lightgrey?style=flat) | **EmoBench** | Benchmarking Emotional Intelligence for Large Language Models | [[Paper](https://arxiv.org/pdf/2402.12071)][[Code](https://github.com/Sahandfer/EmoBench)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.01](https://img.shields.io/badge/2024.01-lightgrey?style=flat) | **MER-Bench** | A Unified Evaluation Benchmark for Multimodal Emotion Recognition | [[Paper](https://arxiv.org/pdf/2401.03429)] [[Code](https://github.com/zeroQiaoba/MERTools)] |
| ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2023.12](https://img.shields.io/badge/2023.12-lightgrey?style=flat) | **EQ-Bench** | A Benchmark for Emotional Intelligence in LLMs | [[Paper](https://arxiv.org/pdf/2312.06281)] [[Leaderboard](https://eqbench.com/)] |
| ![ECCV](https://img.shields.io/badge/ECCV-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) | **Affective Visual Dialog** | Large-Scale Benchmark for Emotional Reasoning (2023.08) | [[Paper](https://arxiv.org/pdf/2308.16349)] [[Code](https://affective-visual-dialog.github.io/)] |
---

<a id="emotional-intelligence"></a>
## 🤖 Emotional Intelligence in Large Models (LLM/MLLM/ALLM)

<a id="emotional-intelligence-mllm"></a>
### MLLM / Omni-modal Models (Vision+Audio+Text)
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **VidEmo: Affective-Tree Reasoning for Emotion-Centric Video Foundation Models** | [[Paper](https://arxiv.org/pdf/2511.02712v1)] [[Code](https://zzcheng.top/VidEmo)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **Learning What to Attend First: Modality-Importance-Guided Reasoning** | [[Paper](https://arxiv.org/pdf/2512.02699v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **Large Emotional World Model** | [[Paper](https://arxiv.org/pdf/2512.24149v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Learning to Hear by Seeing: VLMs to Understand Artistic Emotion** | [[Paper](https://arxiv.org/pdf/2511.12077v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Affective Multimodal Agents for Emotionally Aligned Marketing Dialogue** | [[Paper](https://arxiv.org/pdf/2511.21728v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Emotion-Coherent Reasoning for MLLMs via Emotional Rationale Verifier** | [[Paper](https://arxiv.org/pdf/2510.23506v4)] [[Code](https://github.com/Rhatanii/ERV)]
- ![COLM](https://img.shields.io/badge/COLM-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Mitigating Modal Imbalance in Multimodal Reasoning** | [[Paper](https://arxiv.org/pdf/2510.02608v2)] [[Code](https://github.com/AR-FORUM/modal-imbalance)]
- ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Affective-CoT: Decomposing Multimodal Emotion Reasoning through a Hierarchical Cognitive Workflow** | [[Paper](https://dl.acm.org/doi/10.1145/3746027.3762009)] [[Code](https://github.com/GPNU-AIoT/DARE)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **AffectGPT-R1: Leveraging RL for Open-Vocabulary Multimodal ER** | [[Paper](https://arxiv.org/pdf/2508.01318)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **The Emotional Baby Is Truly Deadly: Does your MLLM Have Emotional Flattery?** | [[Paper](https://arxiv.org/pdf/2508.03986v1)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Injecting Multimodal Information Into Pre-Trained Language Model for Multimodal Sentiment Analysis** | [[Paper](https://ieeexplore.ieee.org/document/10935629)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Affective Embodied Agent for Patient Assistance in Virtual Rehabilitation** | [[Paper](https://ieeexplore.ieee.org/document/11002736)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.05](https://img.shields.io/badge/2025.05-lightgrey?style=flat) **FEALLM: Advancing Facial Emotion Analysis in MLLMs with Synergy** | [[Paper](https://arxiv.org/pdf/2505.13419v1)] [[Code](https://github.com/953206211/FEALLM)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.04](https://img.shields.io/badge/2025.04-lightgrey?style=flat) **EIBench: Breaking Boundaries in Emotional Reasoning with MLLMs** | [[Paper](https://arxiv.org/pdf/2504.07521v2)] [[Code](https://github.com/Lum1104/EIBench)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.03](https://img.shields.io/badge/2025.03-lightgrey?style=flat) **R1-Omni: Explainable Omni-Multimodal Emotion Recognition with RL** | [[Paper](https://arxiv.org/pdf/2503.05379v2)] [[Code](https://github.com/HumanMLLM/R1-Omni)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.12](https://img.shields.io/badge/2024.12-lightgrey?style=flat) **EmoVerse: Exploring MLLMs for Sentiment and Emotion Understanding** | [[Paper](https://arxiv.org/pdf/2412.08049v3)] [[Code](https://github.com/liaolea/EmoVerse)]
- ![ICML](https://img.shields.io/badge/ICML-brightgreen?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **AffectGPT: Dataset and Framework for Explainable Multimodal ER** | [[Paper](https://arxiv.org/pdf/2407.07653v1)] [[Code](https://github.com/zeroQiaoba/AffectGPT)]
- ![NeurIPS](https://img.shields.io/badge/NeurIPS-green?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning** | [[Paper](https://arxiv.org/pdf/2406.11161v2)] [[Code](https://github.com/ZebangCheng/Emotion-LLaMA)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.06](https://img.shields.io/badge/2024.06-lightgrey?style=flat) **EmoLLM: Multimodal Emotional Understanding Meets Large Language Models** | [[Paper](https://arxiv.org/pdf/2406.16442v2)] [[Code](https://github.com/yan9qu/EmoLLM)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.03](https://img.shields.io/badge/2024.03-lightgrey?style=flat) **GPT as Psychologist? Preliminary Evaluations for GPT-4V on Affective Computing** | [[Paper](https://arxiv.org/pdf/2403.05916v2)] [[Code](https://github.com/EnVision-Research/GPT4Affectivity)]

<a id="emotional-intelligence-audio"></a>
### Audio / Speech LLMs (ALLM)
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2026.01](https://img.shields.io/badge/2026.01-lightgrey?style=flat) **Discovering and Causally Validating Emotion-Sensitive Neurons in Audio-LMs** | [[Paper](https://arxiv.org/pdf/2601.03115v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **LISTEN: Do Audio LLMs Really LISTEN, or Just Transcribe?** | [[Paper](https://arxiv.org/pdf/2510.10444v2)] [[Code](https://delijingyic.github.io/LISTEN-website/)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Semantic Differentiation in Speech ER: Descriptive and Expressive Roles** | [[Paper](https://arxiv.org/abs/2510.03060v1)]
- ![WWW](https://img.shields.io/badge/WWW-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Exploring Multimodal Pre-trained Models for Speech Emotion Recognition** | [[Paper](https://dl.acm.org/doi/epdf/10.1145/3701716.3717561)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.09](https://img.shields.io/badge/2024.09-lightgrey?style=flat) **Multi-Microphone and Multi-Modal Emotion Recognition in Reverberant Environment** | [[Paper](https://arxiv.org/pdf/2409.09545v3)]

<a id="emotional-intelligence-text"></a>
### Text-centric LLMs (Mechanisms, Empathy & Bias)
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **Large Language Models have Chain-of-Affective** | [[Paper](https://arxiv.org/pdf/2512.12283v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **PRC-Emo: Teaching ER with Prompts, Retrieval, and Curriculum Learning** | [[Paper](https://arxiv.org/pdf/2511.07061v3)] [[Code](https://github.com/LiXinran6/PRC-Emo)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Detecting and Steering LLMs’ Empathy in Action** | [[Paper](https://arxiv.org/pdf/2511.16699v1)] [[Code](https://github.com/juancadile/empathy-probes)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Gender Bias in Emotion Recognition by Large Language Models** | [[Paper](https://arxiv.org/pdf/2511.19785v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Mind Reading or Misreading? LLMs on the Big Five Personality Test** | [[Paper](https://arxiv.org/pdf/2511.23101v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **LLMs vs. Traditional Sentiment Tools: Belgian-Dutch Narratives** | [[Paper](https://arxiv.org/pdf/2511.07641v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Acquiring Common Chinese Emotional Events Using Large Language Model** | [[Paper](https://arxiv.org/pdf/2511.04989v1)]
- ![arXIV](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Decoding Emotion in the Deep: How LLMs Represent, Retain, and Express Emotion** | [[Paper](https://arxiv.org/pdf/2510.04064v2)] [[Code](https://github.com/Jingxiang-Zhang/LLM-emotion-study)]
- ![arXIV](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Do LLMs “Feel”? Emotion Circuits Discovery and Control** | [[Paper](https://arxiv.org/pdf/2510.11328v1)] [[Code](https://github.com/Aurora-cx/EmotionCircuits-LLM)]
- ![arXIV](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Emotions Where Art Thou: Emotional Latent Space of Large Language Models** | [[Paper](https://arxiv.org/pdf/2510.22042v1)]
- ![arXIV](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **The Personalization Trap: How User Memory Alters Emotional Reasoning in LLMs** | [[Paper](https://arxiv.org/pdf/2510.09905v1)]
- ![arXIV](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Evaluating Open-Source VLMs for Multimodal Sarcasm Detection** | [[Paper](https://arxiv.org/pdf/2510.11852v1)] [[Code](https://github.com/pvsnp9/sarcasm)]
- ![arXIV](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Empathic Prompting: Non-Verbal Context Integration for MLLM Conversations** | [[Paper](https://arxiv.org/pdf/2510.20743v1)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **How to Enhance Causal Discrimination of Emotional Utterances: A Case on LLMs** | [[Paper](https://ieeexplore.ieee.org/document/11039724)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Rethinking Emotion Annotations in the Era of Large Language Models** | [[Paper](https://arxiv.org/pdf/2412.07906)] [[Code](https://github.com/chailab-umich/GPT-4-Emotion-Annotation)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Aware Yet Biased: Investigating Emotional Reasoning and Appraisal Bias in Large Language Models** | [[Paper](https://ieeexplore.ieee.org/abstract/document/11045290)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **From Translation to Generative LLMs: Classification of Code-Mixed Affective Tasks** | [[Paper](https://ieeexplore.ieee.org/document/10938193)]
- ![AAAI](https://img.shields.io/badge/AAAI-brightgreen?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **MSE-Adapter: Lightweight Plugin for MLLM Sentiment Analysis and ER** | [[Paper](https://arxiv.org/abs/2502.12478)] [[Code](https://github.com/AZYoung233/MSE-Adapter)]
- ![Neural Networks](https://img.shields.io/badge/Neural%20Networks-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **DialogueLLM: Context and emotion knowledge-tuned LLMs for MERC** | [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0893608025007828)]
- ![ICASSP](https://img.shields.io/badge/ICASSP-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **LLM supervised Pre-training for MER in Conversations** | [[Paper](https://arxiv.org/pdf/2501.11468)]
- ![COLING](https://img.shields.io/badge/COLING-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **LaERC-S: Improving LLM-based ER with Speaker Characteristics** | [[Paper](https://arxiv.org/pdf/2403.07260)] [[Code](https://github.com/bigcat-1/LaERC-S)]

---

<a id="emotion-understanding"></a>
## 🔍 Emotion Understanding & Reasoning

- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2026.01](https://img.shields.io/badge/2026.01-lightgrey?style=flat) **EC2ER: From Emotion Classification to Emotional Reasoning in LLMs** | [[Paper](https://arxiv.org/pdf/2601.01407v1)] [[Code](https://github.com/kernelism/EC2ER)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Enhancing Meme Emotion Understanding with Multi-Level Modality Enhancement** | [[Paper](https://arxiv.org/pdf/2511.11126v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **Benchmarking and Bridging Emotion Conflicts for Multimodal Emotion Reasoning** | [[Paper](https://arxiv.org/pdf/2508.01181v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **Resource-Limited Multimodal Sentiment Reasoning via CoT Distillation** | [[Paper](https://arxiv.org/pdf/2508.05234v1)] [[Code](https://github.com/123sghn/MulCoTRD)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **RVISA: Reasoning and Verification for Implicit Sentiment Analysis** | [[Paper](https://arxiv.org/pdf/2407.02340)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Modeling Cognitive-Affective Processes With Appraisal and Reinforcement Learning** | [[Paper](https://arxiv.org/pdf/2309.06367)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.05](https://img.shields.io/badge/2025.05-lightgrey?style=flat) **Project Riley: Multi-Agent LLM Collaboration with Emotional Reasoning** | [[Paper](https://arxiv.org/pdf/2505.20521v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.05](https://img.shields.io/badge/2025.05-lightgrey?style=flat) **Emotion-o1: Adaptive Long Reasoning for Emotion Understanding in LLMs** | [[Paper](https://arxiv.org/pdf/2505.22548v2)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.04](https://img.shields.io/badge/2025.04-lightgrey?style=flat) **DEEMO: De-identity Multimodal Emotion Recognition and Reasoning** | [[Paper](https://arxiv.org/pdf/2504.19549v1)]
- ![ACL](https://img.shields.io/badge/ACL-red?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Listen, Watch, and Learn to Feel: Retrieval-Augmented Emotion Reasoning** | [[Paper](https://aclanthology.org/2025.findings-acl.590.pdf)]
- ![NAACL](https://img.shields.io/badge/NAACL-yellow?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Multi-Condition Guided Diffusion Network for Multimodal ER in Conversation** | [[Paper](https://aclanthology.org/2025.findings-naacl.177)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.11](https://img.shields.io/badge/2024.11-lightgrey?style=flat) **FAME-Net: Generative Emotion Cause Explanation in Multimodal Conversations** | [[Paper](https://arxiv.org/pdf/2411.02430v3)] [[Code](https://github.com/3222345200/FAME-Net)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.08](https://img.shields.io/badge/2024.08-lightgrey?style=flat) **Towards a Generative Approach for Emotion Detection and Reasoning** | [[Paper](https://arxiv.org/pdf/2408.04906v1)]
- ![IJCAI](https://img.shields.io/badge/IJCAI-yellow?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **ECR-Chain: Generative Models Better Emotion-Cause Reasoners through Chains** | [[Paper](https://arxiv.org/pdf/2405.10860)] [[Code](https://github.com/hzp3517/ECR-Chain)]
- ![CVPR](https://img.shields.io/badge/CVPR-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **EmoVIT: Revolutionizing Emotion Insights with Visual Instruction Tuning** | [[Paper](https://arxiv.org/pdf/2404.16670)][[Code](https://github.com/aimmemotion/EmoVIT)]
- ![EMNLP](https://img.shields.io/badge/EMNLP-orange?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **UniMEEC: Towards Unified Multimodal Emotion Recognition and Emotion Cause** | [[Paper](https://aclanthology.org/2024.findings-emnlp.302/)] [[Code](https://github.com/LeMei/causal-unimeec)]
- ![EMNLP](https://img.shields.io/badge/EMNLP-orange?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Enhancing Emotion-Cause Pair Extraction via Center Event Detection** | [[Paper](https://aclanthology.org/2024.findings-emnlp.632.pdf)]
- ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Revisiting Disentanglement and Fusion on Modality and Context in MERC** | [[Paper](https://arxiv.org/pdf/2308.04502)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2023.06](https://img.shields.io/badge/2023.06-lightgrey?style=flat) **Explainable Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2306.15401v6)]

---

<a id="mer-perception"></a>
## 🧠 Multimodal Emotion Recognition (MER) & Perception

<a id="mer-msa"></a>
### MER & MSA (Signal-based Fusion)
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **Multimodal Functional Maximum Correlation for Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2512.23076v1)] [[Code](https://github.com/DY9910/MFMC)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.12](https://img.shields.io/badge/2025.12-lightgrey?style=flat) **Pioneering MER in the Era of Large Models: From Closed Sets to Open Vocabularies** | [[Paper](https://arxiv.org/abs/2512.20938)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **Calibrating Multimodal Consensus for Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2510.20256v1)] [[Code](https://github.com/gw-zhong/CMC)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.10](https://img.shields.io/badge/2025.10-lightgrey?style=flat) **MS-Mix: Unveiling the Power of Mixup for Multimodal Sentiment Analysis** | [[Paper](https://arxiv.org/pdf/2510.11579v1)] [[Code](https://github.com/HongyuZhu-s/MS-Mix)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **A Trustworthy Method for Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2508.07625v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **Hierarchical MoE: Continuous MER with Incomplete Inputs** | [[Paper](https://arxiv.org/pdf/2508.02133v4)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.08](https://img.shields.io/badge/2025.08-lightgrey?style=flat) **Multimodal Video Emotion Recognition with Reliable Reasoning Priors** | [[Paper](https://arxiv.org/pdf/2508.03722v1)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **VISTANet: VIsual Spoken Textual Additive Net for Interpretable Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2208.11450)] [[Code](https://github.com/MIntelligence-Group/MMEmoRec)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.06](https://img.shields.io/badge/2025.06-lightgrey?style=flat) **Leveraging CLIP Encoder for Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2506.00903v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.04](https://img.shields.io/badge/2025.04-lightgrey?style=flat) **Leveraging Label Potential for Enhanced Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2504.05158v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.03](https://img.shields.io/badge/2025.03-lightgrey?style=flat) **Feature-Based Dual Visual Feature Extraction Model for Compound MER** | [[Paper](https://arxiv.org/pdf/2503.17453v1)] [[Code](https://github.com/MyGitHub-ax/8th_ABAW)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.03](https://img.shields.io/badge/2025.03-lightgrey?style=flat) **MAVEN: Multi-modal Attention for Valence-Arousal Emotion Network** | [[Paper](https://arxiv.org/pdf/2503.12623v2)] [[Code](https://github.com/Vrushank-Ahire/MAVEN_8th_ABAW)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.02](https://img.shields.io/badge/2025.02-lightgrey?style=flat) **A Novel Approach for MER: Multimodal semantic information fusion** | [[Paper](https://arxiv.org/pdf/2502.08573v1)] [[Code](https://github.com/ZMW-DW/DeepMSI-MER)]
- ![CVPR](https://img.shields.io/badge/CVPR-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **EMOE: Modality-Specific Enhanced Dynamic Emotion Experts** | [[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Fang_EMOE_Modality-Specific_Enhanced_Dynamic_Emotion_Experts_CVPR_2025_paper.pdf)] [[Code](https://github.com/fuyyyyy/EMOE)]
- ![ICASSP](https://img.shields.io/badge/ICASSP-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **A MoE Multimodal Graph Attention Network Framework for MER** | [[Paper](https://ieeexplore.ieee.org/document/10890390)] [[Code](https://github.com/tdfxlyh/MMGATEMO)]
- ![IJCV](https://img.shields.io/badge/IJCV-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Noise-Resistant Multimodal Transformer for Emotion Recognition** | [[Paper](https://doi.org/10.1007/s11263-024-02304-3)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.10](https://img.shields.io/badge/2024.10-lightgrey?style=flat) **OV-MER: Towards Open-Vocabulary Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2410.01495)] [[Code](https://github.com/zeroQiaoba/AffectGPT)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.09](https://img.shields.io/badge/2024.09-lightgrey?style=flat) **Early Joint Learning of Emotion Information Makes MLLM Understand You Better** | [[Paper](https://arxiv.org/pdf/2409.18971v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.09](https://img.shields.io/badge/2024.09-lightgrey?style=flat) **Hierarchical Hypercomplex Network for Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2409.09194v2)] [[Code](https://github.com/ispamm/MHyEEG)]
- ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **COLD Fusion: Uncertainty-Aware Multimodal Emotion Recognition** | [[Paper](https://ieeexplore.ieee.org/document/10287630)]
- ![ICASSP](https://img.shields.io/badge/ICASSP-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **RL-EMO: A Reinforcement Learning Framework for MER** | [[Paper](https://ieeexplore.ieee.org/document/10446459)] [[Code](https://github.com/zyh9929/RL-EMO)]
- ![AAAI](https://img.shields.io/badge/AAAI-brightgreen?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **CAMEL: Capturing Metaphorical Alignment with Context Disentangling for MER** | [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28787)]
- ![ICME](https://img.shields.io/badge/ICME-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Smile: Spiking Multi-Modal Interactive Label-Guided Enhancement Network** | [[Paper](https://ieeexplore.ieee.org/abstract/document/10688152)]
- ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Graph to Grid: Learning Deep Representations for MER** | [[Paper](https://dl.acm.org/doi/10.1145/3581783.3612074)] [[Code](https://github.com/Jinminbox/G2G)]
- ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Mining High-quality Samples from Raw Data for MER** | [[Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612862)]
- ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Building Robust Sentiment Recognition via Simple Multimodal Transformer** | [[Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612872)] [[Code](https://github.com/dingchaoyue/Multimodal-Emotion-Recognition-MER-and-MuSe-2023-Challenges)]
- ![NeurIPS](https://img.shields.io/badge/NeurIPS-green?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Incomplete Multimodality-Diffused Emotion Recognition** | [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/372cb7805eaccb2b7eed641271a30eec-Paper-Conference.pdf)] [[Code](https://github.com/mdswyz/IMDer)]
- ![CVPR](https://img.shields.io/badge/CVPR-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Decoupled Multimodal Distilling for Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2303.13802v1)] [[Code](https://github.com/mdswyz/DMD)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2022.11](https://img.shields.io/badge/2022.11-lightgrey?style=flat) **UniMSE: Towards Unified Multimodal Sentiment Analysis and Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2211.11256v1)] [[Code](https://github.com/LeMei/UniMSE)]

<a id="facial-physiological"></a>
### Facial & Physiological Affective Perception
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Facial-R1: Aligning Reasoning and Recognition for Facial Emotion Analysis** | [[Paper](https://arxiv.org/pdf/2511.10254v1)] [[Code](https://github.com/RobitsG/Facial-R1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Synheart Emotion: Privacy-Preserving On-Device ER from Biosignals** | [[Paper](https://arxiv.org/pdf/2511.06231v1)] [[Code](https://github.com/synheart-ai/synheart-emotion)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.09](https://img.shields.io/badge/2025.09-lightgrey?style=flat) **MuMTAffect: Framework for Personality and Emotion from Physiological Signals** | [[Paper](https://arxiv.org/pdf/2509.04254v1)] [[Code](https://github.com/itubrainlab/MuMTAffect)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.04](https://img.shields.io/badge/2025.04-lightgrey?style=flat) **Multimodal Representation Learning for Comprehensive Facial State Analysis** | [[Paper](https://arxiv.org/pdf/2504.10351v1)]
- ![TIP](https://img.shields.io/badge/TIP-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **PTH-Net: Dynamic Facial Expression Recognition Without Face Detection** | [[Paper](https://ieeexplore.ieee.org/document/10770138/)] [[Code](https://github.com/lm495455/PTH-Net)]
- ![ICASSP](https://img.shields.io/badge/ICASSP-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Micro-expression Spotting based on Semantic-guided Deep Fusion Model** | [[Paper](https://ieeexplore.ieee.org/document/10888501)]
- ![ICASSP](https://img.shields.io/badge/ICASSP-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Deeply Coupling EEG Signals and Eye Movements for Region-Aware ER** | [[Paper](https://ieeexplore.ieee.org/abstract/document/10888584)]
- ![TKDE](https://img.shields.io/badge/TKDE-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **PURE: Personality-Coupled MTL for Aspect-Based Multimodal Sentiment Analysis** | [[Paper](https://ieeexplore.ieee.org/document/10731889)]
- ![TIP](https://img.shields.io/badge/TIP-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Cross-Layer Contrastive Learning of Latent Semantics for Facial ER** | [[Paper](https://ieeexplore.ieee.org/document/10478291)]
- ![TIP](https://img.shields.io/badge/TIP-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Relationship-Guided Knowledge Transfer for Class-Incremental Facial ER** | [[Paper](https://ieeexplore.ieee.org/document/10471300)]
- ![TVCG](https://img.shields.io/badge/TVCG-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Multimodal Physiological Analysis of Impact of Emotion on Cognitive Control in VR** | [[Paper](https://ieeexplore.ieee.org/document/10458371)]
- ![ACM MM](https://img.shields.io/badge/ACM%20MM-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Multimodal Physiological Signals Fusion for Online Emotion Recognition** | [[Paper](https://dl.acm.org/doi/10.1145/3581783.3612555)]
- ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Brain-Machine Coupled Learning Method for Facial Emotion Recognition** | [[Paper](https://ieeexplore.ieee.org/document/10073607)]
- ![TPAMI](https://img.shields.io/badge/TPAMI-blue?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Emotional Attention: From Eye Tracking to Computational Modeling** | [[Paper](https://ieeexplore.ieee.org/document/9761748)]
- ![IEEE](https://img.shields.io/badge/IEEE-blue?style=flat) ![2021](https://img.shields.io/badge/2021-lightgrey?style=flat) **DEAP | Dataset for Emotion Analysis using Physiological signals** | [[Paper](https://ieeexplore.ieee.org/document/5871728)]

---

<a id="affective-generation"></a>
## 🗣️ Affective Generation & Synthesis

- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Hierarchical Control of Emotion Rendering in Speech Synthesis** | [[Paper](https://arxiv.org/pdf/2412.12498)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Empathetic Response Generation Through Multi-Modality** | [[Paper](https://ieeexplore.ieee.org/document/11129652)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **From Extraction to Generation: Multimodal Emotion-Cause Pair Generation in Conversations** | [[Paper](https://ieeexplore.ieee.org/document/10640186)]
- ![TAC](https://img.shields.io/badge/TAC-orange?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Controllable Multi-Speaker Emotional Speech Synthesis With an Emotion Representation of High Generalization Capability** | [[Paper](https://ieeexplore.ieee.org/abstract/document/10553521)] [[Code](https://woaki.github.io/cmetts/)]
- ![ICMR](https://img.shields.io/badge/ICMR-blue?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **EmoHuman: Fine-Grained Emotion-Controlled Talking Head Generation** | [[Paper](https://dl.acm.org/doi/epdf/10.1145/3731715.3733322)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2024.09](https://img.shields.io/badge/2024.09-lightgrey?style=flat) **Emo-DPO: Controllable Emotional Speech Synthesis via Direct Preference Optimization** | [[Paper](https://arxiv.org/pdf/2409.10157)] [[Code](https://xiaoxue1117.github.io/Emo-tts-dpo/)]
- ![ECCV](https://img.shields.io/badge/ECCV-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **EMO: Emote Portrait Alive: Generating Expressive Portrait Videos** | [[Paper](https://arxiv.org/pdf/2402.17485)] [[Code](https://github.com/HumanAIGC/EMO)]
- ![SICon](https://img.shields.io/badge/SICon-lightgrey?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **EECVAE: Eliciting Rich Positive Emotions in Dialogue Generation** | [[Paper](https://aclanthology.org/2023.sicon-1.1.pdf)] [[Code](https://github.com/taolusi/EECVAE)]

---

<a id="toolkits-challenges"></a>
## 🛠️ Toolkits & Challenges

- **MultiBench** | Standardized Toolkit for Multimodal Deep Learning. [[Paper](https://jmlr.org/papers/v24/22-1021.html)] [[Code](https://github.com/pliang279/MultiBench)]
- **MERTools** | A Holistic Toolkit for Multimodal Emotion Recognition. [[Code](https://github.com/zeroQiaoba/MERTools)]
- **OpenFace** | Real-time facial behavior analysis toolkit. [[Code](https://github.com/TadasBaltrusaitis/OpenFace)]
- ![WACV](https://img.shields.io/badge/WACV-blue?style=flat) ![2026](https://img.shields.io/badge/2026-lightgrey?style=flat) **Exploring Automated Recognition of Instructional Activity from Classroom Data** | [[Paper](https://arxiv.org/pdf/2512.00087v1)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.11](https://img.shields.io/badge/2025.11-lightgrey?style=flat) **Detecting Emotional Dynamic Trajectories: Evaluation for Emotional Support** | [[Paper](https://arxiv.org/pdf/2511.09003v1)] [[Code](https://ruochoxio.github.io/ETrajEval/)]
- ![arXiv](https://img.shields.io/badge/-arXiv-b31b1b?style=flat&logo=arxiv&logoColor=white) ![2025.03](https://img.shields.io/badge/2025.03-lightgrey?style=flat) **Automated UX Insights from User Research Videos (Facial + Sentiment)** | [[Paper](https://arxiv.org/pdf/2503.22510v1)]
- ![TVCG](https://img.shields.io/badge/TVCG-blue?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Affective Visualization Design: Leveraging Emotional Impact of Data** | [[Paper](https://ieeexplore.ieee.org/document/10301796)]
<a id="muse-challenge"></a>
### 🏆 MuSe Challenge Series
- ![MuSe](https://img.shields.io/badge/MuSe-brightgreen?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **The 6th Multimodal Sentiment Analysis Workshop and Challenge** | [[Website](https://www.muse-challenge.org/)]
- ![MuSe](https://img.shields.io/badge/MuSe-brightgreen?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **The 5th Multimodal Sentiment Analysis Challenge and Workshop: Social Perception and Humor** | [[Website](https://sites.google.com/view/muse-2024/muse-2024)] [[Paper](https://arxiv.org/pdf/2406.07753v1)] [[Code](https://github.com/amirip/MuSe-2024)]
- ![MuSe](https://img.shields.io/badge/MuSe-brightgreen?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **The 4th Multimodal Sentiment Analysis Challenge and Workshop: Mimicked Emotions, Humour and Personalisation** | [[Website](https://www.muse-challenge.org/)] [[Paper](https://arxiv.org/abs/2305.03369)]
- ![MuSe](https://img.shields.io/badge/MuSe-brightgreen?style=flat) ![2022](https://img.shields.io/badge/2022-lightgrey?style=flat) **The Multimodal Sentiment Analysis Challenge: Humor, Emotional Reactions, and Stress** | [[Website](https://sites.google.com/view/muse2022/muse2022)]
- ![MuSe](https://img.shields.io/badge/MuSe-brightgreen?style=flat) ![2021](https://img.shields.io/badge/2021-lightgrey?style=flat) **The Multimodal Sentiment Analysis Challenge: Sentiment, Emotion, Physiological-Emotion, and Stress** | [[Website](https://sites.google.com/view/muse-2021?authuser=0)]
- ![MuSe](https://img.shields.io/badge/MuSe-brightgreen?style=flat) ![2020](https://img.shields.io/badge/2020-lightgrey?style=flat) **The Multimodal Sentiment Challenge in Real-life Media** | [[Website](https://sites.google.com/view/muse2020?authuser=0)]

<a id="mer-challenge"></a>
### 🏆 MER Challenge Series
- ![MER](https://img.shields.io/badge/MER-brightgreen?style=flat) ![2025](https://img.shields.io/badge/2025-lightgrey?style=flat) **Multimodal Emotion Recognition Challenge 2025: Affective Computing Meets LLMs** | [[Website](https://zeroqiaoba.github.io/MER2025-website/)]
- ![MER](https://img.shields.io/badge/MER-brightgreen?style=flat) ![2024](https://img.shields.io/badge/2024-lightgrey?style=flat) **Multimodal Emotion Recognition Challenge 2024: Semi-supervised Learning & Open-Vocabulary** | [[Website](https://zeroqiaoba.github.io/MER2024-website/)]
- ![MER](https://img.shields.io/badge/MER-brightgreen?style=flat) ![2023](https://img.shields.io/badge/2023-lightgrey?style=flat) **Multimodal Emotion Recognition Challenge 2023: Multi-label Learning & Noise Robustness** | [[Website](http://merchallenge.cn/mer2023)]

---

## 🔗 Related Works
- [Awesome-Sentiment-Analysis](https://github.com/Ait-S/Awesome-Sentiment-Analysis)
- [Awesome-Emotion-Recognition-Reasoning](https://github.com/yuntaoshou/Awesome-Emotion-Reasoning)
- [Awesome-Multimodal-ML](https://github.com/pliang279/awesome-multimodal-ml)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Yorkson-huang/awesome-affective-computing&type=Date)](https://star-history.com/#Yorkson-huang/awesome-affective-computing&Date)
