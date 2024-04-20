# Awesome MLLM Hallucination [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->
This is a repository for organizing papres, codes and other resources related to hallucination of Multimodal Large Language Models (MLLM), or called Large Vision-Language Models (LVLM).

Hallucination in LLM usually refers to the phenomenon that the generated content is nonsensical or unfaithful to the provided source content, such as violation of input instruction, or containing factual errors, etc.
In the context of MLLM, hallucination refers to the phenomenon that the generated text is semantically coherent but inconsistent with the given visual content.
The community has been constantly making progress on analyzing, detecting, and mitigating hallucination in MLLM.

#### :books: How to read?
The main contribution of a specific paper is proposing either a new hallucination benchmark (metric) or proposing a hallucination mitigation method.
The analysis and detection of hallucination are only part of the whole paper, serving as the basis of evaluation and mitigation.
Therefore, we divide the paper into two categories: **hallucination evaluation** and **hallucination mitigation**.
In each category, the paper are listd in an order **from new to old**.
Note that there might be some duplicated papers in the two categories. Those papers contain both evaluation benchmark and mitigation method.

#### :high_brightness: This project is still on-going, pull requests are welcomed!!

If you have any suggestions (missing papers, new papers, key researchers or typos), please feel free to edit and pull a request. Just letting us know the title of papers can also be a great contribution to us. You can do this by open issue or contact us directly via email.

#### :star: If you find this repo useful, please star it!!!


