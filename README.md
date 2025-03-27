# Awesome MLLM Hallucination [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

## [Hallucination of Multimodal Large Language Models: A Survey](https://arxiv.org/abs/2404.18930)
### :star: News! We have released a comprehensive survey of MLLM hallucination.

<p align="center">
  <img src="assets/tax.png" alt="TAX" style="display: block; margin: 0 auto;" />
</p>

----

This is a repository for organizing papres, codes and other resources related to hallucination of Multimodal Large Language Models (MLLM), or called Large Vision-Language Models (LVLM).

Hallucination in LLM usually refers to the phenomenon that the generated content is nonsensical or unfaithful to the provided source content, such as violation of input instruction, or containing factual errors, etc.
In the context of MLLM, hallucination refers to the phenomenon that the generated text is semantically coherent but inconsistent with the given visual content.
The community has been constantly making progress on analyzing, detecting, and mitigating hallucination in MLLM.

#### :books: How to read?
The main contribution of a specific paper is proposing either a new hallucination benchmark (metric) or proposing a hallucination mitigation method.
The analysis and detection of hallucination are only part of the whole paper, serving as the basis of evaluation and mitigation.
Therefore, we divide the papers into two categories: **hallucination evaluation & analysis ** and **hallucination mitigation**.
In each category, the paper are listd in an order **from new to old**.
Note that there might be some duplicated papers in the two categories. Those papers contain both evaluation benchmark and mitigation method.

#### :high_brightness: This project is still on-going, pull requests are welcomed!!

If you have any suggestions (missing papers, new papers, key researchers or typos), please feel free to edit and pull a request. Just letting us know the title of papers can also be a great contribution to us. You can do this by open issue or contact us directly via email.

#### :star: If you find this repo useful, please star it!!!


