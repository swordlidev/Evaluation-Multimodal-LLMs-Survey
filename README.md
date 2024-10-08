# Benchmarks of MLLMs: Survey


> **[A Survey on Benchmarks of Multimodal Large Language Models](https://arxiv.org/abs/2408.08632)**

> *<sup>1</sup>Tencent, <sup>2</sup>PKU, <sup>2</sup>NUS, <sup>2</sup>SEU, <sup>2</sup>NJU*

**⚡We will actively maintain this repository and incorporate new research as it emerges. If you have any questions, please contact swordli@tencent.com. Welcome to collaborate on academic research and writing papers together.**
## 📌 What is This Survey About?

<p align="center">
    <img src="BMLLM_statistic.png" width="100%" height="100%">
</p>


Multimodal Large Language Models (MLLMs) are gaining increasing popularity in both academia and industry due to their remarkable performance in various applications such as visual question answering, visual perception, understanding, and reasoning. Over the past few years, significant efforts have been made to examine MLLMs from multiple perspectives. This paper presents a comprehensive review of 200+ benchmarks and evaluations for MLLMs, focusing on (1)perception and understanding, (2)cognition and reasoning, (3)specific domains, (4)key capabilities, and (5)other modalities. Finally, we discuss the limitations of the current evaluation methods for MLLMs and explore promising future directions. Our key argument is that evaluation should be regarded as a crucial discipline to better support the development of MLLMs.


##  Summary of 200 MLLM Benchmarks

### Perception&Understanding
#### Comprehensive Evaluation
1. <mark>MDVP-Bench</mark> **"Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want"**. *Lin W, Wei X, An R, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2403.20271)] [[Github](https://github.com/AFeng-x/Draw-and-Understand)].
2. <mark>ChEF</mark> **"CHEF: A COMPREHENSIVE EVALUATION FRAMEWORK FOR STANDARDIZED ASSESSMENT OF MULTIMODAL LARGE LANGUAGE MODELS"**. *Shi Z, Wang Z, Fan H, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2311.02692)] [[Github](https://github.com/OpenGVLab/LAMM)].
3. <mark>UniBench</mark> **"UniBench: Visual Reasoning Requires Rethinking Vision-Language Beyond Scaling"**. *Al-Tahan H, Garrido Q, Balestriero R, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2408.04810)] [[Github](https://github.com/facebookresearch/unibench)].
4. <mark>MME</mark> **"MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models"**. *Fu C, Chen P, Shen Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2306.13394)] [[Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)].
5. <mark>MM-Vet</mark> **"MM-Vet: Evaluating Large Multimodal Models for Integrated Capabilities"**. *Yu W, Yang Z, Li L, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2308.02490)] [[Github](https://github.com/yuweihao/MM-Vet)].
6. <mark>TouchStone</mark> **"TouchStone: Evaluating Vision-Language Models by Language Models"**. *Bai S, Yang S, Bai J, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2308.16890)] [[Github](https://github.com/OFA-Sys/TouchStone)].
7. <mark>MMBench</mark> **"MMBench: Is Your Multi-modal Model an All-around Player?"**. *Liu Y, Duan H, Zhang Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2307.06281)] [[Github](https://github.com/open-compass/VLMEvalKit)].
8. <mark>OwlEval</mark> **"mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality"**. *Ye Q, Xu H, Xu G, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2304.14178)] [[Github](https://github.com/X-PLUG/mPLUG-Owl)].
9. <mark>Open-VQA</mark> **"What Matters in Training a GPT4-Style Language Model with Multimodal Inputs?"**. *Zeng Y, Zhang H, Zheng J, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2307.02469)] [[Github](https://lynx-llm.github.io/)].
10. <mark>SEED-Bench</mark> **"SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension"**. *Li B, Wang R, Wang G, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2307.16125)] [[Github](https://github.com/AILab-CVC/SEED-Bench)].
11. <mark>SEED-Bench-2</mark> **"SEED-Bench-2: Benchmarking Multimodal Large Language Models"**. *Li B, Ge Y, Ge Y, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2311.17092)] [[Github](https://github.com/AILab-CVC/SEED-Bench)].
12. <mark>LLaVA-Bench</mark> **"Visual Instruction Tuning"**. *Liu H, Li C, Wu Q, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2304.08485)] [[Github](https://llava-vl.github.io/)].
13. <mark>LAMM</mark> **"LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark"**. *Yin Z, Wang J, Cao J, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2306.06687)] [[Github](https://github.com/OpenGVLab/LAMM)].

#### Fine-grained Perception
**Visual Grounding and Object Detection**
1. <mark>CODE</mark> **"Contextual Object Detection with Multimodal Large Language Models"**. *Zang Y, Li W, Han J, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2305.18279)] [[Github](https://github.com/yuhangzang/ContextDET)].
2. <mark>Flickr30k Entities</mark> **"Flickr30k Entities: Collecting Region-to-Phrase Correspondences for Richer Image-to-Sentence Models"**. *Plummer B. A, Wang L, Cervantes C. M, et al.*. arXiv 2016. [[Paper](https://arxiv.org/abs/1505.04870)] [[Github](https://github.com/BryanPlummer/flickr30k_entities)].
3. <mark>Visual7W</mark> **"Visual7W: Grounded Question Answering in Images"**. *Zhu Y, Groth O, Bernstein M, et al.*. CVPR 2016. [[Paper](https://arxiv.org/abs/1511.03416)] [[Github](https://github.com/yukezhu/visual7w-toolkit)].
4. <mark>V*Bench</mark> **"V\*: Guided Visual Search as a Core Mechanism in Multimodal LLMs"**. *Wu P, Xie S, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2312.14135)] [[Github](https://github.com/penghao-wu/vstar)].
5. <mark>Grounding-Bench</mark> **"LLaVA-Grounding: Grounded Visual Chat with Large Multimodal Models"**. *Zhang H, Li H, Li F, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2312.02949)] [[Github](https://github.com/UX-Decoder/LLaVA-Grounding)].
   
**Fine-grained Identification and Recognition**
1. <mark>GVT-Bench</mark> **"What Makes for Good Visual Tokenizers for Large Language Models?"**. *Wang G, Ge Y,Ding X, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2305.12223)] [[Github](https://github.com/TencentARC/GVT)].
2. <mark>V* Bench</mark> **"V\*: Guided Visual Search as a Core Mechanism in Multimodal LLMs"**. *Wu P, Xie S.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2312.14135)] [[Github](https://github.com/penghao-wu/vstar)].
3. <mark>MMVP</mark> **"Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs"**. *Tong S,Liu Z,Zhai Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.06209)] [[Github](https://tsb0601.github.io/mmvp_blog/)].
4. <mark>CV-Bench</mark> **"Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs"**. *Tong S,Brown E,Wu P, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.16860)] [[Github](https://cambrian-mllm.github.io/)].
5. <mark>P2GB</mark> **"Plug-and-Play Grounding of Reasoning in Multimodal Large Language Models"**. *Chen J, Liu Y, Li D, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.19322)] [[Github]()].
7. <mark>Visual CoT</mark> **"Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning"**. *Shao H, Qian S, Xiao H, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.16999)] [[Github](https://github.com/deepcs233/Visual-CoT)].
8. <mark>MagnifierBench</mark> **"OtterHD: A High-Resolution Multi-modality Model"**. *Li B, Zhang  P, Yang J, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2311.04219)] [[Github](https://github.com/Luodian/Otter)].
9. <mark>HR-Bench</mark> **"Divide, Conquer and Combine: A Training-Free Framework for High-Resolution Image Perception in Multimodal Large Language Models"**. *Wang W, Ding L,Zeng  M, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.15556)] [[Github](https://github.com/DreamMr/HR-Bench)].
10. <mark>SPARK</mark> **"SPARK: Multi-Vision Sensor Perception and Reasoning Benchmark for Large-scale Vision-Language Models"**. *Yu Y,Chung  S,Lee  B, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.12114)] [[Github](https://github.com/top-yun/SPARK)].


**Nuanced Vision-language Alignment**
1. <mark>Eqben</mark> **"Equivariant Similarity for Vision-Language Foundation Models"**. *Wang T, Lin, K. Li L,Lin C, et al.*. ICCV 2023. [[Paper](https://arxiv.org/abs/2303.14465)] [[Github](https://github.com/Wangt-CN/EqBen)].
2. <mark>SPEC</mark> **"Asclepius: A Spectrum Evaluation Benchmark for Medical Multi-Modal Large Language Models"**. *Wang W, Su Y, Huan Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.11217)] [[Github](https://asclepius-med.github.io/)].
3. <mark>VALSE</mark> **"When and why vision-language models behave like bags-of-words, and what to do about it?"**. *Yuksekgonul M, Bianchi F, Kalluri P, et al.*. ICLR 2023. [[Paper](https://arxiv.org/abs/2210.01936)] [[Github]()].
4. <mark>VL-Checklist</mark> **"VL-CheckList: Evaluating Pre-trained Vision-Language Models with Objects, Attributes and Relations"**. *Zhao T, Zhang T, Zhu M, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2207.00221)] [[Github](https://github.com/om-ai-lab/VL-CheckList)].
5. <mark>Winoground</mark> **"Winoground: Probing Vision and Language Models for Visio-Linguistic Compositionality"**. *Thrush T, Jiang R, Bartolo M, et al.*. CVPR 2022. [[Paper](https://arxiv.org/abs/2204.03162)] [[Github](https://huggingface.co/datasets/facebook/winoground)].
6. <mark>ARO</mark> **"When and why vision-language models behave like bags-of-words, and what to do about it?"**. *Yuksekgonul M, Bianchi F, Kalluri P, et al.*. ICLR 2023. [[Paper](https://arxiv.org/abs/2210.01936)] [[Github]()].

#### Image Understanding
**Multi-image Understanding**
1. <mark>Mementos</mark> **"Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences"**. *Wang X, Zhou Y, Liu X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.10529)] [[Github](https://github.com/umd-huang-lab/Mementos)].
2. <mark>MileBench</mark> **"MileBench: Benchmarking MLLMs in Long Context"**. *Song D, Chen S, Chen G, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.18532)] [[Github](https://milebench.github.io/)].
3. <mark>MuirBench</mark> **"MuirBench: A Comprehensive Benchmark for Robust Multi-image Understanding"**. *Wang F, Fu X, Huang J, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.09411)] [[Github](https://muirbench.github.io/)].
4. <mark>CompBench</mark> **"CompBench: A Comparative Reasoning Benchmark for Multimodal LLMs"**. *Kil J, Mai Z, Lee J, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2407.16837)] [[Github](https://compbench.github.io/)].
5. <mark>MMIU</mark> **"MMIU: Multimodal Multi-image Understanding for Evaluating Large Vision-Language Models"**. *Meng F, Wang J, Li C, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.02718)] [[Github](https://mmiu-bench.github.io/)].

**Implication Understanding**
1. <mark>II-Bench</mark> **"II-Bench: An Image Implication Understanding Benchmark for Multimodal Large Language Models"**. *Liu Z, Fang F, Feng X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.05862)] [[Github](https://huggingface.co/datasets/m-a-p/II-Bench)].
2. <mark>ImplicitAVE</mark> **"ImplicitAVE: An Open-Source Dataset and Multimodal LLMs Benchmark for Implicit Attribute Value Extraction"**. *Zou H, Samuel V, Zhou Y, et al.*. ACL 2024. [[Paper](https://arxiv.org/abs/2404.15592)] [[Github](https://github.com/HenryPengZou/ImplicitAVE)].
3. <mark>FABA-Bench</mark> **"Facial Affective Behavior Analysis with Instruction Tuning"**. *Li Y, Dao A, Bao W, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.05052)] [[Github](https://johnx69.github.io/FABA/)].

**Image Quality and Aesthetics Perception**
1. <mark>AesBench</mark> **"AesBench: An Expert Benchmark for Multimodal Large Language Models on Image Aesthetics Perception"**. *Huang Y, Yuan Q, Sheng X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.08276)] [[Github](https://github.com/yipoh/AesBench)].
2. <mark>UNIAA</mark> **"UNIAA: A Unified Multi-modal Image Aesthetic Assessment Baseline and Benchmark"**. *Zhou Z, Wang Q, Lin B, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.09619)] [[Github](https://github.com/KwaiVGI/Uniaa)].
3. <mark>DesignProbe</mark> **"DesignProbe: A Graphic Design Benchmark for Multimodal Large Language Models"**. *Lin J, Huang D, Zhao T, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.14801)] [[Github]()].
4. <mark>Q-Bench</mark> **"Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-level Vision"**. *Wu H, Zhang Z, Zhang E, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2309.14181)] [[Github](https://q-future.github.io/Q-Bench/)].
5. <mark>Q-Bench+</mark> **"A Benchmark for Multi-modal Foundation Models on Low-level Vision: from Single Images to Pairs"**. *Zhang Z, Wu H, Zhang E, et al.*. TPAMI. [[Paper](https://arxiv.org/abs/2402.07116)] [[Github](https://github.com/Q-Future/Q-Bench)].
   

### Cognition&Reasoning
#### General Reasoning
**Visual Relation**
1. <mark>MMRel</mark> **"MMRel: A Relation Understanding Dataset and Benchmark in the MLLM Era"**. *Nie J, Zhang G, An W, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.09121)] [[Github](https://github.com/niejiahao1998/MMRel)].
2. <mark>What’sUp</mark> **"What's "up" with vision-language models? Investigating their struggle with spatial reasoning"**. *Kamath A, Hessel J, Chang K*. EMNLP 2023. [[Paper](https://arxiv.org/abs/2310.19785)] [[Github](https://github.com/amitakamath/whatsup_vlms)].
3. <mark>GSR-BENCH</mark> **"GSR-BENCH: A Benchmark for Grounded Spatial Reasoning Evaluation via Multimodal LLMs"**. *Rajabi N, Kosecka J*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.13246)] [[Github]()].
4. <mark>CRPE</mark> **"The All-Seeing Project V2: Towards General Relation Comprehension of the Open World"**. *Wang W, Ren Y, Luo H, et al.*. ECCV 2024. [[Paper](https://arxiv.org/abs/2402.19474)] [[Github](https://github.com/OpenGVLab/all-seeing)].
5. <mark>VSR</mark> **"Visual Spatial Reasoning"**. *Liu F, Emerson G, Collier N, et al.*. arXiv 2022. [[Paper](https://arxiv.org/abs/2205.00363)] [[Github](https://github.com/cambridgeltl/visual-spatial-reasoning)].
6. <mark>SpatialRGPT</mark> **"SpatialRGPT: Grounded Spatial Reasoning in Vision Language Model"**. *Cheng A, Yin H, Fu Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.01584)] [[Github](https://www.anjiecheng.me/SpatialRGPT)].
7. <mark>MuCR</mark> **"Multimodal Causal Reasoning Benchmark: Challenging Vision Large Language Models to Infer Causal Links Between Siamese Images"**. *Li Z, Wang H, Liu D, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.08105)] [[Github](https://github.com/Zhiyuan-Li-John/MuCR)].

**Context-dependent Reasoning**
1. <mark>CODIS</mark> **"CODIS: Benchmarking Context-Dependent Visual Comprehension for Multimodal Large Language Models"**. *Luo F, Chen C, Wan Z, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.13607)] [[Github](https://thunlp-mt.github.io/CODIS/)].
2. <mark>CFMM</mark> **"Eyes Can Deceive: Benchmarking Counterfactual Reasoning Abilities of Multi-modal Large Language Models"**. *Li Y, Tian W, Jiao Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.12966)] [[Github]()].
3. <mark>VL-ICLBench</mark> **"VL-ICL Bench: The Devil in the Details of Benchmarking Multimodal In-Context Learning"**. *Zong Y, Bohdal O, Hospedales T, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2403.13164)] [[Github](https://github.com/ys-zong/VL-ICL)].

**CoT Reasoning**
1. <mark>SCIENCEQA</mark> **"Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering"**. *Lu P, Mishra S, Xia T, et al.*. NIPS 2022. [[Paper](https://arxiv.org/abs/2209.09513)] [[Github](https://scienceqa.github.io/)].
2. <mark>VisualCoT</mark> **"Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning"**. *Shao H, Qian S, Xiao H, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.16999)] [[Github](https://github.com/deepcs233/Visual-CoT)].
3. <mark>M3CoT</mark> **"M3CoT: A Novel Benchmark for Multi-Domain Multi-step Multi-modal Chain-of-Thought"**. *Chen Q, Qin L, Zhang J, et al.*. ACL2024. [[Paper](https://arxiv.org/abs/2405.16473)] [[Github](https://github.com/LightChen233/M3CoT)].

**Vision-Indispensable Capabilities**
1. <mark>CLEVR</mark> **"CLEVR: A Diagnostic Dataset for Compositional Language and Elementary Visual Reasoning"**. *Johnson J, Hariharan B, Maaten L, et al.*. arXiv 2016. [[Paper](https://arxiv.org/abs/1612.06890)] [[Github](https://github.com/elinorp-d/clevr)].
2. <mark>VQAv2</mark> **"Visually Dehallucinative Instruction Generation: Know What You Don't Know"**. *Cha S, Lee J, Lee Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.09717)] [[Github](https://github.com/ncsoft/idk)].
3. <mark>GQA</mark> **"GQA: A New Dataset for Real-World Visual Reasoning and Compositional Question Answering"**. *Hudson D, Manning C*. CVPR 2019. [[Paper](https://arxiv.org/abs/1902.09506)] [[Github]()].
4. <mark>MMStar</mark> **"Are We on the Right Way for Evaluating Large Vision-Language Models?"**. *Chen L, Li J, Dong X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.20330)] [[Github](https://mmstar-benchmark.github.io/)].

#### Knowledge-based Reasoning
**Knowledge-based Visual Question Answering**
1. <mark>KB-VQA</mark> **"Explicit Knowledge-based Reasoning for Visual Question Answering"**. *Wang P, Wu Q, Shen C, et al.*. arXiv 2015. [[Paper](https://arxiv.org/abs/1511.02570)] [[Github]()].
2. <mark>FVQA</mark> **"FVQA: Fact-based Visual Question Answering"**. *Wang P, Wu Q, Shen C, et al.*. arXiv 2016. [[Paper](https://arxiv.org/abs/1606.05433)] [[Github](https://github.com/wangpengnorman/FVQA)].
3. <mark>OK-VQA</mark> **"OK-VQA: A Visual Question Answering Benchmark Requiring External Knowledge"**. *Marino K, Rastegari M, Farhadi A, et al.*. CVPR 2019. [[Paper](https://arxiv.org/abs/1906.00067)] [[Github](https://okvqa.allenai.org/)].
4. <mark>A-OKVQA</mark> **"A-OKVQA: A Benchmark for Visual Question Answering using World Knowledge"**. *Schwenk D, Khandelwal A, Clark C, et al.*. arXiv 2022. [[Paper](https://arxiv.org/abs/2206.01718)] [[Github](https://github.com/allenai/aokvqa)].
5. <mark>SOK-Bench</mark> **"SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge"**. *Wang A, Wu B, Chen S, et al.*. CVPR 2024. [[Paper](https://arxiv.org/abs/2405.09713)] [[Github](https://bobbywu.com/SOKBench/)].

**Knowledge Editing**
1. <mark>MMEdit</mark> **"Can We Edit Multimodal Large Language Models?"**. *Cheng S, Tian B, Liu Q, et al.*. EMNLP 2023. [[Paper](https://arxiv.org/abs/2310.08475)] [[Github](https://github.com/zjunlp/EasyEdit)].
2. <mark>MIKE</mark> **"MIKE: A New Benchmark for Fine-grained Multimodal Entity Knowledge Editing"**. *Li J, Du M, Zhang C, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.14835)] [[Github]()].
3. <mark>VLKEB</mark> **"VLKEB: A Large Vision-Language Model Knowledge Editing Benchmark"**. *Huang H, Zhong H, Yu T, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.07350)] [[Github](https://github.com/VLKEB/VLKEB)].
4. <mark>MC-MKE</mark> **"MC-MKE: A Fine-Grained Multimodal Knowledge Editing Benchmark Emphasizing Modality Consistency"**. *Zhang J, Zhang H, Yin X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.13219)] [[Github]()].


#### Intelligence&Cognition
**Intelligent Question Answering**
1. <mark>RAVEN</mark> **"RAVEN: A Dataset for Relational and Analogical Visual rEasoNing"**. *Zhang C, Gao F, Jia B, et al.*. CVPR 2019. [[Paper](https://arxiv.org/abs/1903.02741)] [[Github](https://wellyzhang.github.io/project/raven.html)].
2. <mark>MARVEL</mark> **"MARVEL: Multidimensional Abstraction and Reasoning through Visual Evaluation and Learning"**. *Jiang Y, Zhang J, Sun K, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.13591)] [[Github](https://github.com/1171-jpg/MARVEL_AVR)].
3. <mark>VCog-Bench</mark> **"What is the Visual Cognition Gap between Humans and Multimodal LLMs?"**. *Cao X, Lai B, Ye W, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.10424)] [[Github](https://github.com/IrohXu/VCog-Bench)].
4. <mark>M3GIA</mark> **"M3GIA: A Cognition Inspired Multilingual and Multimodal General Intelligence Ability Benchmark"**. *Song W, Li Y, Xu J, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.05343)] [[Github]()].


**Mathematical Question Answering**
1. <mark>MathVista</mark> **"MathVista: Evaluating Mathematical Reasoning of Foundation Models in Visual Contexts"**. *Lu P, Bansal H, Xia T, et al.*. ICLR 2024. [[Paper](https://arxiv.org/abs/2310.02255)] [[Github](https://mathvista.github.io/)].
2. <mark>MathVerse</mark> **"MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual Math Problems?"**. *ZhangR, JiangD, ZhangY, et al.*. ECCV 2024. [[Paper](https://arxiv.org/abs/2403.14624)] [[Github](https://mathverse-cuhk.github.io/)].
3. <mark>NPHardEval4V</mark> **"NPHardEval4V: A Dynamic Reasoning Benchmark of Multimodal Large Language Models"**. *FanL, HuaW, LiX, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.01777)] [[Github](https://github.com/lizhouf/NPHardEval4V)].
4. <mark>Math-Vision</mark> **"Measuring Multimodal Mathematical Reasoning with MATH-Vision Dataset"**. *WangK, PanJ, ShiW, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.14804)] [[Github](https://mathvision-cuhk.github.io/)].
5. <mark>MATHCHECK-GEO</mark> **"Is Your Model Really A Good Math Reasoner? Evaluating Mathematical Reasoning with Checklist"**. *ZhouZ, LiuS, NingM, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2407.08733)] [[Github](https://mathcheck.github.io/)].
6. <mark>Geometry3K</mark> **"Inter-GPS: Interpretable Geometry Problem Solving with Formal Language and Symbolic Reasoning"**. *LuP, GongR, JiangS, et al.*. ACL 2021. [[Paper](https://arxiv.org/abs/2105.04165)] [[Github](https://lupantech.github.io/inter-gps/)].

**Multidisciplinary Question Answering**
1. <mark>M3Exam</mark> **"M3Exam: A Multilingual, Multimodal, Multilevel Benchmark for Examining Large Language Models"**. *ZhangW, AljuniedS, GaoC, et al.*. NeurIPS 2023. [[Paper](https://arxiv.org/abs/2306.05179)] [[Github](https://github.com/DAMO-NLP-SG/M3Exam)].
2. <mark>CMMMU</mark> **"CMMMU: A Chinese Massive Multi-discipline Multimodal Understanding Benchmark"**. *ZhangG, DuX, ChenB, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.11944)] [[Github](https://cmmmu-benchmark.github.io/)].
3. <mark>ScienceQA</mark> **"Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering"**. *LuP, MishraS, XiaT, et al.*. NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.09513)] [[Github](https://scienceqa.github.io/)].
4. <mark>MMMU</mark> **"MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI"**. *YueX, NiY, ZhangK, et al.*. CVPR 2024. [[Paper](https://arxiv.org/abs/2311.16502)] [[Github](https://mmmu-benchmark.github.io/)].
5. <mark>CMMU</mark> **"CMMU: A Benchmark for Chinese Multi-modal Multi-type Question Understanding and Reasoning"**. *HeZ, WuX, ZhouP, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.14011)] [[Github](https://github.com/FlagOpen/CMMU)].
6. <mark>SceMQA</mark> **"SceMQA: A Scientific College Entrance Level Multimodal Question Answering Benchmark"**. *LiangZ, GuoK, LiuG, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.05138)] [[Github](https://scemqa.github.io/)].
7. <mark>MULTI</mark> **"MULTI: Multimodal Understanding Leaderboard with Text and Images"**. *ZhuZ, XuY, ChenL, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.03173)] [[Github](https://opendfm.github.io/MULTI-Benchmark/)].
   

### Specific Domains
#### Text-rich VQA
**Text-oriented Question Answering**
1. <mark>OCRBench</mark> **"On the Hidden Mystery of OCR in Large Multimodal Models"**. *LiuY, LiZ, HuangM, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2305.07895)] [[Github](https://github.com/Yuliang-Liu/MultimodalOCR)].
2. <mark>P2GB</mark> **"Plug-and-Play Grounding of Reasoning in Multimodal Large Language Models"**. *ChenJ, LiuY, LiD, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.19322)] [[Github]()].
3. <mark>TextVQA</mark> **"Towards VQA Models That Can Read"**. *SinghA, NatarajanV, ShahM, et al.*. CVPR 2019. [[Paper](https://arxiv.org/abs/1904.08920)] [[Github](https://textvqa.org/)].
4. <mark>TextCaps</mark> **"TextCaps: a Dataset for Image Captioning with Reading Comprehension"**. *SidorovO, HuR, RohrbachM, et al.*. ECCV 2020. [[Paper](https://arxiv.org/abs/2003.12462)] [[Github](https://textvqa.org/textcaps/)].
5. <mark>SEED-Bench-2-Plus</mark> **"SEED-Bench-2-Plus: Benchmarking Multimodal Large Language Models with Text-Rich Visual Comprehension"**. *Bohao Li, Yuying Ge, Yi Chen, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.16790)] [[Github](https://github.com/AILab-CVC/SEED-Bench)].
   
**Document-oriented Question Answering**
1. <mark>SPDocVQA</mark> **"Document Visual Question Answering Challenge 2020"**. *Minesh Mathew, Ruben Tito, Dimosthenis Karatzas, et al.*. DAS 2020. [[Paper](https://arxiv.org/abs/2008.08899)] [[Github]()].
2. <mark>MPDocVQA</mark> **"Hierarchical multimodal transformers for Multi-Page DocVQA"**. *Rubèn Tito, Dimosthenis Karatzas, Ernest Valveny*. arXiv 2022. [[Paper](https://arxiv.org/abs/2212.05935)] [[Github](https://github.com/rubenpt91/MP-DocVQA-Framework)].
3. <mark>InfographicVQA</mark> **"Minesh Mathew and Viraj Bagal and Rubèn Pérez Tito and Dimosthenis Karatzas and Ernest Valveny and C. V Jawahar"**. *Minesh Mathew, Viraj Bagal, Rubèn Pérez Tito, et al.*. arXiv 2021. [[Paper](https://arxiv.org/abs/2104.12756)] [[Github](https://www.docvqa.org/)].
4. <mark>DUDE</mark> **"Document Understanding Dataset and Evaluation (DUDE)"**. *Jordy Van Landeghem, Rubén Tito, Łukasz Borchmann, et al.*. ICCV 2023. [[Paper](https://arxiv.org/abs/2305.08455)] [[Github](huggingface.co/datasets/jordyvl/DUDE_loader)].
5. <mark>MM-NIAH</mark> **"Needle In A Multimodal Haystack"**. *Weiyun Wang, Shuibo Zhang, Yiming Ren, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.07230)] [[Github](https://github.com/OpenGVLab/MM-NIAH)].

**Chart-oriented Question Answering**
1. <mark>ChartQA</mark> **"ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning"**. *Ahmed Masry, Do Xuan Long, Jia Qing Tan, et al.*. ACL 2022. [[Paper](https://arxiv.org/abs/2203.10244)] [[Github]()].
2. <mark>ChartX</mark> **"ChartX and ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning"**. *Renqiu Xia, Bo Zhang, Hancheng Ye, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.12185)] [[Github](https://github.com/UniModal4Reasoning/ChartVLM)].
3. <mark>ChartBench</mark> **"ChartBench: A Benchmark for Complex Visual Reasoning in Charts"**. *Zhengzhuo Xu, Sinan Du, Yiyan Qi, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2312.15915)] [[Github](https://chartbench.github.io/)].
4. <mark>SciGraphQA</mark> **"SciGraphQA: A Large-Scale Synthetic Multi-Turn Question-Answering Dataset for Scientific Graphs"**. *Shengzhi Li, Nima Tajbakhsh*. arXiv 2023. [[Paper](https://arxiv.org/abs/2308.03349)] [[Github](https://github.com/findalexli/SciGraphQA)].
5. <mark>MMC-Benchmark</mark> **"MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning"**. *Fuxiao Liu, Xiaoyang Wang, Wenlin Yao, et al.*. NAACL 2024. [[Paper](https://arxiv.org/abs/2311.10774)] [[Github](https://github.com/FuxiaoLiu/MMC)].
6. <mark>CharXiv</mark> **"CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs"**. *Zirui Wang, Mengzhou Xia, Luxi He, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.18521)] [[Github](https://charxiv.github.io/)].
7. <mark>CHOPINLLM</mark> **"On Pre-training of Multimodal Language Models Customized for Chart Understanding"**. *Wan-Cyuan Fan, Yen-Chun Chen, Mengchen Liu, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2407.14506)] [[Github]()].
8. <mark>SciFIBench</mark> **"SciFIBench: Benchmarking Large Multimodal Models for Scientific Figure Interpretation"**. *Jonathan Roberts, Kai Han, Neil Houlsby, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2405.08807)] [[Github](https://github.com/jonathan-roberts1/SciFIBench)].

**Html-oriented Question Answering**
1. <mark>Web2Code</mark> **"Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs"**. *Sukmin Yun, Haokun Lin, Rusiru Thushara, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.20098)] [[Github](https://mbzuai-llm.github.io/webpage2code/)].
2. <mark>VisualWebBench</mark> **"VisualWebBench: How Far Have Multimodal LLMs Evolved in Web Page Understanding and Grounding?"**. *Junpeng Liu, Yifan Song, Bill Yuchen Lin, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.05955)] [[Github](https://github.com/VisualWebBench/VisualWebBench)].
3. <mark>Plot2Code</mark> **"Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots"**. *Chengyue Wu, Yixiao Ge, Qiushan Guo, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2405.07990)] [[Github](https://huggingface.co/datasets/TencentARC/Plot2Code)].

#### Decision-making Agents
**Embodied Decision-making**
1. <mark>VisualAgentBench</mark> **"VisualAgentBench: Towards Large Multimodal Models as Visual Foundation Agents"**. *Xiao Liu, Tianjie Zhang, Yu Gu, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.06327)] [[Github](https://github.com/THUDM/VisualAgentBench)].
2. <mark>EgoPlan-Bench</mark> **"EgoPlan-Bench: Benchmarking Multimodal Large Language Models for Human-Level Planning"**. *Yi Chen, Yuying Ge, Yixiao Ge, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2312.06722)] [[Github](https://github.com/ChenYi99/EgoPlan)].
3. <mark>PCA-EVAL</mark> **"Towards End-to-End Embodied Decision Making via Multi-modal Large Language Model: Explorations with GPT4-Vision and Beyond"**. *Liang Chen, Yichi Zhang, Shuhuai Ren, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2310.02071)] [[Github](https://github.com/pkunlp-icler/PCA-EVAL/)].
4. <mark>OpenEQA</mark> **"OpenEQA: Embodied Question Answering in the Era of Foundation Models"**. *Majumdar, Arjun and Ajay, Anurag and Zhang, et al.*. CVPR 2024. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper.pdf)] [[Github](https://open-eqa.github.io/)].
   
**Mobile Agency**
1. <mark>Mobile-Eval</mark> **"Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception"**. *Junyang Wang, Haiyang Xu, Jiabo Ye, et al.*. ICLR 2024. [[Paper](https://arxiv.org/abs/2401.16158)] [[Github](https://github.com/X-PLUG/MobileAgent)].
2. <mark>Fereet-UI</mark> **"Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs"**. *You K, Zhang H, Schoop E, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2404.05719)] [[Github](https://github.com/apple/ml-ferret)].
3. <mark>CRAB</mark> **"CRAB: Cross-environment Agent Benchmark for Multimodal Language Model Agents"**. *Tianqi Xu, Linyao Chen, Dai-Jie Wu, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2407.01511)] [[Github](https://github.com/camel-ai/crab)].
   
#### Diverse Cultures&Languages
1. <mark>CMMU</mark> **"CMMU: A Benchmark for Chinese Multi-modal Multi-type Question Understanding and Reasoning"**. *Zheqi He, Xinya Wu, Pengfei Zhou, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.14011)] [[Github](https://github.com/flageval-baai/CMMU)].
2. <mark>Henna</mark> **"Peacock: A Family of Arabic Multimodal Large Language Models and Benchmarks"**. *Fakhraddin Alwajih, El Moatez Billah Nagoudi, Gagan Bhatia, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2403.01031)] [[Github](https://github.com/UBC-NLP/peacock)].
3. <mark>LaVy-Bench</mark> **"LaVy: Vietnamese Multimodal Large Language Model"**. *Chi Tran, Huong Le Thanh*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.07922)] [[Github](https://github.com/baochi0212/LaVy)].
4. <mark>MTVQA</mark> **"MTVQA: Benchmarking Multilingual Text-Centric Visual Question Answering"**. *Jingqun Tang, Qi Liu, Yongjie Ye, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2405.11985)] [[Github](https://bytedance.github.io/MTVQA/)].
5. <mark>CVQA</mark> **"CVQA: Culturally-diverse Multilingual Visual Question Answering Benchmark"**. *David Romero, Chenyang Lyu, Haryo Akbarianto Wibowo, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.05967)] [[Github](https://cvqa-benchmark.org/)].
6. <mark>CMMMU</mark> **"CMMMU: A Chinese Massive Multi-discipline Multimodal Understanding Benchmark"**. *Ge Zhang, Xinrun Du, Bei Chen, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.11944)] [[Github](https://github.com/CMMMU-Benchmark/CMMMU)].
7. <mark>MULTI</mark> **"MULTI: Multimodal Understanding Leaderboard with Text and Images"**. *Zichen Zhu, Yang Xu, Lu Chen, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.03173)] [[Github](https://opendfm.github.io/MULTI-Benchmark/)].

#### Other Applications
**Geography and Remote Sensing**
1. <mark>LHRS-Bench</mark> **"LHRS-Bot: Empowering Remote Sensing with VGI-Enhanced Large Multimodal Language Model"**. *Dilxat Muhtar, Zhenshi Li, Feng Gu, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.02544)] [[Github](https://github.com/NJU-LHRS/LHRS-Bot)].
2. <mark>ChartingNewTerritories</mark> **"Charting New Territories: Exploring the Geographic and Geospatial Capabilities of Multimodal LLMs"**. *Jonathan Roberts, Timo Lüddecke, Rehan Sheikh, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2311.14656)] [[Github](https://github.com/jonathan-roberts1/charting-new-territories)].
   
**Medicine**
1. <mark>GMAI-MMBench</mark> **"GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI"**. *Pengcheng Chen, Jin Ye, Guoan Wang, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.03361)] [[Github](https://github.com/uni-medical/GMAI-MMBench)].
2. <mark>M3D</mark> **"M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts"**. *Mingsheng Li, Xin Chen, Chi Zhang, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2312.10763)] [[Github](https://github.com/OpenM3D/M3DBench)].
3. <mark>Asclepius</mark> **"Asclepius: A Spectrum Evaluation Benchmark for Medical Multi-Modal Large Language Models"**. *Wenxuan Wang, Yihang Su, Jingyuan Huan, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2402.11217)] [[Github](https://asclepius-med.github.io/)].
4. <mark>MultiMed</mark> **"MultiMed: Massively Multimodal and Multitask Medical Understanding"**. *Shentong Mo, Paul Pu Liang*. arXiv 2024. [[Paper](https://arxiv.org/abs/2408.12682)] [[Github]()].
   
**Society**
1. <mark>VizWiz</mark> **"VizWiz Grand Challenge: Answering Visual Questions from Blind People"**. *Danna Gurari, Qing Li, Abigale J. Stangl, et al.*. arXiv 2018. [[Paper](https://arxiv.org/abs/1802.08218)] [[Github](https://github.com/DenisDsh/VizWiz-VQA-PyTorch)].
2. <mark>MM-Soc</mark> **"MM-Soc: Benchmarking Multimodal Large Language Models in Social Media Platforms"**. *Yiqiao Jin, Minje Choi, Gaurav Verma, et al.*. ACL 2024. [[Paper](https://arxiv.org/abs/2402.14154)] [[Github](https://github.com/claws-lab/MMSoc)].
3. <mark>TransportationGames</mark> **"TransportationGames: Benchmarking Transportation Knowledge of (Multimodal) Large Language Models"**. *Xue Zhang, Xiangyu Shi, Xinyue Lou, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2401.04471)] [[Github](https://github.com/sxysxy/Transportation.Games)].
   
**Industry**
1. <mark>MMRo</mark> **"MMRo: Are Multimodal LLMs Eligible as the Brain for In-Home Robotics?"**. *Jinming Li, Yichen Zhu, Zhiyuan Xu, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.19693)] [[Github]()].
2. <mark>DesignQA</mark> **"DesignQA: A Multimodal Benchmark for Evaluating Large Language Models' Understanding of Engineering Documentation"**. *Anna C. Doris, Daniele Grandi, Ryan Tomich, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2404.07917)] [[Github](https://github.com/anniedoris/design_qa)].
   
**Autonomous Driving**
1. <mark>NuScenes-QA</mark> **"NuScenes-QA: A Multi-modal Visual Question Answering Benchmark for Autonomous Driving Scenario"**. *Tianwen Qian, Jingjing Chen, Linhai Zhuo, et al.*. AAAI 2024. [[Paper](https://arxiv.org/abs/2305.14836)] [[Github](https://github.com/qiantianwen/NuScenes-QA)].
2. <mark>DriveLM-DATA</mark> **"DriveLM: Driving with Graph Visual Question Answering"**. *Chonghao Sima, Katrin Renz, Kashyap Chitta, et al.*. ECCV 2024. [[Paper](https://arxiv.org/abs/2312.14150)] [[Github](https://github.com/OpenDriveLab/DriveLM)].

### Key Capabilities
#### Conversation Abilities
**Long-context**
1. <mark>Mile-Bench</mark> **"MileBench: Benchmarking MLLMs in Long Context"**. *Song D, Chen S, Chen G H, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2404.18532)] [[Github](https://milebench.github.io/)].
2. <mark>MMNeedle</mark> **"Multimodal Needle in a Haystack: Benchmarking Long-Context Capability of Multimodal Large Language Models"**. *Wang H, Shi H, Tan S, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.11230)] [[Github](https://github.com/Wang-ML-Lab/multimodal-needle-in-a-haystack)].
3. <mark>MLVU</mark> **"MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding"**. *Zhou J, Shu Y, Zhao B, et al.*. arXiv 2024. [[Paper](https://arxiv.org/abs/2406.04264)] [[Github](https://github.com/JUNJIE99/MLVU)].
   
**Instruction Following**
1. <mark>CoIN</mark> **"CoIN: A Benchmark of Continual Instruction tuNing for Multimodel Large Language Model"**. *Chen C, Zhu J, Luo X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2403.08350)] [[Github](https://github.com/zackschen/CoIN)].
2. <mark>MIA-Bench</mark> **"MIA-Bench: Towards Better Instruction Following Evaluation of Multimodal LLMs"**. *Qian Y, Ye H, Fauconnier J P, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2407.01509)] [[Github](https://github.com/apple/ml-mia-bench)].
3. <mark>DEMON</mark> **"Fine-tuning Multimodal LLMs to Follow Zero-shot Demonstrative Instructions"**. *Li J, Pan K, Ge Z, et al.*. ICLR 2023. [[Paper](https://arxiv.org/pdf/2308.04152)] [[Github](https://github.com/DCDmllm/Cheetah)].
4. <mark>VisIT-Bench</mark> **"VisIT-Bench: A Benchmark for Vision-Language Instruction Following Inspired by Real-World Use"**. *Bitton Y, Bansal H, Hessel J, et al.*. NeurIPS 2023. [[Paper](https://arxiv.org/pdf/2308.06595)] [[Github](https://visit-bench.github.io/)].

#### Hallucination
1. <mark>POPE</mark> **"Evaluating Object Hallucination in Large Vision-Language Models"**. *Li Y, Du Y, Zhou K, et al.*. EMNLP 2023. [[Paper](https://arxiv.org/pdf/2305.10355)] [[Github](https://github.com/RUCAIBox/POPE)].
2. <mark>GAVIE</mark> **"Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning"**. *Liu F, Lin K, Li L, et al.*. ICLR 2023. [[Paper](https://www.researchgate.net/profile/Fuxiao-Liu-2/publication/375596083_Mitigating_Hallucination_in_Large_Multi-Modal_Models_via_Robust_Instruction_Tuning/links/655188b0b1398a779d7f4a04/Mitigating-Hallucination-in-Large-Multi-Modal-Models-via-Robust-Instruction-Tuning.pdf)] [[Github](https://fuxiaoliu.github.io/LRV/)].
3. <mark>HaELM</mark> **"Evaluation and Analysis of Hallucination in Large Vision-Language Models"**. *Wang J, Zhou Y, Xu G, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2308.15126)] [[Github](https://github.com/junyangwang0410/HaELM)].
4. <mark>M-HalDetect</mark> **"Detecting and Preventing Hallucinations in Large Vision Language Models"**. *Gunjal A, Yin J, Bas E.*. AAAI 2024. [[Paper](https://arxiv.org/pdf/2308.06394)] [[Github](https://github.com/hendryx-scale/mhal-detect)].
5. <mark>Bingo</mark> **"Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges"**. *Cui C, Zhou Y, Yang X, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2311.03287)] [[Github](https://github.com/gzcch/Bingo)].
6. <mark>HallusionBench</mark> **"HALLUSIONBENCH: An Advanced Diagnostic Suite for Entangled Language Hallucination and Visual Illusion in Large Vision-Language Models"**. *Guan T, Liu F, Wu X, et al.*. CVPR 2024. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Guan_HallusionBench_An_Advanced_Diagnostic_Suite_for_Entangled_Language_Hallucination_and_CVPR_2024_paper.pdf)] [[Github](https://github.com/tianyi-lab/HallusionBench)].
7. <mark>VHTest</mark> **"Visual Hallucinations of Multi-modal Large Language Models"**. *Huang W, Liu H, Guo M, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.14683)] [[Github](https://github.com/wenhuang2000/VHTest)].
8. <mark>CorrelationQA</mark> **"The Instinctive Bias: Spurious Images lead to Hallucination in MLLMs"**. *Han T, Lian Q, Pan R, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.03757)] [[Github](https://github.com/MasaiahHan/CorrelationQA)].
9. <mark>CHAIR</mark> **"Object Hallucination in Image Captioning"**. *Rohrbach A, Hendricks L A, Burns K, et al.*. EMNLP 2018. [[Paper](https://arxiv.org/pdf/1809.02156)] [[Github](https://github.com/LisaAnne/Hallucination)].
10. <mark>MHaluBench</mark> **"Unified Hallucination Detection for Multimodal Large Language Models"**. *Chen X, Wang C, Xue Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.03190)] [[Github](https://github.com/zjunlp/EasyDetect)].
11. <mark>VideoHallucer</mark> **"VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models"**. *Wang Y, Wang Y, Zhao D, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.16338)] [[Github](https://videohallucer.github.io/)].
12. <mark>MMHAL-BENCH</mark> **"Aligning Large Multimodal Models with Factually Augmented RLHF"**. *Sun Z, Shen S, Cao S, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2309.14525)] [[Github](https://llava-rlhf.github.io/)].
13. <mark>AMBER</mark> **"AMBER: An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation"**. *Wang J, Wang Y, Xu G, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2311.07397)] [[Github](https://github.com/junyangwang0410/AMBER)].
14. <mark>MMECeption</mark> **"GenCeption: Evaluate Multimodal LLMs with Unlabeled Unimodal Data"**. *Cao L, Buchner V, Senane Z, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.14973)] [[Github](https://github.com/llcresearch/GenCeption)].


   
#### Trustworthiness
**Robustness**
1. <mark>MAD-Bench</mark> **"How Easy is It to Fool Your Multimodal LLMs? An Empirical Analysis on Deceptive Prompts"**. *Qian Y, Zhang H, Yang Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.13220)] [[Github]()].
2. <mark>MMR</mark> **"Seeing Clearly, Answering Incorrectly: A Multimodal Robustness Benchmark for Evaluating MLLMs on Leading Questions"**. *Liu Y, Liang Z, Wang Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.10638)] [[Github](https://github.com/BAAI-DCAI/Multimodal-Robustness-Benchmark)].
3. <mark>MM-SpuBench</mark> **"MM-SpuBench: Towards Better Understanding of Spurious Biases in Multimodal LLMs"**. *Ye W, Zheng G, Ma Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.17126)] [[Github](https://huggingface.co/datasets/mmbench/MM-SpuBench)].
4. <mark>MM-SAP</mark> **"MM-SAP: A Comprehensive Benchmark for Assessing Self-Awareness of Multimodal Large Language Models in Perception"**. *Wang Y, Liao Y, Liu H, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2401.07529)] [[Github](https://github.com/YHWmz/MM-SAP)].
5. <mark>BenchLMM</mark> **"BenchLMM: Benchmarking Cross-style Visual Capability of Large Multimodal Models"**. *Cai R, Song Z, Guan D, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2312.02896)] [[Github](https://github.com/AIFEG/BenchLMM)].
6. <mark>VQAv2-IDK</mark> **"Visually Dehallucinative Instruction Generation: Know What You Don’t Know"**. *Cha S, Lee J, Lee Y, et al.*. ICASSP 2024. [[Paper](https://arxiv.org/pdf/2402.09717)] [[Github](https://github.com/ncsoft/idk)].
7. 
**Safety**
1. <mark>MMUBench</mark> **"Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models"**. *Li J, Wei Q, Zhang C, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2405.12523)] [[Github]()].
2. <mark>JailBreakV-28K</mark> **"JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks"**. *Luo W, Ma S, Liu X, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2404.03027)] [[Github](https://eddyluo1232.github.io/JailBreakV28K/)].
3. <mark>MultiTrust</mark> **"Benchmarking Trustworthiness of Multimodal Large Language Models: A Comprehensive Study"**. *Zhang Y, Huang Y, Sun Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.07057)] [[Github](https://multi-trust.github.io/)].
4. <mark>MM-SafetyBench</mark> **"MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models"**. *Liu X, Zhu Y, Gu J, et al.*. ECCV 2024. [[Paper](https://arxiv.org/pdf/2311.17600)] [[Github](https://github.com/isXinLiu/MM-SafetyBench)].
5. <mark>SHIELD</mark> **"SHIELD: An Evaluation Benchmark for Face Spoofing and Forgery Detection with Multimodal Large Language Models"**. *Shi Y, Gao Y, Lai Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.04178)] [[Github](https://github.com/laiyingxin2/SHIELD)].
6. <mark>RTVLM</mark> **"Red teaming visual language models"**. *Li M, Li L, Yin Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2401.12915)] [[Github](https://huggingface.co/datasets/MMInstruction/RedTeamingVLM)].

### Other Modalities
#### Videos
**Temporal Perception**
1. <mark>MVBench</mark> **"MVBench: A Comprehensive Multi-modal Video Understanding Benchmark"**. *Li K, Wang Y, He Y, et al.*. CVPR 2024. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_MVBench_A_Comprehensive_Multi-modal_Video_Understanding_Benchmark_CVPR_2024_paper.pdf)] [[Github](https://github.com/OpenGVLab/Ask-Anything)].
2. <mark>TimeIT</mark> **"Timechat: A time-sensitive multimodal large language model for long video understanding"**. *Ren S, Yao L, Li S, et al.*. CVPR 2024. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Ren_TimeChat_A_Time-sensitive_Multimodal_Large_Language_Model_for_Long_Video_CVPR_2024_paper.pdf)] [[Github](https://github.com/RenShuhuai-Andy/TimeChat)].
3. <mark>ViLMA</mark> **"ViLMA: A Zero-Shot Benchmark for Linguistic and Temporal Grounding in Video-Language Models"**. *Kesen I, Pedrotti A, Dogan M, et al.*. ICLR 2024. [[Paper](https://arxiv.org/pdf/2311.07022)] [[Github](https://cyberiada.github.io/ViLMA/)].
4. <mark>VITATECS</mark> **"VITATECS: A Diagnostic Dataset for Temporal Concept Understanding of Video-Language Models"**. *Li S, Li L, Ren S, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2311.17404)] [[Github](https://github.com/lscpku/VITATECS)].
5. <mark>TempCompass</mark> **"TempCompass: Do Video LLMs Really Understand Videos?"**. *Liu Y, Li S, Liu Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2403.00476)] [[Github](https://github.com/llyx97/TempCompass)].
6. <mark>OSCaR</mark> **"OSCaR: Object State Captioning and State Change Representation"**. *Nguyen N, Bi J, Vosoughi A, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.17128)] [[Github](https://github.com/nguyennm1024/OSCaR)].
7. <mark>ADLMCQ</mark> **"LLAVIDAL: Benchmarking Large Language Vision Models for Daily Activities of Living"**. *Chakraborty R, Sinha A, Reilly D, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.09390)] [[Github](https://github.com/ADL-X/LLAVIDAL)].
8. <mark>Perception Test</mark> **"Perception Test: A Diagnostic Benchmark for Multimodal Video Models"**. *Patraucean V, Smaira L, Gupta A, et al.*. NeurIPS2024. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/8540fba4abdc7f9f7a7b1cc6cd60e409-Paper-Datasets_and_Benchmarks.pdf)] [[Github](https://github.com/google-deepmind/perception_test)].

**Long Video Understanding**
1. <mark>MovieChat-1k</mark> **"Moviechat: From dense token to sparse memory for long video understanding"**. **. . [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Song_MovieChat_From_Dense_Token_to_Sparse_Memory_for_Long_Video_CVPR_2024_paper.pdf)] [[Github](https://github.com/rese1f/MovieChat)].
2. <mark>EgoSchema</mark> **"EgoSchema: A Diagnostic Benchmark for Very Long-form Video Language Understanding"**. **. . [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/90ce332aff156b910b002ce4e6880dec-Paper-Datasets_and_Benchmarks.pdf)] [[Github](https://egoschema.github.io/)].
3. <mark>Event-Bench</mark> **"Towards Event-oriented Long Video Understanding"**. **. . [[Paper](https://arxiv.org/pdf/2406.14129)] [[Github](https://github.com/RUCAIBox/Event-Bench)].
4. <mark>MLVU</mark> **"MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding"**. **. . [[Paper](https://arxiv.org/abs/2406.04264)] [[Github](https://github.com/JUNJIE99/MLVU)].

**Comprehensive Evaluation**
1. <mark>Video-Bench</mark> **"Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating Video-based Large Language Models"**. *Ning M, Zhu B, Xie Y, et al.*. arXiv 2023. [[Paper](https://arxiv.org/abs/2311.16103)] [[Github](https://github.com/PKU-YuanGroup/Video-Bench)].
2. <mark>MMBench-Video</mark> **"MMBench-Video: A Long-Form Multi-Shot Benchmark for Holistic Video Understanding"**. *Fang X, Mao K, Duan H, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.14515)] [[Github](https://github.com/open-compass/VLMEvalKit)].
3. <mark>Video-MME</mark> **"Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis"**. *Fu C, Dai Y, Luo Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2405.21075)] [[Github](https://video-mme.github.io/)].
4. <mark>AutoEval-Video</mark> **"AutoEval-Video: An Automatic Benchmark for Assessing Large Vision Language Models in Open-Ended Video Question Answering"**. *Chen X, Lin Y, Zhang Y, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2311.14906)] [[Github](https://github.com/Xiuyuan-Chen/AutoEval-Video)].
5. <mark>MMWorld</mark> **"MMWorld: Towards Multi-discipline Multi-faceted World Model Evaluation in Videos"**. *He X, Feng W, Zheng K, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.08407)] [[Github](https://mmworld-bench.github.io/)].
6. <mark>WorldNet</mark> **"WorldGPT: Empowering LLM as Multimodal World Model"**. *Ge Z, Huang H, Zhou M, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2404.18202)] [[Github](https://github.com/DCDmllm/WorldGPT)].


#### Audio
1. <mark>Dynamic-SUPERB</mark> **"Dynamic-superb: Towards a dynamic, collaborative, and comprehensive instruction-tuning benchmark for speech"**. *Huang C, Lu K H, Wang S H, et al.*. ICASSP 2024. [[Paper](https://arxiv.org/pdf/2309.09510)] [[Github](https://github.com/dynamic-superb/dynamic-superb)].
2. <mark>MuChoMusic</mark> **"MuChoMusic: Evaluating Music Understanding in Multimodal Audio-Language Models"**. *Weck B, Manco I, Benetos E, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2408.01337)] [[Github](https://mulab-mir.github.io/muchomusic/)].
3. <mark>AIR-Bench</mark> **"AIR-Bench: Benchmarking Large Audio-Language Models via Generative Comprehension"**. *Yang Q, Xu J, Liu W, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.07729)] [[Github](https://github.com/OFA-Sys/AIR-Bench)].

#### 3D Points
1. <mark>ScanQA</mark> **"ScanQA: 3D Question Answering for Spatial Scene Understanding"**. *Azuma D, Miyanishi T, Kurita S, et al.*. CVPR 2022. [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Azuma_ScanQA_3D_Question_Answering_for_Spatial_Scene_Understanding_CVPR_2022_paper.pdf)] [[Github](https://github.com/ATR-DBI/ScanQA)].
2. <mark>ScanReason</mark> **"ScanReason: Empowering 3D Visual Grounding with Reasoning Capabilities"**. *Zhu C, Wang T, Zhang W, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2407.01525)] [[Github](https://zcmax.github.io/projects/ScanReason/)].
3. <mark>LAMM</mark> **"LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark"**. *Yin Z, Wang J, Cao J, et al.*. NeurIPS 2024. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/548a41b9cac6f50dccf7e63e9e1b1b9b-Paper-Datasets_and_Benchmarks.pdf)] [[Github](https://openlamm.github.io/)].
4. <mark>SpatialRGPT</mark> **"SpatialRGPT: Grounded Spatial Reasoning in Vision Language Model"**. *Cheng A C, Yin H, Fu Y, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2406.01584)] [[Github](https://www.anjiecheng.me/SpatialRGPT)].
5. <mark>M3DBench</mark> **"M3DBench: Let’s Instruct Large Models with Multi-modal 3D Prompts"**. *Li M, Chen X, Zhang C, et al.*. arXiv 2023. [[Paper](https://arxiv.org/pdf/2312.10763)] [[Github](https://github.com/OpenM3D/M3DBench/)].
   
#### Omni-modal
1. <mark>MCUB</mark> **"Model Composition for Multimodal Large Language Models"**. *Chen C, Du Y, Fang Z, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2402.12750)] [[Github](https://github.com/THUNLP-MT/ModelCompose)].
2. <mark>AVQA</mark> **"AVQA: A Dataset for Audio-Visual Question Answering on Videos"**. *Yang P, Wang X, Duan X, et al.*. MM 2022. [[paper](https://dl.acm.org/doi/pdf/10.1145/3503161.3548291)] [[Github](https://mn.cs.tsinghua.edu.cn/avqa/)].
3. <mark>MusicAVQA</mark> **"Learning to Answer Questions in Dynamic Audio-Visual Scenarios"**. *Li G, Wei Y, Tian Y, et al.*. CVPR 2022. [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Learning_To_Answer_Questions_in_Dynamic_Audio-Visual_Scenarios_CVPR_2022_paper.pdf)] [[Github](https://gewu-lab.github.io/MUSIC-AVQA/)].
4. <mark>MMT-Bench</mark> **"MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI"**. *Ying K, Meng F, Wang J, et al.*. arXiv 2024. [[paper](https://arxiv.org/pdf/2404.16006)] [[Github](https://github.com/OpenGVLab/MMT-Bench)].
