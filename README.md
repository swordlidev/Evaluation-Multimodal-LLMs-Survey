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
**Comprehensive Evaluation**
1. **"Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want"**. *Lin W, Wei X, An R, et al.*. arXiv 2024. [[Paper](https://arxiv.org/pdf/2403.20271)] [[Github](https://github.com/AFeng-x/Draw-and-Understand)].
2. **"CHEF: A COMPREHENSIVE EVALUATION FRAMEWORK FOR STANDARDIZED ASSESSMENT OF MULTIMODAL LARGE LANGUAGE MODELS"**. *Shi Z, Wang Z, Fan H, et al*. arXiv 2023. [[paper](https://arxiv.org/pdf/2311.02692)] [[Github](https://github.com/OpenGVLab/LAMM)].
   
**Fine-grained Perception**
**Image Understanding**

### Cognition&Reasoning
**General Reasoning**
**Knowledge-based Reasoning**
**Intelligence&Cognition**

### Specific Domains
**Text-rich VQA**
**Decision-making Agents**
**Diverse Cultures&Languages**
**Other Applications**
**Long-context**
1. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
2. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
3. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
4. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
5. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
6. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
7. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
8. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
**Instruction Following**
1. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
2. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
3. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
4. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
5. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
6. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
7. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].
8. <mark></mark> **""**. **. . [[Paper]()] [[Github]()].

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