## Table of Contents <!-- omit in toc -->
- [Hallucination Benchmarks](#hallucination-benchmarks)
- [Hallucination Mitigation](#hallucination-mitigation)



### Hallucination Benchmarks 

+ **ALOHa** [ALOHa: A New Measure for Hallucination in Captioning Models](https://arxiv.org/abs/2404.02904v1) (Apr. 03, 2024, NAACL 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02904v1)

+ **IllusionVQA** [IllusionVQA: A Challenging Optical Illusion Dataset for Vision Language Models](https://arxiv.org/abs/2403.15952) (Mar. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15952)

+ **PhD** [PhD: A Prompted Visual Hallucination Evaluation Dataset](https://arxiv.org/abs/2403.11116) (Mar. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.11116)

+ [AIGCs Confuse AI Too: Investigating and Explaining Synthetic Image-induced Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2403.08542) (Mar. 13, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.08542)

+ **Hal-Eval** [Hal-Eval: A Universal and Fine-grained Hallucination Evaluation Framework for Large Vision Language Models](https://arxiv.org/abs/2402.15721) (Feb. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15721)

+ **VHTest** [Visual Hallucinations of Multi-modal Large Language Models](https://arxiv.org/abs/2402.14683v1) (Feb. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14683v1)
  [![Star](https://img.shields.io/github/stars/wenhuang2000/VHTest.svg?style=social&label=Star)](https://github.com/wenhuang2000/VHTest)

+ **MAD-Bench** [How Easy is It to Fool Your Multimodal LLMs? An Empirical Analysis on Deceptive Prompts](https://arxiv.org/abs/2402.13220) (Feb. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.13220)

+ **MHaluBench** [Unified Hallucination Detection for Multimodal Large Language Models](https://arxiv.org/abs/2402.03190) (Feb. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03190)
  [![Star](https://img.shields.io/github/stars/OpenKG-ORG/EasyDetect.svg?style=social&label=Star)](https://github.com/OpenKG-ORG/EasyDetect)

+ **VQAv2-IDK** [Visually Dehallucinative Instruction Generation: Know What You Don't Know](https://arxiv.org/abs/2402.09717) (Feb. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09717)

+ **CorrelationQA** [The Instinctive Bias: Spurious Images lead to Hallucination in MLLMs](https://arxiv.org/abs/2402.03757) (Feb. 06, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03757)
  [![Star](https://img.shields.io/github/stars/MasaiahHan/CorrelationQA.svg?style=social&label=Star)](https://github.com/MasaiahHan/CorrelationQA)

+ **MMVP** [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209) (Jan. 11, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.06209)

+ **MOCHa (OpenCHAIR)** [MOCHa: Multi-Objective Reinforcement Mitigating Caption Hallucinations](https://arxiv.org/abs/2312.03631) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03631)
  [![Star](https://img.shields.io/github/stars/assafbk/mocha_code.svg?style=social&label=Star)](https://github.com/assafbk/mocha_code)

+ **FGHE** [Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites](https://arxiv.org/abs/2312.01701)  (Dec. 04, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.01701)
  [![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star)](https://github.com/Anonymousanoy/FOHE)

+ **MERLIM** [Behind the Magic, MERLIM: Multi-modal Evaluation Benchmark for Large Image-Language Models](https://arxiv.org/abs/2312.02219) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02219)

+ **CCEval** [HallE-Switch: Controlling Object Hallucination in Large Vision Language Models](https://arxiv.org/abs/2310.01779v2) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01779v2)
  [![Star](https://img.shields.io/github/stars/bronyayang/HallE_Switch.svg?style=social&label=Star)](https://github.com/bronyayang/HallE_Switch)

+ **HallusionBench** [HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination & Visual Illusion in Large Vision-Language Models](https://arxiv.org/abs/2310.14566) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14566)

+ **RAH-Bench** [Mitigating Hallucination in Visual Language Models with Visual Supervision](https://arxiv.org/abs/2311.16479) (Nov. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16479)

+ **AMBER** [An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation](https://arxiv.org/abs/2311.07397) (Nov. 13, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07397)
  [![Star](https://img.shields.io/github/stars/junyangwang0410/AMBER.svg?style=social&label=Star)](https://github.com/junyangwang0410/AMBER)

+ **Bingo** [Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges](https://arxiv.org/abs/2311.03287) (Nov. 7, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.03287)
  [![Star](https://img.shields.io/github/stars/gzcch/Bingo.svg?style=social&label=Star)](https://github.com/gzcch/Bingo)

+ **FAITHSCORE** [FAITHSCORE: Evaluating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2311.01477) (Nov. 2, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.01477)
  [![Star](https://img.shields.io/github/stars/bcdnlp/FAITHSCORE.svg?style=social&label=Star)](https://github.com/bcdnlp/FAITHSCORE)

+ **HaELM** [Evaluation and Analysis of Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2308.15126) (Oct. 10, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.15126)
  [![Star](https://img.shields.io/github/stars/junyangwang0410/HaELM.svg?style=social&label=Star)](https://github.com/junyangwang0410/HaELM)

+ **NOPE** [Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2310.05338) (Oct. 9, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05338)

+ **LRV (GAVIE)** [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565) (Sep., 29 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.14565)
  [![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star)](https://github.com/FuxiaoLiu/LRV-Instruction)

+ **MMHal-Bench** [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2306.14565) (Sep. 25, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14525)
  [![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star)](https://github.com/llava-rlhf/LLaVA-RLHF)

+ **CIEM** [CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning](https://arxiv.org/abs/2309.02301) (NeurlPS Workshop)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.02301)

+ **POPE** [Evaluating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2305.10355) (EMNLP 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10355)
  [![Star](https://img.shields.io/github/stars/AoiDragon/POPE.svg?style=social&label=Star)](https://github.com/AoiDragon/POPE)

+ **CHAIR** [Object Hallucination in Image Captioning](https://arxiv.org/abs/1809.02156) (EMNLP 2018)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1809.02156)



### Hallucination Mitigation 

+ **FACT** [Fact :Teaching MLLMs with Faithful, Concise and Transferable Rationales](https://arxiv.org/abs/2404.11129) (Apr. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.11129)

+ **SeVa** [Self-Supervised Visual Preference Alignment](https://arxiv.org/abs/2404.10501) (Apr. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10501)

+ **DFTG** [Prescribing the Right Remedy: Mitigating Hallucinations in Large Vision-Language Models via Targeted Instruction Tuning](https://arxiv.org/abs/2404.10332) (Apr. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10332)

+ **FGAIF** [FGAIF: Aligning Large Vision-Language Models with Fine-grained AI Feedback](https://arxiv.org/abs/2404.05046) (Apr. 07, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05046)

+ **ICD** [Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding](https://arxiv.org/abs/2403.18715) (Mar. 27, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.18715)

+ **ESREAL** [Exploiting Semantic Reconstruction to Mitigate Hallucinations in Vision-Language Models](https://arxiv.org/abs/2403.16167) (Mar. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16167)

+ **Pensieve** [Pensieve: Retrospect-then-Compare Mitigates Visual Hallucination](https://arxiv.org/abs/2403.14401) (Mar. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14401)

+ **M3ID** [Multi-Modal Hallucination Control by Visual Information Grounding](https://arxiv.org/abs/2403.14003) (Mar. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14003)

+ **DVP** [What if...?: Counterfactual Inception to Mitigate Hallucination Effects in Large Multimodal Models](https://arxiv.org/abs/2403.13513) (Mar. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.13513)

+ **AIT** [Mitigating Dialogue Hallucination for Large Multi-modal Models via Adversarial Instruction Tuning](https://arxiv.org/abs/2403.10492) (Mar. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.10492)

+ **HALC** [HALC: Object Hallucination Reduction via Adaptive Focal-Contrast Decoding](https://arxiv.org/abs/2403.00425) (Mar. 01, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.00425)
  [![Star](https://img.shields.io/github/stars/BillChan226/HALC.svg?style=social&label=Star)](https://github.com/BillChan226/HALC)

+ **IBD** [IBD: Alleviating Hallucinations in Large Vision-Language Models via Image-Biased Decoding](https://arxiv.org/abs/2402.18476) (Feb. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.18476)

+ **CGD** [Seeing is Believing: Mitigating Hallucination in Large Vision-Language Models via CLIP-Guided Decoding](https://arxiv.org/abs/2402.15300) (Feb. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15300)

+ **Less is More** [Less is More: Mitigating Multimodal Hallucination from an EOS Decision Perspective](https://arxiv.org/abs/2402.14545) (Feb. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14545)
  [![Star](https://img.shields.io/github/stars/yuezih/less-is-more.svg?style=social&label=Star)](https://github.com/yuezih/less-is-more)

+ **LogicCheckGPT** [Logical Closed Loop: Uncovering Object Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2402.11622) (Feb. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.11622)
  [![Star](https://img.shields.io/github/stars/Hyperwjf/LogicCheckGPT.svg?style=social&label=Star)](https://github.com/Hyperwjf/LogicCheckGPT)

+ **POVID** [Aligning Modalities in Vision Large Language Models via Preference Fine-tuning](https://arxiv.org/abs/2402.11411) (Feb. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.11411)
  [![Star](https://img.shields.io/github/stars/YiyangZhou/POVID.svg?style=social&label=Star)](https://github.com/YiyangZhou/POVID)

+ **EFUF** [EFUF: Efficient Fine-grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models](https://arxiv.org/abs/2402.09801) (Feb. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09801)

+ **IDK-Instruction** [Visually Dehallucinative Instruction Generation: Know What You Don't Know](https://arxiv.org/abs/2402.09717) (Feb. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09717)

+ **MARINE** [Mitigating Object Hallucination in Large Vision-Language Models via Classifier-Free Guidance](https://arxiv.org/abs/2402.08680) (Feb. 13, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.08680)

+ **Skip \n** [Skip \n: A Simple Method to Reduce Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2402.01345) (Feb. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01345)

+ **ViGoR** [ViGoR: Improving Visual Grounding of Large Vision Language Models with Fine-Grained Reward Modeling](https://arxiv.org/abs/2402.06118) (Feb. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.06118)

+ **LAR-LAF** [Enhancing Multimodal Large Language Models with Vision Detection Models: An Empirical Study](https://arxiv.org/abs/2401.17981) (Jan. 31, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.17981)

+ **HACL** [Hallucination Augmented Contrastive Learning for Multimodal Large Language Model](https://arxiv.org/abs/2312.06968) (Dec. 12, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06968)

+ **MOCHa (OpenCHAIR)** [MOCHa: Multi-Objective Reinforcement Mitigating Caption Hallucinations](https://arxiv.org/abs/2312.03631) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03631)
  [![Star](https://img.shields.io/github/stars/assafbk/mocha_code.svg?style=social&label=Star)](https://github.com/assafbk/mocha_code)

+ **FGHE** [Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites](https://arxiv.org/abs/2312.01701) (Dec. 04, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.01701)
  [![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star)](https://github.com/Anonymousanoy/FOHE)

+ **HallE-Switch** [HallE-Switch: Controlling Object Hallucination in Large Vision Language Models](https://arxiv.org/abs/2310.01779v2) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01779v2)
  [![Star](https://img.shields.io/github/stars/bronyayang/HallE_Switch.svg?style=social&label=Star)](https://github.com/bronyayang/HallE_Switch)

+ **VCD** [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849) (Dec. 01, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00849)
  [![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V.svg?style=social&label=Star)](https://github.com/RLHF-V/RLHF-V)

+ **OPERA** [OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation](https://arxiv.org/abs/2311.17911) (Nov. 29, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17911)
  [![Star](https://img.shields.io/github/stars/shikiw/OPERA.svg?style=social&label=Star)](https://github.com/shikiw/OPERA)

+ **VCD** [Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding](https://arxiv.org/abs/2311.16922) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16922)
  [![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VCD.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/VCD)

+ **HA-DPO** [Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization](https://arxiv.org/abs/2311.16839) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16839)

+ **RAH-Bench** [Mitigating Hallucination in Visual Language Models with Visual Supervision](https://arxiv.org/abs/2311.16479) (Nov. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16479)

+ **HalluciDoctor** [HalluciDoctor: Mitigating Hallucinatory Toxicity in Visual Instruction Data](https://arxiv.org/abs/2311.13614) (Nov. 22, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13614)
  [![Star](https://img.shields.io/github/stars/Yuqifan1117/HalluciDoctor.svg?style=social&label=Star)](https://github.com/Yuqifan1117/HalluciDoctor)

+ **Volcano** [Volcano: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision](https://arxiv.org/abs/2311.07362) (Nov. 14, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07362)
  [![Star](https://img.shields.io/github/stars/kaistAI/Volcano.svg?style=social&label=Star)](https://github.com/kaistAI/Volcano)

+ **Woodpecker** [Woodpecker: Hallucination Correction for Multimodal Large Language Models](https://arxiv.org/abs/2310.16045) (Oct. 24, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.16045)
  [![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)](https://github.com/BradyFU/Woodpecker)

+ **LURE** [Analyzing and Mitigating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2310.00754) (Oct. 1, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00754)
  [![Star](https://img.shields.io/github/stars/YiyangZhou/LURE.svg?style=social&label=Star)](https://github.com/YiyangZhou/LURE)

+ **LRV-Instruction** [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565) (Sep. 29, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.14565)
  [![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star)](https://github.com/FuxiaoLiu/LRV-Instruction)

+ **LLaVA-RLHF** [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2306.14565) (Sep. 25, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14525)
  [![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star)](https://github.com/llava-rlhf/LLaVA-RLHF)

+ **VIGC** [VIGC: Visual Instruction Generation and Correction](https://arxiv.org/abs/2308.12714) (Sep. 11, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.12714)
  [![Star](https://img.shields.io/github/stars/opendatalab/VIGC.svg?style=social&label=Star)](https://github.com/opendatalab/VIGC)

+ **HalDectect** [Detecting and Preventing Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2308.06394) (Aug. 18, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.06394)