## Table of Contents <!-- omit in toc -->
- [Hallucination Survey](#hallucination-survey)
- [Hallucination Evaluation & Analysis ](#hallucination-evaluation--analysis)
- [Hallucination Mitigation](#hallucination-mitigation)


### Hallucination Survey
+ [Hallucination of Multimodal Large Language Models: A Survey](https://arxiv.org/abs/2404.18930) (Apr. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.18930)


### Hallucination Evaluation & Analysis 
+ **UNSCENE** [MASH-VLM:Mitigating Action-Scene Hallucination in Video-LLMs through Disentangled Spatial-Temporal Representations](https://arxiv.org/abs/2503.15871) (Mar. 20, 2025, CVPR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.15871)

+ **MedHallTune** [An Instruction-Tuning Benchmark for Mitigating Medical Hallucination in Vision-Language Models](https://arxiv.org/abs/2502.20780) (Feb. 28, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20780)
  [![Star](https://img.shields.io/github/stars/russellyq/MedHallTune.svg?style=social&label=Star)](https://github.com/russellyq/MedHallTune)

+ **F-CLIPScore** [Vision-Encoders (Already) Know What They See: Mitigating Object Hallucination via Simple Fine-Grained CLIPScore](https://arxiv.org/abs/2502.20034) (Feb. 27, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20034)
  [![Star](https://img.shields.io/github/stars/abzb1/f-clip.svg?style=social&label=Star)](https://github.com/abzb1/f-clip)

+ **CutPaste&Find** [Efficient Multimodal Hallucination Detector with Visual-aid Knowledge Base](https://arxiv.org/abs/2502.12591) (Mar. 18, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.12591)

+ [DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities](https://arxiv.org/abs/2502.07905) (Feb. 11, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07905)

+ **CAOS** [Evaluating Hallucination in Large Vision-Language Models based on Context-Aware Object Similarities](https://arxiv.org/abs/2501.15046) (Jan. 25, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.15046)

+ **HALLUCINOGEN** [Towards a Systematic Evaluation of Hallucinations in Large-Vision Language Models](https://arxiv.org/abs/2412.20622) (Dec. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.20622)

+ **MedHallBench** [A New Benchmark for Assessing Hallucination in Medical Large Language Models](https://arxiv.org/abs/2412.18947) (Dec. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.18947)

+ [Delve into Visual Contrastive Decoding for Hallucination Mitigation of Large Vision-Language Models](https://arxiv.org/abs/2412.06775) (Dec. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06775)

+ **VidHalluc** [Evaluating Temporal Hallucinations in Multimodal Large Language Models for Video Understanding](https://www.arxiv.org/abs/2412.03735) (Dec. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2412.03735)

+ [Who Brings the Frisbee: Probing Hidden Hallucination Factors in Large Vision-Language Model via Causality Analysis](https://www.arxiv.org/abs/2412.02946) (Dec. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2412.02946)

+ [Beyond Logit Lens: Contextual Embeddings for Robust Hallucination Detection & Grounding in VLMs](https://arxiv.org/abs/2411.19187v1) (Nov. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19187v1)

+ **DHCP** [Detecting Hallucinations by Cross-modal Attention Pattern in Large Vision-Language Models](https://arxiv.org/abs/2411.18659) (Nov. 27, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18659)

+ **VidHal** [Benchmarking Temporal Hallucinations in Vision LLMs](https://www.arxiv.org/abs/2411.16771) (Nov. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2411.16771)
  [![Star](https://img.shields.io/github/stars/Lookuz/VidHal.svg?style=social&label=Star)](https://github.com/Lookuz/VidHal)

+ [Devils in Middle Layers of Large Vision-Language Models: Interpreting, Detecting and Mitigating Object Hallucinations via Attention Lens](https://www.arxiv.org/abs/2411.16724) (Nov. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2411.16724)

+ **VL-Uncertainty** [Detecting Hallucination in Large Vision-Language Model via Uncertainty Estimation](https://arxiv.org/abs/2411.11919) (Nov. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.11919)
  [![Star](https://img.shields.io/github/stars/Ruiyang-061X/VL-Uncertainty.svg?style=social&label=Star)](https://github.com/Ruiyang-061X/VL-Uncertainty)

+ **H-POPE** [Hierarchical Polling-based Probing Evaluation of Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2411.04077) (Nov. 06, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04077)

+ **Tri-He** [Unified Triplet-Level Hallucination Evaluation for Large Vision-Language Models](https://arxiv.org/abs/2410.23114) (Oct. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.23114)
  [![Star](https://img.shields.io/github/stars/wujunjie1998/Tri-HE.svg?style=social&label=Star)](https://github.com/wujunjie1998/Tri-HE)

+ **AVHBench** [A Cross-Modal Hallucination Benchmark for Audio-Visual Large Language Models](https://arxiv.org/abs/2410.18325) (Oct. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.18325)

+ **CMM** [The Curse of Multi-Modalities: Evaluating Hallucinations of Large Multimodal Models across Language, Visual, and Audio](https://arxiv.org/abs/2410.12787) (Oct. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.12787)
  [![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/CMM.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/CMM)

+ **VHExpansion** [Automatically Generating Visual Hallucination Test Cases for Multimodal Large Language Models](https://arxiv.org/abs/2410.11242) (Oct. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.11242)
  [![Star](https://img.shields.io/github/stars/lycheeefish/VHExpansion.svg?style=social&label=Star)](https://github.com/lycheeefish/VHExpansion)

+ **LongHalQA** [Long-Context Hallucination Evaluation for MultiModal Large Language Models](https://arxiv.org/abs/2410.09962) (Oct. 13, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.09962)
  [![Star](https://img.shields.io/github/stars/hanqiu-hq/LongHalQA.svg?style=social&label=Star)](https://github.com/hanqiu-hq/LongHalQA)

+ **EventHallusion** [Diagnosing Event Hallucinations in Video LLMs](https://arxiv.org/abs/2409.16597) (Sep. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16597)
  [![Star](https://img.shields.io/github/stars/Stevetich/EventHallusion.svg?style=social&label=Star)](https://github.com/Stevetich/EventHallusion)

+ **FIHA** [Autonomous Hallucination Evaluation in Vision-Language Models with Davidson Scene Graphs](https://arxiv.org/abs/2409.13612) (Sep. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.13612)

+ **CAST** [CAST: Cross-modal Alignment Similarity Test for Vision Language Models](https://arxiv.org/abs/2409.11007) (Sep. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.11007)
  [![Star](https://img.shields.io/github/stars/gautierdag/cast.svg?style=social&label=Star)](https://github.com/gautierdag/cast)

+ **QL-Bench** [Explore the Hallucination on Low-level Perception for MLLMs](https://www.arxiv.org/abs/2409.09748) (Sep. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.09748)

+ **ODE** [Open-Set Evaluation of Hallucinations in Multimodal Large Language Models](https://web3.arxiv.org/abs/2409.09318) (Sep. 14, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://web3.arxiv.org/abs/2409.09318)

+ **Pfram** [Understanding Multimodal Hallucination with Parameter-Free Representation Alignment](https://arxiv.org/abs/2409.01151) (Sep. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01151)
  [![Star](https://img.shields.io/github/stars/yellow-binary-tree/Pfram.svg?style=social&label=Star)](https://github.com/yellow-binary-tree/Pfram)

+ [Pre-Training Multimodal Hallucination Detectors with Corrupted Grounding Data](https://arxiv.org/abs/2409.00238) (Aug. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.00238)

+ **Reefknot** [Reefknot: A Comprehensive Benchmark for Relation Hallucination Evaluation, Analysis and Mitigation in Multimodal Large Language Models](https://arxiv.org/abs/2408.09429) (Aug. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09429)

+ **Hallu-PI** [Hallu-PI: Evaluating Hallucination in Multi-modal Large Language Models within Perturbed Inputs](https://arxiv.org/abs/2408.01355) (Aug. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.01355)
  [![Star](https://img.shields.io/github/stars/NJUNLP/Hallu-PI.svg?style=social&label=Star)](https://github.com/NJUNLP/Hallu-PI)

+ **HaloQuest** [HaloQuest: A Visual Hallucination Dataset for Advancing Multimodal Reasoning](https://arxiv.org/abs/2407.15680) (Jul. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.15680)

+ **ROPE** [Multi-Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2407.06192) (Jul. 08, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.06192)
  [![Star](https://img.shields.io/github/stars/sled-group/moh.svg?style=social&label=Star)](https://github.com/sled-group/moh)

+ **BEAF** [BEAF: Observing BEfore-AFter Changes to Evaluate Hallucination in Vision-language Models](https://arxiv.org/abs/2407.13442) (Jun. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.13442)
  [![Star](https://img.shields.io/github/stars/postech-ami/BEAF.svg?style=social&label=Star)](https://github.com/postech-ami/BEAF)

+ **HAVEN** [Exploring Hallucination of Large Multimodal Models in Video Understanding: Benchmark, Analysis and Mitigation](https://arxiv.org/abs/2503.19622) (March. 26, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.19622)
  [![Star](https://img.shields.io/github/stars/Hongcheng-Gao/HAVEN.svg?style=social&label=Star)](https://github.com/Hongcheng-Gao/HAVEN)

+ **VideoHallucer** [VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models](https://arxiv.org/abs/2406.16338) (Jun. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16338)
  [![Star](https://img.shields.io/github/stars/patrick-tssn/VideoHallucer.svg?style=social&label=Star)](https://github.com/patrick-tssn/VideoHallucer)

+ **HQHBench** [Evaluating the Quality of Hallucination Benchmarks for Large Vision-Language Models](https://arxiv.org/abs/2406.17115) (Jun. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17115)
  [![Star](https://img.shields.io/github/stars/HQHBench/HQHBench.svg?style=social&label=Star)](https://github.com/HQHBench/HQHBench)

+ [Does Object Grounding Really Reduce Hallucination of Large Vision-Language Models?](https://arxiv.org/abs/2406.14492v1) (Jun. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.14492v1)

+ **VGA** [VGA: Vision GUI Assistant -- Minimizing Hallucinations through Image-Centric Fine-Tuning](https://arxiv.org/abs/2406.14056) (Jun. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.14056)

+ [Do More Details Always Introduce More Hallucinations in LVLM-based Image Captioning?](https://arxiv.org/abs/2406.12663v1) (Jun. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12663v1)

+ **MFC-Bench** [MFC-Bench: Benchmarking Multimodal Fact-Checking with Large Vision-Language Models](https://arxiv.org/abs/2406.11288) (Jun. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.11288)

+ **AutoHallusion** [AUTOHALLUSION: Automatic Generation of Hallucination Benchmarks for Vision-Language Models](https://arxiv.org/abs/2406.10900v1) (Jun. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10900v1)

+ **Med-HallMark** [Detecting and Evaluating Medical Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2406.10185) (Jun. 14, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10185)

+ **MetaToken** [MetaToken: Detecting Hallucination in Image Descriptions by Meta Classification](https://arxiv.org/abs/2405.19186) (May. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.19186)

+ **THRONE** [THRONE: An Object-based Hallucination Benchmark for the Free-form Generations of Large Vision-Language Models](https://arxiv.org/abs/2405.05256) (May. 08, 2024, CVPR 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05256)

+ **VALOR-EVAL** [VALOR-EVAL: Holistic Coverage and Faithfulness Evaluation of Large Vision-Language Models](https://arxiv.org/abs/2404.13874) (Apr. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13874)
  [![Star](https://img.shields.io/github/stars/haoyiq114/VALOR.svg?style=social&label=Star)](https://github.com/haoyiq114/VALOR)

+ **ALOHa** [ALOHa: A New Measure for Hallucination in Captioning Models](https://arxiv.org/abs/2404.02904v1) (Apr. 03, 2024, NAACL 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02904v1)

+ **UPD** [Unsolvable Problem Detection: Evaluating Trustworthiness of Vision Language Models](https://arxiv.org/abs/2403.20331) (Mar. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.20331)
  [![Star](https://img.shields.io/github/stars/AtsuMiyai/UPD.svg?style=social&label=Star)](https://github.com/AtsuMiyai/UPD)

+ **IllusionVQA** [IllusionVQA: A Challenging Optical Illusion Dataset for Vision Language Models](https://arxiv.org/abs/2403.15952) (Mar. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15952)

+ **CounterAnimal** [Do CLIPs Always Generalize Better than ImageNet Models ?](https://arxiv.org/abs/2403.11497) (Mar. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.11497)

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
+ **IAVA** [Instruction-Aligned Visual Attention for Mitigating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2503.18556) (Mar. 19, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18556)

+ **MASH-VLM** [Mitigating Action-Scene Hallucination in Video-LLMs through Disentangled Spatial-Temporal Representations](https://arxiv.org/abs/2503.15871) (Mar. 20, 2025, CVPR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.15871)

+ **MFP** [Mitigating Object Hallucinations in MLLMs via Multi-Frequency Perturbations](https://arxiv.org/abs/2503.14895) (Mar. 19, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14895)

+ **ClearSight** [Visual Signal Enhancement for Object Hallucination Mitigation in Multimodal Large language Models](https://arxiv.org/abs/2503.13107) (Mar. 17, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.13107)
  [![Star](https://img.shields.io/github/stars/ustc-hyin/ClearSight.svg?style=social&label=Star)](https://github.com/ustc-hyin/ClearSight)

+ **TruthPrInt** [Mitigating LVLM Object Hallucination Via Latent Truthful-Guided Pre-Intervention](https://arxiv.org/abs/2503.10602) (Mar. 13, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10602)
  [![Star](https://img.shields.io/github/stars/jinhaoduan/TruthPrInt.svg?style=social&label=Star)](https://github.com/jinhaoduan/TruthPrInt)

+ **PM** [Through the Magnifying Glass: Adaptive Perception Magnification for Hallucination-Free VLM Decoding](https://arxiv.org/abs/2503.10183) (Mar. 13, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10183)
  [![Star](https://img.shields.io/github/stars/ShunqiM/PM.svg?style=social&label=Star)](https://github.com/ShunqiM/PM)

+ **AttnReal** [Attention Reallocation: Towards Zero-cost and Controllable Hallucination Mitigation of MLLMs](https://arxiv.org/abs/2503.08342) (Mar. 11, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.08342)

+ **AID** [Attention Hijackers: Detect and Disentangle Attention Hijacking in LVLMs for Hallucination Mitigation](https://arxiv.org/abs/2503.08216) (Mar. 11, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.08216)

+ **EAZY** [Eliminating Hallucinations in LVLMs by Zeroing out Hallucinatory Image Tokens](https://arxiv.org/abs/2503.07772) (Mar. 10, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07772)

+ **PerturboLLaVA** [Reducing Multimodal Hallucinations with Perturbative Visual Training](https://arxiv.org/abs/2503.06486) (Mar. 09, 2025, ICLR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.06486)

+ **NDE** [Treble Counterfactual VLMs: A Causal Approach to Hallucination](https://arxiv.org/abs/2503.06169) (Mar. 08, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.06169)
  [![Star](https://img.shields.io/github/stars/TREE985/Treble-Counterfactual-VLMs.svg?style=social&label=Star)](https://github.com/TREE985/Treble-Counterfactual-VLMs)

+ **TPC** [Cross-Temporal Prediction Connection for Vision-Language Model Hallucination Reduction](https://arxiv.org/abs/2503.04457) (Mar. 06, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.04457)

+ **HalCECE** [A Framework for Explainable Hallucination Detection through Conceptual Counterfactuals in Image Captioning](https://arxiv.org/abs/2503.00436) (Mar. 01, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00436)

+ **Octopus** [Alleviating Hallucination via Dynamic Contrastive Decoding](https://arxiv.org/abs/2503.00361) (Mar. 01, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00361)
  [![Star](https://img.shields.io/github/stars/LijunZhang01/Octopus.svg?style=social&label=Star)](https://github.com/LijunZhang01/Octopus)

+ **AdaVIB** [Mitigating Hallucinations in Large Vision-Language Models by Adaptively Constraining Information Flow](https://arxiv.org/abs/2502.20750) (Feb. 28, 2025, AAAI 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20750)
  [![Star](https://img.shields.io/github/stars/jiaqi5598/AdaVIB.svg?style=social&label=Star)](https://github.com/jiaqi5598/AdaVIB)

+ **FilterRAG** [Zero-Shot Informed Retrieval-Augmented Generation to Mitigate Hallucinations in VQA](https://arxiv.org/abs/2502.18536) (Feb. 25, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.18536)

+ [Exploring Causes and Mitigation of Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2502.16842) (Feb. 24, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.16842)

+ [The Role of Background Information in Reducing Object Hallucination in Vision-Language Models: Insights from Cutoff API Prompting](https://arxiv.org/abs/2502.15389) (Feb. 21, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.15389)

+ **CAP** [Mitigating Hallucinations in Multimodal Spatial Relations through Constraint-Aware Prompting](https://arxiv.org/abs/2502.08317) (Feb. 12, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08317)
  [![Star](https://img.shields.io/github/stars/jwu114/CAP.svg?style=social&label=Star)](https://github.com/jwu114/CAP)

+ **FilterRAG** [Zero-Shot Informed Retrieval-Augmented Generation to Mitigate Hallucinations in VQA](https://arxiv.org/abs/2502.18536) (Feb. 25, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.18536)

+ **DeGF** [Self-Correcting Decoding with Generative Feedback for Mitigating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2502.06130) (Feb. 10, 2025, ICLR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06130)
  [![Star](https://img.shields.io/github/stars/zhangce01/DeGF.svg?style=social&label=Star)](https://github.com/zhangce01/DeGF)

+ **VISTA** [The Hidden Life of Tokens: Reducing Hallucination of Large Vision-Language Models via Visual Information Steering](https://arxiv.org/abs/2502.03628) (Feb. 05, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.03628)
  [![Star](https://img.shields.io/github/stars/LzVv123456/VISTA.svg?style=social&label=Star)](https://github.com/LzVv123456/VISTA)

+ [Mitigating Object Hallucinations in Large Vision-Language Models via Attention Calibration](https://arxiv.org/abs/2502.01969) (Feb. 04, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01969)

+ **IFCD** [Mitigating Hallucinations in Large Vision-Language Models with Internal Fact-based Contrastive Decoding](https://arxiv.org/abs/2502.01056) (Feb. 03, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01056)

+ **MINT** [Mitigating Hallucinations in Large Vision-Language Models via Token Reduction](https://arxiv.org/abs/2502.00717) (Feb. 02, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.00717)

+ **VAP** [Poison as Cure: Visual Noise for Mitigating Object Hallucinations in LVMs](https://arxiv.org/abs/2501.19164) (Jan. 31, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.19164)
  [![Star](https://img.shields.io/github/stars/KejiaZhang-Robust/VAP.svg?style=social&label=Star)](https://github.com/KejiaZhang-Robust/VAP)

+ **PAINT** [Fixing Imbalanced Attention to Mitigate In-Context Hallucination of Large Vision-Language Model](https://arxiv.org/abs/2501.12206) (Jan. 21, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.12206)
  [![Star](https://img.shields.io/github/stars/hasanar1f/PAINT.svg?style=social&label=Star)](https://github.com/hasanar1f/PAINT)

+ [Mitigating Hallucinations on Object Attributes using Multiview Images and Negative Instructions](https://arxiv.org/abs/2501.10011) (Jan. 17, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10011)

+ **OPA-DPO** [Mitigating Hallucinations in Large Vision-Language Models via DPO: On-Policy Data Hold the Key](https://arxiv.org/abs/2501.09695) (Jan. 16, 2025, CVPR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.09695)
  [![Star](https://img.shields.io/github/stars/zhyang2226/OPA-DPO.svg?style=social&label=Star)](https://github.com/zhyang2226/OPA-DPO)

+ **VASparse** [Towards Efficient Visual Hallucination Mitigation via Visual-Aware Token Sparsification](https://arxiv.org/abs/2501.06553) (Jan. 11, 2025, CVPR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06553)
  [![Star](https://img.shields.io/github/stars/mengchuang123/VASparse-github.svg?style=social&label=Star)](https://github.com/mengchuang123/VASparse-github)

+ **EAGLE** [Enhanced Visual Grounding Minimizes Hallucinations in Instructional Multimodal Models](https://arxiv.org/abs/2501.02699) (Jan. 06, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.02699)

+ **CDAR** [Mitigating Hallucination for Large Vision Language Model by Inter-Modality Correlation Calibration Decoding](https://arxiv.org/abs/2501.01926) (Jan. 03, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01926)
  [![Star](https://img.shields.io/github/stars/lijm48/IMCCD.svg?style=social&label=Star)](https://github.com/lijm48/IMCCD)

+ **VORD** [Visual Ordinal Calibration for Mitigating Object Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2412.15739) (Dec. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15739)

+ **TPO** [Token Preference Optimization with Self-Calibrated Visual-Anchored Rewards for Hallucination Mitigation](https://arxiv.org/abs/2412.14487) (Dec. 19, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14487)

+ **Nullu** [Mitigating Object Hallucinations in Large Vision-Language Models via HalluSpace Projection](https://arxiv.org/abs/2412.13817) (Dec. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.13817)
  [![Star](https://img.shields.io/github/stars/Ziwei-Zheng/Nullu.svg?style=social&label=Star)](https://github.com/Ziwei-Zheng/Nullu)

+ **VHD** [Cracking the Code of Hallucination in LVLMs with Vision-aware Head Divergence](https://arxiv.org/abs/2412.13949v1) (Dec. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.13949v1)

+ [Combating Multimodal LLM Hallucination via Bottom-up Holistic Reasoning](https://arxiv.org/abs/2412.11124) (Dec. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11124)

+ **Verb Mirage** [Unveiling and Assessing Verb Concept Hallucinations in Multimodal Large Language Models](https://arxiv.org/abs/2412.04939) (Dec. 06, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04939)

+ **VaLiD** [Mitigating the Hallucination of Large Vision Language Models by Visual Layer Fusion Contrastive Decoding](https://arxiv.org/abs/2411.15839) (Nov. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.15839)

+ **SIG** [Looking Beyond Text: Reducing Language bias in Large Vision-Language Models via Multimodal Dual-Attention and Soft-Image Guidance](https://arxiv.org/abs/2411.14279) (Nov. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.14279)

+ **CATCH** [Complementary Adaptive Token-level Contrastive Decoding to Mitigate Hallucinations in LVLMs](https://arxiv.org/abs/2411.12713) (Nov. 19, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.12713)

+ **VIC** [Thinking Before Looking: Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination](https://arxiv.org/abs/2411.12591) (Nov. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.12591)
  [![Star](https://img.shields.io/github/stars/Terry-Xu-666/visual_inference_chain.svg?style=social&label=Star)](https://github.com/Terry-Xu-666/visual_inference_chain)

+ **EAH** [Seeing Clearly by Layer Two: Enhancing Attention Heads to Alleviate Hallucination in LVLMs](https://arxiv.org/abs/2411.09968) (Nov. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.09968)

+ **HDPO** [Mitigating Hallucination in Multimodal Large Language Model via Hallucination-targeted Direct Preference Optimization](https://arxiv.org/abs/2411.10436) (Nov. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10436)

+ **V-DPO** [Mitigating Hallucination in Large Vision Language Models via Vision-Guided Direct Preference Optimization](https://arxiv.org/abs/2411.02712) (Nov. 05, EMNLP 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.02712)
  [![Star](https://img.shields.io/github/stars/YuxiXie/V-DPO.svg?style=social&label=Star)](https://github.com/YuxiXie/V-DPO)

+ **VTI** [Reducing Hallucinations in Vision-Language Models via Latent Space Steering](https://arxiv.org/abs/2410.15778) (Oct. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15778)

+ **CCA** [Mitigating Object Hallucination via Concentric Causal Attention](https://arxiv.org/abs/2410.15926) (Oct. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15926)
  [![Star](https://img.shields.io/github/stars/xing0047/cca-llava.svg?style=social&label=Star)](https://github.com/xing0047/cca-llava)

+ **SGD** [Mitigating Hallucinations in Large Vision-Language Models via Summary-Guided Decoding](https://arxiv.org/abs/2410.13321) (Oct. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13321)

+ **MagPrompt** [Magnifier Prompt: Tackling Multimodal Hallucination via Extremely Simple Instructions](https://arxiv.org/abs/2410.11701) (Oct. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.11701)

+ **DeCo** [MLLM can see? Dynamic Correction Decoding for Hallucination Mitigation](https://www.arxiv.org/abs/2410.11779) (Oct. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2410.11779)
  [![Star](https://img.shields.io/github/stars/zjunlp/DeCo.svg?style=social&label=Star)](https://github.com/zjunlp/DeCo)

+ **NoVo** [Norm Voting off Hallucinations with Attention Heads in Large Language Models](https://arxiv.org/abs/2410.08970) (Oct. 11, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.08970)

+ **PATCH** [From Pixels to Tokens: Revisiting Object Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2410.06795) (Oct. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.06795)

+ **CausalMM** [Mitigating Modality Prior-Induced Hallucinations in Multimodal Large Language Models via Deciphering Attention Causality](https://arxiv.org/abs/2410.04780) (Oct. 07, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04780)
  [![Star](https://img.shields.io/github/stars/The-Martyr/CausalMM.svg?style=social&label=Star)](https://github.com/The-Martyr/CausalMM)

+ **DAMRO** [Dive into the Attention Mechanism of LVLM to Reduce Object Hallucination](https://arxiv.org/abs/2410.04514) (Oct. 06, EMNLP 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04514)

+ **MemVR** [Look Twice Before You Answer: Memory-Space Visual Retracing for Hallucination Mitigation in Multimodal Large Language Models](https://arxiv.org/abs/2410.03577) (Oct. 07, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03577)
  [![Star](https://img.shields.io/github/stars/1zhou-Wang/MemVR.svg?style=social&label=Star)](https://github.com/1zhou-Wang/MemVR)

+ **OHD-Caps** [Investigating and Mitigating Object Hallucinations in Pretrained Vision-Language (CLIP) Models](https://arxiv.org/abs/2410.03176v1) (Oct. 04, EMNLP 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03176v1)
  [![Star](https://img.shields.io/github/stars/Yufang-Liu/clip_hallucination.svg?style=social&label=Star)](https://github.com/Yufang-Liu/clip_hallucination)

+ **VL-Interp** [Interpreting and Editing Vision-Language Representations to Mitigate Hallucinations](https://arxiv.org/abs/2410.02762) (Oct. 03, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02762)
  [![Star](https://img.shields.io/github/stars/nickjiang2378/vl-interp.svg?style=social&label=Star)](https://github.com/nickjiang2378/vl-interp)

  
+ **HELPD** [Mitigating Hallucination of LVLMs by Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding](https://www.arxiv.org/abs/2409.20429) (Sep. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.20429)

+ **Dentist** [A Unified Hallucination Mitigation Framework for Large Vision-Language Models](https://www.arxiv.org/abs/2409.16494) (Sep. 22, TMLR, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.16494)

+ **PACU** [Effectively Enhancing Vision Language Large Models by Prompt Augmentation and Caption Utilization](https://arxiv.org/abs/2409.14484) (Sep. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.14484)

+ **RBD** [Mitigating Hallucination in Visual-Language Models via Re-Balancing Contrastive Decoding](https://arxiv.org/abs/2409.06485) (Sep. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.06485)

+ **MVP** [Look, Compare, Decide: Alleviating Hallucination in Large Vision-Language Models via Multi-View Multi-Path Reasoning](https://arxiv.org/abs/2408.17150) (Aug. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.17150)
  [![Star](https://img.shields.io/github/stars/GasolSun36/MVP.svg?style=social&label=Star)](https://github.com/GasolSun36/MVP)

+ **ConVis** [Contrastive Decoding with Hallucination Visualization for Mitigating Hallucinations in Multimodal Large Language Models](https://arxiv.org/abs/2408.13906) (Aug. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13906)
  [![Star](https://img.shields.io/github/stars/yejipark-m/ConVis.svg?style=social&label=Star)](https://github.com/yejipark-m/ConVis)

+ **CLIP-DPO** [Vision-Language Models as a Source of Preference for Fixing Hallucinations in LVLMs](https://www.arxiv.org/abs/2408.10433) (Aug. 19, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2408.10433)

+ **SID** [Self-Introspective Decoding: Alleviating Hallucinations for Large Vision-Language Models](https://www.arxiv.org/abs/2408.02032) (Aug. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2408.02032)
  [![Star](https://img.shields.io/github/stars/huofushuo/SID.svg?style=social&label=Star)](https://github.com/huofushuo/SID)

+ **ARA** [Alleviating Hallucination in Large Vision-Language Models with Active Retrieval Augmentation](https://arxiv.org/abs/2408.00555) (Aug. 01, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.00555)

+ **PAI** [Paying More Attention to Image: A Training-Free Method for Alleviating Hallucination in LVLMs](https://arxiv.org/abs/2407.21771) (Jul. 31, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21771)
  [![Star](https://img.shields.io/github/stars/LALBJ/PAI.svg?style=social&label=Star)](https://github.com/LALBJ/PAI)

+ **MAD** [Interpreting and Mitigating Hallucination in MLLMs through Multi-agent Debate](https://arxiv.org/abs/2407.20505) (Jul. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.20505)
  [![Star](https://img.shields.io/github/stars/LZzz2000/HalluciMAD.svg?style=social&label=Star)](https://github.com/LZzz2000/HalluciMAD)

+ **VACoDe** [VACoDe: Visual Augmented Contrastive Decoding](https://www.arxiv.org/abs/2408.05337) (Jul. 26, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2408.05337)

+ **REVERIE** [Reflective Instruction Tuning: Mitigating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2407.11422) (Jul. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.11422)
  [![Star](https://img.shields.io/github/stars/zjr2000/REVERIE.svg?style=social&label=Star)](https://github.com/zjr2000/REVERIE)

+ **BACON** [BACON: Supercharge Your VLM with Bag-of-Concept Graph to Mitigate Hallucinations](https://arxiv.org/abs/2407.03314) (Jul. 03, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03314)
  [![Star](https://img.shields.io/github/stars/ztyang23/BACON.svg?style=social&label=Star)](https://github.com/ztyang23/BACON)

+ **Pelican** [Pelican: Correcting Hallucination in Vision-LLMs via Claim Decomposition and Program of Thought Verification](https://arxiv.org/abs/2407.02352) (Jul. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.02352)

+ **MMHalSnowball** [Investigating and Mitigating the Multimodal Hallucination Snowballing in Large Vision-Language Models](https://www.arxiv.org/abs/2407.00569) (Jun. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2407.00569)
  [![Star](https://img.shields.io/github/stars/whongzhong/MMHalSnowball.svg?style=social&label=Star)](https://github.com/whongzhong/MMHalSnowball)

+ **AGLA** [AGLA: Mitigating Object Hallucinations in Large Vision-Language Models with Assembly of Global and Local Attention](https://arxiv.org/abs/2406.12718) (Jun. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12718)
  [![Star](https://img.shields.io/github/stars/Lackel/AGLA.svg?style=social&label=Star)](https://github.com/Lackel/AGLA)

+ **MedThink** [MedThink: Inducing Medical Large-scale Visual Language Models to Hallucinate Less by Thinking More](https://arxiv.org/abs/2406.11451) (Jun. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.11451)

+ **TUNA** [Reminding Multimodal Large Language Models of Object-aware Knowledge with Retrieved Tags](https://arxiv.org/abs/2406.10839) (Jun. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10839)

+ **CODE** [CODE: Contrasting Self-generated Description to Combat Hallucination in Large Multi-modal Models](https://arxiv.org/abs/2406.01920v1) (Jun. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01920v1)

+ **NoiseBoost** [NoiseBoost: Alleviating Hallucination with Noise Perturbation for Multimodal Large Language Models](https://arxiv.org/abs/2405.20081) (May. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20081)

+ **RITUAL** [RITUAL: Random Image Transformations as a Universal Anti-hallucination Lever in LVLMs](https://arxiv.org/abs/2405.17821) (May. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17821)
  [![Star](https://img.shields.io/github/stars/sangminwoo/RITUAL.svg?style=social&label=Star)](https://github.com/sangminwoo/RITUAL)

+ **HALVA** [Mitigating Object Hallucination via Data Augmented Contrastive Tuning](https://www.arxiv.org/abs/2405.18654) (May. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2405.18654)

+ **AvisC** [Don't Miss the Forest for the Trees: Attentional Vision Calibration for Large Vision Language Models](https://arxiv.org/abs/2405.17820) (May. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17820)
  [![Star](https://img.shields.io/github/stars/sangminwoo/AvisC.svg?style=social&label=Star)](https://github.com/sangminwoo/AvisC)

+ **RLAIF-V** [RLAIF-V: Aligning MLLMs through Open-Source AI Feedback for Super GPT-4V Trustworthiness](https://arxiv.org/abs/2405.17220) (May. 27, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17220)
  [![Star](https://img.shields.io/github/stars/RLHF-V/RLAIF-V.svg?style=social&label=Star)](https://github.com/RLHF-V/RLAIF-V)

+ **HIO** [Alleviating Hallucinations in Large Vision-Language Models through Hallucination-Induced Optimization](https://arxiv.org/abs/2405.15356v1) (May. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15356v1)

+ **VDGD** [VDGD: Mitigating LVLM Hallucinations in Cognitive Prompts by Bridging the Visual Perception Gap](https://arxiv.org/abs/2405.15683) (May. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15683)

+ **VFC** [Visual Fact Checker: Enabling High-Fidelity Detailed Caption Generation](https://arxiv.org/abs/2404.19752) (Apr. 30, 2024 (CVPR 2024))
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.19752)

+ **SoM-LLaVA** [List Items One by One: A New Data Source and Learning Paradigm for Multimodal LLMs](https://arxiv.org/abs/2404.16375) (Apr. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16375)
  [![Star](https://img.shields.io/github/stars/zzxslp/SoM-LLaVA.svg?style=social&label=Star)](https://github.com/zzxslp/SoM-LLaVA)

+ **Cantor** [Cantor: Inspiring Multimodal Chain-of-Thought of MLLM](https://arxiv.org/abs/2404.16033) (Apr. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16033)
  [![Star](https://img.shields.io/github/stars/BillChan226/HALC.svg?style=social&label=Star)](https://github.com/ggg0919/cantor)

+ **HSA-DPO** [Detecting and Mitigating Hallucination in Large Vision Language Models via Fine-Grained AI Feedback](https://arxiv.org/abs/2404.14233v1) (Apr. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.14233v1)

+ **FACT** [Fact :Teaching MLLMs with Faithful, Concise and Transferable Rationales](https://arxiv.org/abs/2404.11129) (Apr. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.11129)

+ **SeVa** [Self-Supervised Visual Preference Alignment](https://arxiv.org/abs/2404.10501) (Apr. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10501)

+ **DFTG** [Prescribing the Right Remedy: Mitigating Hallucinations in Large Vision-Language Models via Targeted Instruction Tuning](https://arxiv.org/abs/2404.10332) (Apr. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10332)

+ **FGAIF** [FGAIF: Aligning Large Vision-Language Models with Fine-grained AI Feedback](https://arxiv.org/abs/2404.05046) (Apr. 07, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05046)

+ **ICD** [Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding](https://arxiv.org/abs/2403.18715) (ACL 2024, Mar. 27, 2024)
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

+ **Silkie** [Silkie: Preference Distillation for Large Visual Language Models](https://arxiv.org/abs/2312.10665) (Dec. 17, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.10665)

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

+ **RLHF-V** [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849) (Dec. 01, 2023)
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


