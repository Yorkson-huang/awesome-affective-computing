<div align="center">
  
# Awesome Affective Computing: Emotion Recognition, Reasoning & Intelligence
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Yorkson-huang/awesome-affective-computing/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Yorkson-huang/awesome-affective-computing/graphs/commit-activity)

**"Teaching Machines to Sense, Think, and Feel."**

</div>

---

> *"If we want computers to be genuinely intelligent and to interact naturally with us, we must give them the ability to recognize, understand, even to have and express emotions."*  
> —— **Rosalind Picard**, *Affective Computing (1997)*

## 🌟 Introduction

**Affective Computing (AC)** is an interdisciplinary field spanning computer science, psychology, and cognitive science. As AI evolves from discriminative tasks to generative intelligence, the field is undergoing a significant paradigm shift: moving from **Signal-based Perception** (recognizing patterns in face, voice, and physiology) to **LLM-driven Emotional Reasoning** (understanding context, empathy, and causal logic).

This repository is a curated collection of research papers, datasets, and toolkits designed to track this evolution. It serves as a comprehensive roadmap for researchers exploring how Large Language Models (LLMs) and Multimodal models are redefining the boundaries of **Artificial Emotional Intelligence (AEI)**.

---

## 📑 Table of Contents
- [📚 Surveys & Reviews](#surveys-reviews)
- [📊 Datasets and Benchmarks](#datasets-benchmarks)
- [🤖 Emotional Intelligence in Large Models (LLM/MLLM/ALLM)](#emotional-intelligence)
- [🔍 Emotion Understanding & Reasoning](#emotion-understanding)
- [🧠 Multimodal Emotion Recognition (MER) & Perception](#mer-perception)
- [🗣️ Affective Generation & Synthesis](#affective-generation)
- [🛠️ Toolkits & Challenges](#toolkits-challenges)

---

<a id="surveys-reviews"></a>
## 📚 Surveys & Reviews

- [Arxiv 2025.12] **Computational emotion analysis with multimodal LLMs: Current evidence on an emerging methodological opportunity** | [[Paper](https://arxiv.org/pdf/2512.10882v1)]
- [Arxiv 2025.11] **Intelligent Agents with Emotional Intelligence: Current Trends, Challenges, and Future Prospects** | [[Paper](https://arxiv.org/pdf/2511.20657)]
- [Arxiv 2025.11] **Rethinking Facial Expression Recognition in the Era of Multimodal Large Language Models** | [[Paper](https://arxiv.org/pdf/2511.00389v1)] [[Code](https://github.com/zfkarl/UniFER)]
- [Arxiv 2025.10] **Datasets for Valence and Arousal Inference: A Survey** | [[Paper](https://arxiv.org/pdf/2510.00738v1)]
- [Arxiv 2025.09] **Multimodal Large Language Models Meet Multimodal Emotion Recognition and Reasoning: A Survey** | [[Paper](https://arxiv.org/pdf/2509.24322)]
- [TAC 2025] **SarcasmBench: Towards Evaluating Large Language Models on Sarcasm Understanding** | [[Paper](https://arxiv.org/pdf/2408.11319)]
- [TAC 2025] **A Review of Human Emotion Synthesis Based on Generative Technology** | [[Paper](https://arxiv.org/pdf/2412.07116)]
- [TAC 2025] **A Comprehensive Survey on Datasets for Affective Computing and Mental Disorder** | [[Paper](https://ieeexplore.ieee.org/document/11214492)]
- [TAC 2025] **A Systematic Review of Experimental Protocols: Towards a Uniform Framework in Virtual Reality Affective Research** | [[Paper](https://ieeexplore.ieee.org/document/10945786)]
- [TAC 2025] **Affective Computing Databases: In-Depth Analysis of Systematic Reviews and Surveys** | [[Paper](https://ieeexplore.ieee.org/document/10769002)]
- [TAC 2025] **Explainable AI for Audio and Visual Affective Computing: A Scoping Review** | [[Paper](https://ieeexplore.ieee.org/document/10766406)]
- [Arxiv 2025.05] **Multimodal Emotion Recognition in Conversations: A Survey of Methods, Trends, Challenges and Prospects** | [[Paper](https://arxiv.org/pdf/2505.20511)]
- [Arxiv 2025.04] **A Survey on Multimodal Music Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2504.18799v1)]
- [Arxiv 2024.09] **Recent Trends of Multimodal Affective Computing: A Survey from an NLP Perspective** | [[Paper](https://arxiv.org/pdf/2409.07388)]
- [Arxiv 2024.08] **Affective computing in the era of large language models: A survey from the nlp perspective** | [[Paper](https://arxiv.org/pdf/2408.04638)]
- [Arxiv 2024.06] **Large Language Models Meet Text-Centric Multimodal Sentiment Analysis: A Survey** | [[Paper](https://arxiv.org/pdf/2406.08068)]
- [Arxiv 2023.12] **A Comprehensive Survey on Multi-modal Conversational Emotion Recognition with Deep Learning** | [[Paper](https://arxiv.org/pdf/2312.05735v1)]
- [Arxiv 2023.05] **A Comprehensive Survey on Affective Computing; Challenges, Trends, and Future Directions** | [[Paper](https://arxiv.org/pdf/2305.07665)]
- [Arxiv 2023.05] **Multimodal Sentiment Analysis: A Survey** | [[Paper](https://arxiv.org/pdf/2305.07611)]
- [Arxiv 2022.03] **A Systematic Review on Affective Computing: Emotion Models and Databases** | [[Paper](https://arxiv.org/pdf/2203.06935)]
- [TPAMI 2022] **Video-Based Facial Micro-Expression Analysis: A Survey of Datasets and Algorithms** | [[Paper](https://ieeexplore.ieee.org/document/9382112)]
- [TPAMI 2022] **Affective Image Content Analysis: Two Decades Review and New Perspectives** | [[Paper](https://ieeexplore.ieee.org/document/9472932)]

---

<a id="datasets-benchmarks"></a>
## 📊 Datasets and Benchmarks

### 📁 Datasets
*Curated list of multimodal, physiological, and emotional datasets.*

| Source | Dataset Name | Description / Modality | Links |
| :--- | :--- | :--- | :--- |
| [AAAI 2026] | **EmoVid** | Multimodal Emotion Video Dataset for Video Generation | [[Paper](https://arxiv.org/pdf/2511.11002)] [[Code](https://zane-zyqiu.github.io/EmoVid/)] |
| [Arxiv 2025.12] | **Smile Face, Sad Eyes** | Multimodal Dataset of Eye and Facial Behaviors | [[Paper](https://arxiv.org/abs/2512.16485v1)] [[Code](https://anonymous.4open.science/r/EMER-database)] |
| [Arxiv 2025.11] | **EM2LDL** | Multilingual Speech Corpus for Mixed Emotion Recognition | [[Paper](https://arxiv.org/abs/2511.20106v1)] [[Code](https://github.com/xingfengli/EM2LDL)] |
| [Arxiv 2025.11] | **RF-Behavior** | Multimodal Radio-Frequency Dataset for Emotion Analysis | [[Paper](https://arxiv.org/pdf/2511.06020v1)] |
| [Arxiv 2025.10] | **WELD** | Longitudinal Dataset of Workplace Emotional Dynamics | [[Paper](https://arxiv.org/pdf/2510.15221v1)] |
| [TAC 2025] | **SEED-MYA** | A Novel Myanmar Multimodal Dataset for Enhancing Emotion Recognition | [[Paper](https://ieeexplore.ieee.org/document/11072296)] |
| [TAC 2025] | **CoAffinity** | A Multimodal Dataset for Cognitive Load and Affect Assessment in Remote Collaboration | [[Paper](https://ieeexplore.ieee.org/abstract/document/10970421)] |
| [TAC 2025] | **SEED-VII** | A Multimodal Dataset of Six Basic Emotions With Continuous Labels for Emotion Recognition | [[Paper](https://ieeexplore.ieee.org/document/10731546/)] [[Code](https://github.com/gx123412/SEED-VII/blob/main/README.md)] |
| [TAC 2025] | **FEAD** | Introduction to the fNIRS-EEG Affective Database - Video Stimuli | [[Paper](https://ieeexplore.ieee.org/document/10542388)] [[Code](https://github.com/farniadb/dataset/tree/main)] |
| [MER 2025] | **OV-MERD、MER-Caption+** | Multimodal Emotion Recognition Challenge 2025 | [[Data](https://huggingface.co/datasets/MERChallenge/MER2025)] |
| [Arxiv 2025.06] | **MMME** | Spontaneous Multi-Modal Micro-Expression (Visual-Physiological) | [[Paper](https://arxiv.org/pdf/2506.09834v2)] [[Code](https://github.com/Mac0504/MMME)] |
| [Arxiv 2025.03] | **EVA-MED** | Enhanced Valence-Arousal Multimodal Emotion Dataset | [[Paper](https://arxiv.org/pdf/2503.16584v1)] |
| [ACL 2025] | **ACE** | Akan Cinematic Emotions Dataset for Low-resource Languages | [[Paper](https://arxiv.org/abs/2502.10973)] [[Code](https://github.com/sasudavid/AkaCE)] |
| [NeurIPS 2024] | **MERR** | Multimodal Emotion Recognition and Reasoning Dataset | [[Data](https://zebangcheng.github.io/Emotion-LLaMA/dataset/)] |
| [2024] | **MER2024** | Multimodal Emotion Recognition Challenge 2024 | [[Data](https://huggingface.co/datasets/MERChallenge/MER2024)] |
| [Arxiv 2024] | **AffectNet+** | Enhancing Facial Expression Recognition with Soft-Labels | [[Paper](https://arxiv.org/pdf/2410.22506v1)] |
| [TVCG 2024] | **An Immersive and Interactive VR Dataset to Elicit Emotions** | |[[Paper](https://ieeexplore.ieee.org/document/10670431)] |
| [2023] | **MER2023** | Multimodal Emotion Recognition Challenge 2023 | [[Data](https://huggingface.co/datasets/MERChallenge/MER2023)] |
| [TVCG 2023] | **HEADSET** | Human Emotion Awareness under Partial Occlusions | [[Paper](https://ieeexplore.ieee.org/document/10269730)] |
| [TPAMI 2023] | **EgoCom** | Multi-Person Multimodal Egocentric Communications Dataset | [[Paper](https://ieeexplore.ieee.org/document/9200754)] |
| [TPAMI 2023] | **CAS(ME)3** | Spontaneous Micro-Expression Database with Depth Information | [[Paper](https://doi.org/10.1109/TPAMI.2022.3174895)] |
| [ACM MM 2022] | **MAFW** | Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild | [[Paper](https://arxiv.org/pdf/2208.00847)] [[Code](https://github.com/MAFW-database/MAFW)] |
| [Arxiv 2022.09] | **CH-SIMS v2.0** | Chinese Single- and Multi-modal Sentiment Dataset | [[Paper](https://arxiv.org/pdf/2209.02604)] [[Code](https://github.com/thuiar/ch-sims-v2)] |
| [CVPR 2022] | **FERV39k** | : A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos | [[Paper](https://arxiv.org/pdf/2203.09463)] [[Code](https://wangyanckxx.github.io/Proj_CVPR2022_FERV39k.html)] |
| [Arxiv 2022.05] | **M3ED** | Multi-modal Multi-scene Multi-label Emotional Dialogue | [[Paper](https://arxiv.org/abs/2205.10237)] |
| [2020] | **CH-SIMS** | Chinese Single- and Multi-modal Sentiment Dataset | [[Paper](https://aclanthology.org/2020.acl-main.343/)] [[Code](https://github.com/thuiar/MMSA)] |
| [2019] | **MUStARD** | Multimodal Utterances for Sarcasm and Irony | [[Paper](https://aclanthology.org/P19-1455/)] [[Code](https://github.com/Himanshu-sudo/MUStARD-dataset)] |
| [2018] | **CMU-MOSEI** | Large-scale Dataset for Sentiment and Emotion Intensity | [[Data](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/)][[Paper](https://aclanthology.org/P18-1208.pdf)] |
| [2018] | **MELD** | Multimodal EmotionLines Dataset (Friends TV show) | [[Paper](https://arxiv.org/pdf/1810.02508)] [[Code](https://github.com/declare-lab/MELD)] |
| [2018] | **PMEmo** | Music Emotion Recognition with Physiological Signals | [[Paper](https://dl.acm.org/doi/10.1145/3206025.3206037)] [[Code](https://github.com/HuiZhangDB/PMEmo)] |
| [2017] | **CMU-MOSI** | Large-scale Dataset for Sentiment and Emotion Intensity  | [[Data](https://github.com/CMU-MultiComp-Lab/CMU-MultimodalSDK)][[Paper](https://aclanthology.org/D17-1115.pdf)] |
| [2017] | **AffectNet** | Facial Expression, Valence, and Arousal Computing in the Wild  | [[Data](https://mohammadmahoor.com/pages/databases/affectnet/)][[Paper](https://arxiv.org/pdf/1708.03985v4)] |
| [2017] | **SEED-IV** | EEG Dataset for Emotion Recognition (SJTU) | [[Code](https://bcmi.sjtu.edu.cn/~seed/seed.html)] |
| [2015] | **SEED** | EEG Dataset for Emotion Recognition (SJTU) | [[Code](https://bcmi.sjtu.edu.cn/~seed/seed.html)] |
| [2011] | **DEAP** | Dataset for Emotion Analysis using Physiological signals | [[Paper](https://ieeexplore.ieee.org/document/5871728)] |
| [2008] | **IEMOCAP** | Interactive Emotional Dyadic Motion Capture | [[Code](https://sail.usc.edu/iemocap/)] |
| [2008] | **DFEW** | Dynamic Facial Expression in-the-Wild | [[Data](https://dfew-dataset.github.io/)][[Paper](https://arxiv.org/pdf/2008.05924)] |
| [2000] | **emoDB** | German database of emotional utterances| [[Data](http://emodb.bilderbar.info/docu/)] |


### ⚖️ Benchmarks
*Holistic evaluation benchmarks for LLMs, MLLMs, and Emotional Reasoning.*

| Source | Benchmark Name | Evaluation Focus | Links |
| :--- | :--- | :--- | :--- |
| [Arxiv 2025.10] | **AV-EMO-Reasoning** | Emotional Reasoning in Omni-modal LLMs with Audio-visual Cues | [[Paper](https://arxiv.org/pdf/2510.07355v1)] |
| [Arxiv 2025.10] | **SEER** | The Span-based Emotion Evidence Retrieval Benchmark | [[Paper](https://arxiv.org/pdf/2510.03490v1)] [[Code](https://github.com/chailab-umich/SEER)] |
| [Arxiv 2025.08] | **MME-Emotion** | A Holistic Evaluation Benchmark for Emotional Intelligence in MLLMs | [[Paper](https://www.arxiv.org/pdf/2508.09210)] [[Code](https://mme-emotion.github.io/)] |
| [Arxiv 2025.08] | **MTMEUR** | A Multi-Turn Multimodal Emotion Understanding and Reasoning Benchmark | [[Paper](https://arxiv.org/pdf/2508.16859v1)] [[Code](https://github.com/MindIntLab-HFUT/MTMEUR)] |
| [MER 2025] | **MER-UniBench** | A Comprehensive Evaluation for MLLM-based Emotion Understanding | [[Code](https://github.com/zeroQiaoba/AffectGPT)] |
| [TAC 2025] | **ECDaily** | A Large-scale Benchmark for Emotion Cause Extraction in Conversations | [[Paper](https://ieeexplore.ieee.org/document/10830477)] [[Code](https://github.com/xiangju2017/ECDaily-realtime)] |
| [ACL 2025] | **ToMEmoReason** | Emotion Reasoning as a Theory of Mind Benchmark for LLMs | [[Paper](https://arxiv.org/pdf/2506.00334)] [[Code](https://github.com/GerardYeo/ToMEmoReason)] |
| [Arxiv 2025.05] | **EmotionHallucer** | Evaluating Emotion Hallucinations in MLLMs | [[Paper](https://arxiv.org/pdf/2505.11405v1)] [[Code](https://github.com/xxtars/EmotionHallucer)] |
| [Arxiv 2025.02] | **EmoBench-M** | Benchmarking Emotional Intelligence for Multimodal LLMs | [[Paper](https://arxiv.org/pdf/2502.04424v1)] [[Code](https://emo-gml.github.io/)] |
| [ICML 2025] | **EMMA** | An Enhanced MultiModal ReAsoning Benchmark | [[Paper](https://arxiv.org/pdf/2501.05444v1)] [[Code](https://emma-benchmark.github.io/)] |
| [Arxiv 2024.02] | **EmoBench** | Benchmarking Emotional Intelligence for Large Language Models | [[Paper](https://arxiv.org/pdf/2402.12071)][[Code](https://github.com/Sahandfer/EmoBench)] |
| [Arxiv 2024.01] | **MER-Bench** | A Unified Evaluation Benchmark for Multimodal Emotion Recognition | [[Paper](https://arxiv.org/pdf/2401.03429)] [[Code](https://github.com/zeroQiaoba/MERTools)] |
| [Arxiv 2023.12] | **EQ-Bench** | A Benchmark for Emotional Intelligence in LLMs | [[Paper](https://arxiv.org/pdf/2312.06281)] [[Leaderboard](https://eqbench.com/)] |
| [ECCV 2024] | **Affective Visual Dialog** | Large-Scale Benchmark for Emotional Reasoning (2023.08) | [[Paper](https://arxiv.org/pdf/2308.16349)] [[Code](https://affective-visual-dialog.github.io/)] |
---

<a id="emotional-intelligence"></a>
## 🤖 Emotional Intelligence in Large Models (LLM/MLLM/ALLM)

### MLLM / Omni-modal Models (Vision+Audio+Text)
- [Arxiv 2025.12] **VidEmo: Affective-Tree Reasoning for Emotion-Centric Video Foundation Models** | [[Paper](https://arxiv.org/pdf/2511.02712v1)] [[Code](https://zzcheng.top/VidEmo)]
- [Arxiv 2025.12] **Learning What to Attend First: Modality-Importance-Guided Reasoning** | [[Paper](https://arxiv.org/pdf/2512.02699v1)]
- [Arxiv 2025.12] **Large Emotional World Model** | [[Paper](https://arxiv.org/pdf/2512.24149v1)]
- [Arxiv 2025.11] **Learning to Hear by Seeing: VLMs to Understand Artistic Emotion** | [[Paper](https://arxiv.org/pdf/2511.12077v1)]
- [Arxiv 2025.11] **Affective Multimodal Agents for Emotionally Aligned Marketing Dialogue** | [[Paper](https://arxiv.org/pdf/2511.21728v1)]
- [Arxiv 2025.10] **Emotion-Coherent Reasoning for MLLMs via Emotional Rationale Verifier** | [[Paper](https://arxiv.org/pdf/2510.23506v4)] [[Code](https://github.com/Rhatanii/ERV)]
- [COLM 2025] **Mitigating Modal Imbalance in Multimodal Reasoning** | [[Paper](https://arxiv.org/pdf/2510.02608v2)] [[Code](https://github.com/AR-FORUM/modal-imbalance)]
- [ACM MM 2025] **Affective-CoT: Decomposing Multimodal Emotion Reasoning through a Hierarchical Cognitive Workflow** | [[Paper](https://dl.acm.org/doi/10.1145/3746027.3762009)] [[Code](https://github.com/GPNU-AIoT/DARE)]
- [Arxiv 2025.08] **AffectGPT-R1: Leveraging RL for Open-Vocabulary Multimodal ER** | [[Paper](https://arxiv.org/pdf/2508.01318)]
- [Arxiv 2025.08] **The Emotional Baby Is Truly Deadly: Does your MLLM Have Emotional Flattery?** | [[Paper](https://arxiv.org/pdf/2508.03986v1)]
- [TAC 2025] **Injecting Multimodal Information Into Pre-Trained Language Model for Multimodal Sentiment Analysis** | [[Paper](https://ieeexplore.ieee.org/document/10935629)]
- [TAC 2025] **Affective Embodied Agent for Patient Assistance in Virtual Rehabilitation** | [[Paper](https://ieeexplore.ieee.org/document/11002736)]
- [Arxiv 2025.05] **FEALLM: Advancing Facial Emotion Analysis in MLLMs with Synergy** | [[Paper](https://arxiv.org/pdf/2505.13419v1)] [[Code](https://github.com/953206211/FEALLM)]
- [Arxiv 2025.04] **EIBench: Breaking Boundaries in Emotional Reasoning with MLLMs** | [[Paper](https://arxiv.org/pdf/2504.07521v2)] [[Code](https://github.com/Lum1104/EIBench)]
- [Arxiv 2025.03] **R1-Omni: Explainable Omni-Multimodal Emotion Recognition with RL** | [[Paper](https://arxiv.org/pdf/2503.05379v2)] [[Code](https://github.com/HumanMLLM/R1-Omni)]
- [Arxiv 2024.12] **EmoVerse: Exploring MLLMs for Sentiment and Emotion Understanding** | [[Paper](https://arxiv.org/pdf/2412.08049v3)] [[Code](https://github.com/liaolea/EmoVerse)]
- [ICML 2025] **AffectGPT: Dataset and Framework for Explainable Multimodal ER** | [[Paper](https://arxiv.org/pdf/2407.07653v1)] [[Code](https://github.com/zeroQiaoba/AffectGPT)]
- [NeurIPS 2024] **Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning** | [[Paper](https://arxiv.org/pdf/2406.11161v2)] [[Code](https://github.com/ZebangCheng/Emotion-LLaMA)]
- [Arxiv 2024.06] **EmoLLM: Multimodal Emotional Understanding Meets Large Language Models** | [[Paper](https://arxiv.org/pdf/2406.16442v2)] [[Code](https://github.com/yan9qu/EmoLLM)]
- [Arxiv 2024.03] **GPT as Psychologist? Preliminary Evaluations for GPT-4V on Affective Computing** | [[Paper](https://arxiv.org/pdf/2403.05916v2)] [[Code](https://github.com/EnVision-Research/GPT4Affectivity)]

### Audio / Speech LLMs (ALLM)
- [Arxiv 2026.01] **Discovering and Causally Validating Emotion-Sensitive Neurons in Audio-LMs** | [[Paper](https://arxiv.org/pdf/2601.03115v1)]
- [Arxiv 2025.10] **LISTEN: Do Audio LLMs Really LISTEN, or Just Transcribe?** | [[Paper](https://arxiv.org/pdf/2510.10444v2)] [[Code](https://delijingyic.github.io/LISTEN-website/)]
- [Arxiv 2025.10] **Semantic Differentiation in Speech ER: Descriptive and Expressive Roles** | [[Paper](https://arxiv.org/abs/2510.03060v1)]
- [WWW 2025] **Exploring Multimodal Pre-trained Models for Speech Emotion Recognition** | [[Paper](https://dl.acm.org/doi/epdf/10.1145/3701716.3717561)]
- [Arxiv 2024.09] **Multi-Microphone and Multi-Modal Emotion Recognition in Reverberant Environment** | [[Paper](https://arxiv.org/pdf/2409.09545v3)]

### Text-centric LLMs (Mechanisms, Empathy & Bias)
- [Arxiv 2025.12] **Large Language Models have Chain-of-Affective** | [[Paper](https://arxiv.org/pdf/2512.12283v1)]
- [Arxiv 2025.11] **PRC-Emo: Teaching ER with Prompts, Retrieval, and Curriculum Learning** | [[Paper](https://arxiv.org/pdf/2511.07061v3)] [[Code](https://github.com/LiXinran6/PRC-Emo)]
- [Arxiv 2025.11] **Detecting and Steering LLMs’ Empathy in Action** | [[Paper](https://arxiv.org/pdf/2511.16699v1)] [[Code](https://github.com/juancadile/empathy-probes)]
- [Arxiv 2025.11] **Gender Bias in Emotion Recognition by Large Language Models** | [[Paper](https://arxiv.org/pdf/2511.19785v1)]
- [Arxiv 2025.11] **Mind Reading or Misreading? LLMs on the Big Five Personality Test** | [[Paper](https://arxiv.org/pdf/2511.23101v1)]
- [Arxiv 2025.11] **LLMs vs. Traditional Sentiment Tools: Belgian-Dutch Narratives** | [[Paper](https://arxiv.org/pdf/2511.07641v1)]
- [Arxiv 2025.11] **Acquiring Common Chinese Emotional Events Using Large Language Model** | [[Paper](https://arxiv.org/pdf/2511.04989v1)]
- [Arxiv 2025.10] **Decoding Emotion in the Deep: How LLMs Represent, Retain, and Express Emotion** | [[Paper](https://arxiv.org/pdf/2510.04064v2)] [[Code](https://github.com/Jingxiang-Zhang/LLM-emotion-study)]
- [Arxiv 2025.10] **Do LLMs “Feel”? Emotion Circuits Discovery and Control** | [[Paper](https://arxiv.org/pdf/2510.11328v1)] [[Code](https://github.com/Aurora-cx/EmotionCircuits-LLM)]
- [Arxiv 2025.10] **Emotions Where Art Thou: Emotional Latent Space of Large Language Models** | [[Paper](https://arxiv.org/pdf/2510.22042v1)]
- [Arxiv 2025.10] **The Personalization Trap: How User Memory Alters Emotional Reasoning in LLMs** | [[Paper](https://arxiv.org/pdf/2510.09905v1)]
- [Arxiv 2025.10] **Evaluating Open-Source VLMs for Multimodal Sarcasm Detection** | [[Paper](https://arxiv.org/pdf/2510.11852v1)] [[Code](https://github.com/pvsnp9/sarcasm)]
- [Arxiv 2025.10] **Empathic Prompting: Non-Verbal Context Integration for MLLM Conversations** | [[Paper](https://arxiv.org/pdf/2510.20743v1)]
- [TAC 2025] **How to Enhance Causal Discrimination of Emotional Utterances: A Case on LLMs** | [[Paper](https://ieeexplore.ieee.org/document/11039724)]
- [TAC 2025] **Rethinking Emotion Annotations in the Era of Large Language Models** | [[Paper](https://arxiv.org/pdf/2412.07906)] [[Code](https://github.com/chailab-umich/GPT-4-Emotion-Annotation)]
- [TAC 2025] **Aware Yet Biased: Investigating Emotional Reasoning and Appraisal Bias in Large Language Models** | [[Paper](https://ieeexplore.ieee.org/abstract/document/11045290)]
- [TAC 2025] **From Translation to Generative LLMs: Classification of Code-Mixed Affective Tasks** | [[Paper](https://ieeexplore.ieee.org/document/10938193)]
- [AAAI 2025] **MSE-Adapter: Lightweight Plugin for MLLM Sentiment Analysis and ER** | [[Paper](https://arxiv.org/abs/2502.12478)] [[Code](https://github.com/AZYoung233/MSE-Adapter)]
- [Neural Networks 2025] **DialogueLLM: Context and emotion knowledge-tuned LLMs for MERC** | [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0893608025007828)]
- [ICASSP 2025] **LLM supervised Pre-training for MER in Conversations** | [[Paper](https://arxiv.org/pdf/2501.11468)]
- [COLING 2025] **LaERC-S: Improving LLM-based ER with Speaker Characteristics** | [[Paper](https://arxiv.org/pdf/2403.07260)] [[Code](https://github.com/bigcat-1/LaERC-S)]

---

<a id="emotion-understanding"></a>
## 🔍 Emotion Understanding & Reasoning

- [Arxiv 2026.01] **EC2ER: From Emotion Classification to Emotional Reasoning in LLMs** | [[Paper](https://arxiv.org/pdf/2601.01407v1)] [[Code](https://github.com/kernelism/EC2ER)]
- [Arxiv 2025.11] **Enhancing Meme Emotion Understanding with Multi-Level Modality Enhancement** | [[Paper](https://arxiv.org/pdf/2511.11126v1)]
- [Arxiv 2025.08] **Benchmarking and Bridging Emotion Conflicts for Multimodal Emotion Reasoning** | [[Paper](https://arxiv.org/pdf/2508.01181v1)]
- [Arxiv 2025.08] **Resource-Limited Multimodal Sentiment Reasoning via CoT Distillation** | [[Paper](https://arxiv.org/pdf/2508.05234v1)] [[Code](https://github.com/123sghn/MulCoTRD)]
- [TAC 2025] **RVISA: Reasoning and Verification for Implicit Sentiment Analysis** | [[Paper](https://arxiv.org/pdf/2407.02340)]
- [TAC 2025] **Modeling Cognitive-Affective Processes With Appraisal and Reinforcement Learning** | [[Paper](https://arxiv.org/pdf/2309.06367)]
- [Arxiv 2025.05] **Project Riley: Multi-Agent LLM Collaboration with Emotional Reasoning** | [[Paper](https://arxiv.org/pdf/2505.20521v1)]
- [Arxiv 2025.05] **Emotion-o1: Adaptive Long Reasoning for Emotion Understanding in LLMs** | [[Paper](https://arxiv.org/pdf/2505.22548v2)]
- [Arxiv 2025.04] **DEEMO: De-identity Multimodal Emotion Recognition and Reasoning** | [[Paper](https://arxiv.org/pdf/2504.19549v1)]
- [ACL 2025] **Listen, Watch, and Learn to Feel: Retrieval-Augmented Emotion Reasoning** | [[Paper](https://aclanthology.org/2025.findings-acl.590.pdf)]
- [NAACL 2025] **Multi-Condition Guided Diffusion Network for Multimodal ER in Conversation** | [[Paper](https://aclanthology.org/2025.findings-naacl.177)]
- [Arxiv 2024.11] **FAME-Net: Generative Emotion Cause Explanation in Multimodal Conversations** | [[Paper](https://arxiv.org/pdf/2411.02430v3)] [[Code](https://github.com/3222345200/FAME-Net)]
- [Arxiv 2024.08] **Towards a Generative Approach for Emotion Detection and Reasoning** | [[Paper](https://arxiv.org/pdf/2408.04906v1)]
- [IJCAI 2025] **ECR-Chain: Generative Models Better Emotion-Cause Reasoners through Chains** | [[Paper](https://arxiv.org/pdf/2405.10860)] [[Code](https://github.com/hzp3517/ECR-Chain)]
- [CVPR 2024]**EmoVIT: Revolutionizing Emotion Insights with Visual Instruction Tuning** | [[Paper](https://arxiv.org/pdf/2404.16670)][[Code](https://github.com/aimmemotion/EmoVIT)]
- [EMNLP 2024] **UniMEEC: Towards Unified Multimodal Emotion Recognition and Emotion Cause** | [[Paper](https://aclanthology.org/2024.findings-emnlp.302/)] [[Code](https://github.com/LeMei/causal-unimeec)]
- [EMNLP 2024] **Enhancing Emotion-Cause Pair Extraction via Center Event Detection** | [[Paper](https://aclanthology.org/2024.findings-emnlp.632.pdf)]
- [ACM MM 2023] **Revisiting Disentanglement and Fusion on Modality and Context in MERC** | [[Paper](https://arxiv.org/pdf/2308.04502)]
- [Arxiv 2023.06] **Explainable Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2306.15401v6)]

---

<a id="mer-perception"></a>
## 🧠 Multimodal Emotion Recognition (MER) & Perception

### MER & MSA (Signal-based Fusion)
- [Arxiv 2025.12] **Multimodal Functional Maximum Correlation for Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2512.23076v1)] [[Code](https://github.com/DY9910/MFMC)]
- [Arxiv 2025.12] **Pioneering MER in the Era of Large Models: From Closed Sets to Open Vocabularies** | [[Paper](https://arxiv.org/abs/2512.20938)]
- [Arxiv 2025.10] **Calibrating Multimodal Consensus for Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2510.20256v1)] [[Code](https://github.com/gw-zhong/CMC)]
- [Arxiv 2025.10] **MS-Mix: Unveiling the Power of Mixup for Multimodal Sentiment Analysis** | [[Paper](https://arxiv.org/pdf/2510.11579v1)] [[Code](https://github.com/HongyuZhu-s/MS-Mix)]
- [Arxiv 2025.08] **A Trustworthy Method for Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2508.07625v1)]
- [Arxiv 2025.08] **Hierarchical MoE: Continuous MER with Incomplete Inputs** | [[Paper](https://arxiv.org/pdf/2508.02133v4)]
- [Arxiv 2025.08] **Multimodal Video Emotion Recognition with Reliable Reasoning Priors** | [[Paper](https://arxiv.org/pdf/2508.03722v1)]
- [TAC 2025] **VISTANet: VIsual Spoken Textual Additive Net for Interpretable Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2208.11450)] [[Code](https://github.com/MIntelligence-Group/MMEmoRec)]
- [Arxiv 2025.06] **Leveraging CLIP Encoder for Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2506.00903v1)]
- [Arxiv 2025.04] **Leveraging Label Potential for Enhanced Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2504.05158v1)]
- [Arxiv 2025.03] **Feature-Based Dual Visual Feature Extraction Model for Compound MER** | [[Paper](https://arxiv.org/pdf/2503.17453v1)] [[Code](https://github.com/MyGitHub-ax/8th_ABAW)]
- [Arxiv 2025.03] **MAVEN: Multi-modal Attention for Valence-Arousal Emotion Network** | [[Paper](https://arxiv.org/pdf/2503.12623v2)] [[Code](https://github.com/Vrushank-Ahire/MAVEN_8th_ABAW)]
- [Arxiv 2025.02] **A Novel Approach for MER: Multimodal semantic information fusion** | [[Paper](https://arxiv.org/pdf/2502.08573v1)] [[Code](https://github.com/ZMW-DW/DeepMSI-MER)]
- [CVPR 2025] **EMOE: Modality-Specific Enhanced Dynamic Emotion Experts** | [[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Fang_EMOE_Modality-Specific_Enhanced_Dynamic_Emotion_Experts_CVPR_2025_paper.pdf)] [[Code](https://github.com/fuyyyyy/EMOE)]
- [ICASSP 2025] **A MoE Multimodal Graph Attention Network Framework for MER** | [[Paper](https://ieeexplore.ieee.org/document/10890390)] [[Code](https://github.com/tdfxlyh/MMGATEMO)]
- [IJCV 2025] **Noise-Resistant Multimodal Transformer for Emotion Recognition** | [[Paper](https://doi.org/10.1007/s11263-024-02304-3)]
- [Arxiv 2024.10] **OV-MER: Towards Open-Vocabulary Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2410.01495)] [[Code](https://github.com/zeroQiaoba/AffectGPT)]
- [Arxiv 2024.09] **Early Joint Learning of Emotion Information Makes MLLM Understand You Better** | [[Paper](https://arxiv.org/pdf/2409.18971v1)]
- [Arxiv 2024.09] **Hierarchical Hypercomplex Network for Multimodal Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2409.09194v2)] [[Code](https://github.com/ispamm/MHyEEG)]
- [TPAMI 2024] **COLD Fusion: Uncertainty-Aware Multimodal Emotion Recognition** | [[Paper](https://ieeexplore.ieee.org/document/10287630)]
- [ICASSP 2024] **RL-EMO: A Reinforcement Learning Framework for MER** | [[Paper](https://ieeexplore.ieee.org/document/10446459)] [[Code](https://github.com/zyh9929/RL-EMO)]
- [AAAI 2024] **CAMEL: Capturing Metaphorical Alignment with Context Disentangling for MER** | [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28787)]
- [ICME 2024] **Smile: Spiking Multi-Modal Interactive Label-Guided Enhancement Network** | [[Paper](https://ieeexplore.ieee.org/abstract/document/10688152)]
- [ACM MM 2023] **Graph to Grid: Learning Deep Representations for MER** | [[Paper](https://dl.acm.org/doi/10.1145/3581783.3612074)] [[Code](https://github.com/Jinminbox/G2G)]
- [ACM MM 2023] **Mining High-quality Samples from Raw Data for MER** | [[Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612862)]
- [ACM MM 2023] **Building Robust Sentiment Recognition via Simple Multimodal Transformer** | [[Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612872)] [[Code](https://github.com/dingchaoyue/Multimodal-Emotion-Recognition-MER-and-MuSe-2023-Challenges)]
- [NeurIPS 2023] **Incomplete Multimodality-Diffused Emotion Recognition** | [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/372cb7805eaccb2b7eed641271a30eec-Paper-Conference.pdf)] [[Code](https://github.com/mdswyz/IMDer)]
- [CVPR 2023] **Decoupled Multimodal Distilling for Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2303.13802v1)] [[Code](https://github.com/mdswyz/DMD)]
- [Arxiv 2022.11] **UniMSE: Towards Unified Multimodal Sentiment Analysis and Emotion Recognition** | [[Paper](https://arxiv.org/pdf/2211.11256v1)] [[Code](https://github.com/LeMei/UniMSE)]

### Facial & Physiological Affective Perception
- [Arxiv 2025.11] **Facial-R1: Aligning Reasoning and Recognition for Facial Emotion Analysis** | [[Paper](https://arxiv.org/pdf/2511.10254v1)] [[Code](https://github.com/RobitsG/Facial-R1)]
- [Arxiv 2025.11] **Synheart Emotion: Privacy-Preserving On-Device ER from Biosignals** | [[Paper](https://arxiv.org/pdf/2511.06231v1)] [[Code](https://github.com/synheart-ai/synheart-emotion)]
- [Arxiv 2025.09] **MuMTAffect: Framework for Personality and Emotion from Physiological Signals** | [[Paper](https://arxiv.org/pdf/2509.04254v1)] [[Code](https://github.com/itubrainlab/MuMTAffect)]
- [Arxiv 2025.04] **Multimodal Representation Learning for Comprehensive Facial State Analysis** | [[Paper](https://arxiv.org/pdf/2504.10351v1)]
- [TIP 2025] **PTH-Net: Dynamic Facial Expression Recognition Without Face Detection** | [[Paper](https://ieeexplore.ieee.org/document/10770138/)] [[Code](https://github.com/lm495455/PTH-Net)]
- [ICASSP 2025] **Micro-expression Spotting based on Semantic-guided Deep Fusion Model** | [[Paper](https://ieeexplore.ieee.org/document/10888501)]
- [ICASSP 2025] **Deeply Coupling EEG Signals and Eye Movements for Region-Aware ER** | [[Paper](https://ieeexplore.ieee.org/abstract/document/10888584)]
- [TKDE 2025] **PURE: Personality-Coupled MTL for Aspect-Based Multimodal Sentiment Analysis** | [[Paper](https://ieeexplore.ieee.org/document/10731889)]
- [TIP 2024] **Cross-Layer Contrastive Learning of Latent Semantics for Facial ER** | [[Paper](https://ieeexplore.ieee.org/document/10478291)]
- [TIP 2024] **Relationship-Guided Knowledge Transfer for Class-Incremental Facial ER** | [[Paper](https://ieeexplore.ieee.org/document/10471300)]
- [TVCG 2024] **Multimodal Physiological Analysis of Impact of Emotion on Cognitive Control in VR** | [[Paper](https://ieeexplore.ieee.org/document/10458371)]
- [ACM MM 2023] **Multimodal Physiological Signals Fusion for Online Emotion Recognition** | [[Paper](https://dl.acm.org/doi/10.1145/3581783.3612555)]
- [TPAMI 2023] **Brain-Machine Coupled Learning Method for Facial Emotion Recognition** | [[Paper](https://ieeexplore.ieee.org/document/10073607)]
- [TPAMI 2023] **Emotional Attention: From Eye Tracking to Computational Modeling** | [[Paper](https://ieeexplore.ieee.org/document/9761748)]
- [IEEE 2021] **DEAP | Dataset for Emotion Analysis using Physiological signals** | [[Paper](https://ieeexplore.ieee.org/document/5871728)]

---

<a id="affective-generation"></a>
## 🗣️ Affective Generation & Synthesis

- [TAC 2025] **Hierarchical Control of Emotion Rendering in Speech Synthesis** | [[Paper](https://arxiv.org/pdf/2412.12498)]
- [TAC 2025] **Empathetic Response Generation Through Multi-Modality** | [[Paper](https://ieeexplore.ieee.org/document/11129652)]
- [TAC 2025] **From Extraction to Generation: Multimodal Emotion-Cause Pair Generation in Conversations** | [[Paper](https://ieeexplore.ieee.org/document/10640186)]
- [TAC 2025] **Controllable Multi-Speaker Emotional Speech Synthesis With an Emotion Representation of High Generalization Capability** | [[Paper](https://ieeexplore.ieee.org/abstract/document/10553521)] [[Code](https://woaki.github.io/cmetts/)]
- [ICMR 2025] **EmoHuman: Fine-Grained Emotion-Controlled Talking Head Generation** | [[Paper](https://dl.acm.org/doi/epdf/10.1145/3731715.3733322)]
- [Arxiv 2024.09] **Emo-DPO: Controllable Emotional Speech Synthesis via Direct Preference Optimization** | [[Paper](https://arxiv.org/pdf/2409.10157)] [[Code](https://xiaoxue1117.github.io/Emo-tts-dpo/)]
- [ECCV 2024] **EMO: Emote Portrait Alive: Generating Expressive Portrait Videos** | [[Paper](https://arxiv.org/pdf/2402.17485)] [[Code](https://github.com/HumanAIGC/EMO)]
- [SICon 2023] **EECVAE: Eliciting Rich Positive Emotions in Dialogue Generation** | [[Paper](https://aclanthology.org/2023.sicon-1.1.pdf)] [[Code](https://github.com/taolusi/EECVAE)]

---

<a id="toolkits-challenges"></a>
## 🛠️ Toolkits & Challenges

- **MultiBench** | Standardized Toolkit for Multimodal Deep Learning. [[Paper](https://jmlr.org/papers/v24/22-1021.html)] [[Code](https://github.com/pliang279/MultiBench)]
- **MERTools** | A Holistic Toolkit for Multimodal Emotion Recognition. [[Code](https://github.com/zeroQiaoba/MERTools)]
- **OpenFace** | Real-time facial behavior analysis toolkit. [[Code](https://github.com/TadasBaltrusaitis/OpenFace)]
- [WACV 2026] **Exploring Automated Recognition of Instructional Activity from Classroom Data** | [[Paper](https://arxiv.org/pdf/2512.00087v1)]
- [Arxiv 2025.11] **Detecting Emotional Dynamic Trajectories: Evaluation for Emotional Support** | [[Paper](https://arxiv.org/pdf/2511.09003v1)] [[Code](https://ruochoxio.github.io/ETrajEval/)]
- [Arxiv 2025.03] **Automated UX Insights from User Research Videos (Facial + Sentiment)** | [[Paper](https://arxiv.org/pdf/2503.22510v1)]
- [TVCG 2024] **Affective Visualization Design: Leveraging Emotional Impact of Data** | [[Paper](https://ieeexplore.ieee.org/document/10301796)]
### 🏆 MuSe Challenge Series
- [MuSe 2025] **The 6th Multimodal Sentiment Analysis Workshop and Challenge** | [[Website](https://www.muse-challenge.org/)]
- [MuSe 2024] **The 5th Multimodal Sentiment Analysis Challenge and Workshop: Social Perception and Humor** | [[Website](https://sites.google.com/view/muse-2024/muse-2024)] [[Paper](https://arxiv.org/pdf/2406.07753v1)] [[Code](https://github.com/amirip/MuSe-2024)]
- [MuSe 2023] **The 4th Multimodal Sentiment Analysis Challenge and Workshop: Mimicked Emotions, Humour and Personalisation** | [[Website](https://www.muse-challenge.org/)] [[Paper](https://arxiv.org/abs/2305.03369)]
- [MuSe 2022] **The Multimodal Sentiment Analysis Challenge: Humor, Emotional Reactions, and Stress** | [[Website](https://sites.google.com/view/muse2022/muse2022)]
- [MuSe 2021] **The Multimodal Sentiment Analysis Challenge: Sentiment, Emotion, Physiological-Emotion, and Stress** | [[Website](https://sites.google.com/view/muse-2021?authuser=0)]
- [MuSe 2020] **The Multimodal Sentiment Challenge in Real-life Media** | [[Website](https://sites.google.com/view/muse2020?authuser=0)]

### 🏆 MER Challenge Series
- [MER 2025] **Multimodal Emotion Recognition Challenge 2025: Affective Computing Meets LLMs** | [[Website](https://zeroqiaoba.github.io/MER2025-website/)]
- [MER 2024] **Multimodal Emotion Recognition Challenge 2024: Semi-supervised Learning & Open-Vocabulary** | [[Website](https://zeroqiaoba.github.io/MER2024-website/)]
- [MER 2023] **Multimodal Emotion Recognition Challenge 2023: Multi-label Learning & Noise Robustness** | [[Website](http://merchallenge.cn/mer2023)]

---

## 🔗 Related Works
- [Awesome-Sentiment-Analysis](https://github.com/Ait-S/Awesome-Sentiment-Analysis)
- [Awesome-Emotion-Recognition-Reasoning](https://github.com/yuntaoshou/Awesome-Emotion-Reasoning)
- [Awesome-Multimodal-ML](https://github.com/pliang279/awesome-multimodal-ml)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Yorkson-huang/awesome-affective-computing&type=Date)](https://star-history.com/#Yorkson-huang/awesome-affective-computing&Date)
