# LLM-Hallucination-Papers
**Keyword for search:**  
- hallucination - hallu  
- factuality - factu  
- knowledge - knowle

## Contents
- 2024
  - [Other-2024](#other-2024)
  - [EMNLP-202411](#emnlp-202411)
  - [ACL-202408](#acl-202408)
  - [NAACL-202406](#naacl-202406)
  - [NeurIPS-202412](#neurips-202412)
  - [COLM-202410](#colm-202410)
  - [ICML-202407](#icml-202407)
  - [ICLR-202405](#iclr-202405)
- 2023
  - [EMNLP-202312](#emnlp-202312)
  - [ACL-202307](#acl-202307)


##  Other 2024
- Does Fine-Tuning LLMs on New Knowledge Encourage Hallucinations? [[pdf]](https://arxiv.org/abs/2405.05904)  
(在新knowledge上fine-tuning具有风险，会增加模型的Hallucination，可能为当前项目提供论据)
- Evaluating Image Hallucination in Text-to-Image Generation with Question-Answering [[pdf]](https://arxiv.org/abs/2409.12784)  
(提出dataset，采用VQA来衡量text-to-image产生图片的真实性。Image hallucination (text-to-image过程中产生的幻觉)看起来是比较新的领域，可在该领域酝酿idea)
-  Alleviating Hallucinations of Large Language Models through Induced Hallucinations [[pdf]](https://arxiv.org/abs/2312.15710)  
(Tencent AI，使用了TruthfulQA和FActScore，TruthfulQA只评估了MC任务，FActScore使用默认retrieval+ChatGPT)
- Unfamiliar Finetuning Examples Control How Language Models Hallucinate [[pdf]](https://arxiv.org/abs/2403.05612)  
(UC Berkeley+Google，**使用了FActScore**，使用默认的retrieval+ChatGPT，指出FActScore代码需要一点修改)
[Top](#llm-hallucination-papers)

##  EMNLP 202411
#### Hallucination & Factuality
1. EFUF: Efficient Fine-Grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models [[pdf]](https://aclanthology.org/2024.emnlp-main.67/)  
(NJU, Mitigate object hallucination in MLLMs, Gradient ascent by designing losses)
2. Lookback Lens: Detecting and Mitigating Contextual Hallucinations in Large Language Models Using Only Attention Maps [[pdf]](https://aclanthology.org/2024.emnlp-main.84/)  
(⭐️MIT, Detect consistent hallucination, Model's attention on provided context vs its own generations)
3. HELPD: Mitigating Hallucination of  LVLMs by Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding [[pdf]](https://aclanthology.org/2024.emnlp-main.105/)  
(NUAA, Mitigate object hallucination in VLMs, Feedback, Penalty decoding)
4. Embedding and Gradient Say Wrong: A White-Box Method for Hallucination Detection [[pdf]](https://aclanthology.org/2024.emnlp-main.116/)  
(ZJU, Detect hallucination in LLMs, Embedding and gradient information, plug-and-play, sota)
5. Knowledge Verification to Nip Hallucination in the Bud [[pdf]](https://aclanthology.org/2024.emnlp-main.152/)  
(SunU, Mitigate hallucination in LLMs, Reduce knowledge inconsistency between external knowledge & foundation LLM)
6. Whispers that Shake Foundations: Analyzing and Mitigating False Premise Hallucinations in Large Language Models [[pdf]](https://aclanthology.org/2024.emnlp-main.155/)  
(⭐️CAS, Analysis & Mitigate False Premise Hallucinations in LLMs)
7. Does Object Grounding Really Reduce Hallucination of Large Vision-Language Models? [[pdf]](https://aclanthology.org/2024.emnlp-main.159/)  
(⭐️WüNLP, Systematic analysis, Effect of object grounding on LVLM hallucination)
8. An Audit on the Perspectives and Challenges of Hallucinations in  NLP [[pdf]](https://aclanthology.org/2024.emnlp-main.375/)  
(⭐️PennsylvaniaSU, Survey, Definition of hallucination)
9. Knowledge-Centric Hallucination Detection [[pdf]](https://aclanthology.org/2024.emnlp-main.395/)  
 (Shanghai AI Lab, Detect hallucination, Split model's response into claim-triplets, different with FActScore)
10. DAMRO: Dive into the Attention Mechanism of  LVLM  to Reduce Object Hallucination [[pdf]](https://aclanthology.org/2024.emnlp-main.439/)  
(TongjiU, Reduce object hallucination in VLMs, Attention distribution, Filter out high-attention outlier tokens)
11. Does Fine-Tuning  LLMs on New Knowledge Encourage Hallucinations? [[pdf]](https://aclanthology.org/2024.emnlp-main.444/)  
(IIT+Google, Study the effect of new knowledge during fine-tuning on the model's hallucination)
12. Pelican: Correcting Hallucination in Vision-LLMs via Claim Decomposition and Program of Thought Verification [[pdf]](https://aclanthology.org/2024.emnlp-main.470/)  
(SRI Inc. Detect and mitigate hallucinations in VLMs, Claim decomposition, Verification)
13. ToolBeHonest: A Multi-level Hallucination Diagnostic Benchmark for Tool-Augmented Large Language Models [[pdf]](https://aclanthology.org/2024.emnlp-main.637/)  
(WasedaU, Hallucination benchmark for Tool-augmented LLM)
14. Null-Shot Prompting: Rethinking Prompting Large Language Models With Hallucination [[pdf]](https://aclanthology.org/2024.emnlp-main.740/)  
(⭐️RitsumeikanU, Hallucination in prompt, Enhance LLM's performance)
15. Small Agent Can Also Rock! Empowering Small Language Models as Hallucination Detector [[pdf]](https://aclanthology.org/2024.emnlp-main.809/)  
(RUC, Detect hallucination in LLM, HaluAgent, Combining hallucination & Agent)
16. HalluMeasure: Fine-grained Hallucination Measurement Using Chain-of-Thought Reasoning [[pdf]](https://aclanthology.org/2024.emnlp-main.837/)  
(Amazon, Detect hallucination in LLM's responses, Decompose claims, Check atomic claims using CoT reasoning)
17. Game on Tree: Visual Hallucination Mitigation via Coarse-to-Fine View Tree and Game Theory [[pdf]](https://aclanthology.org/2024.emnlp-main.998/)  
(PKU, Mitigate hallucination in VLM, New decoding strategy)
18. Investigating and Mitigating Object Hallucinations in Pretrained Vision-Language (CLIP) Models [[pdf]](https://aclanthology.org/2024.emnlp-main.1016/)  
(⭐️ECNU, Investigate hallucination in CLIP, Which part does the hallucination come from, **Inspiration for LLaVA's hallucination?**)
19. Enhanced Hallucination Detection in Neural Machine Translation through Simple Detector Aggregation [[pdf]](https://aclanthology.org/2024.emnlp-main.1033/)  
(Paris-SaclayU, Detect hallucination in machine translation)
20. Mitigating Open-Vocabulary Caption Hallucinations [[pdf]](https://aclanthology.org/2024.emnlp-main.1263/)  
(Tel-AvivU, Mitigate hallucination in image captioning)
21. VGA: Vision  GUI  Assistant - Minimizing Hallucinations through Image-Centric Fine-Tuning [[pdf]](https://aclanthology.org/2024.findings-emnlp.68/)  
(ECNU, Reduce hallucination in GPU understanding task, VQA dataset, Fune-tuning)
22. Zero-Resource Hallucination Prevention for Large Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.204/)  
(⭐️PSU, Detect hallucination before generation, Evaluate model's familiarity with the concepts in prompts)
23. Reference-free Hallucination Detection for Large Vision-Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.262/)  
(⭐️MBZUAI, Detect hallucination in VLM, reference-free, little summary)
24. FaithScore: Fine-grained Evaluations of Hallucinations in Large Vision-Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.290/)  
(UoTD, Detect hallucination in VLM, Evaluation metric, Multimodal version of FActScore)
25. Mitigating Hallucinations of Large Language Models in Medical Information Extraction via Contrastive Decoding [[pdf]](https://aclanthology.org/2024.findings-emnlp.456/)  
(USTC, Mitigate hallucination in Medical information extraction, Contrastive Decoding, )
26. Multilingual Fine-Grained News Headline Hallucination Detection [[pdf]](https://aclanthology.org/2024.findings-emnlp.461/)  
(Google, News headline hallucination detection, Dataset, Multilingual)
27. Mechanistic Understanding and Mitigation of Language Model Non-Factual Hallucinations [[pdf]](https://aclanthology.org/2024.findings-emnlp.466/)  
(UoT, Explore mechanistic causes of hallucinations, Dataset, Mitigate hallucination)
28. AutoHallusion: Automatic Generation of Hallucination Benchmarks for Vision-Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.493/)  
(UoMaryland, Benchmark for VLM, Automated benchmark generation approach)
29. DiaHalu: A Dialogue-level Hallucination Evaluation Benchmark for Large Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.529/)  
(ECNU, Benchmark, Dialogue)
30. Machine Translation Hallucination Detection for Low and High Resource Languages using Large Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.564/)  
(UCL, Detect hallucination in MT, LLMs have good performance even without training)
31. Navigating Hallucinations for Reasoning of Unintentional Activities [[pdf]](https://aclanthology.org/2024.findings-emnlp.565/)  
(IIT India, New task: understanding unintentional human activities, Hallucinated reasoning, New prompting)
32. What if...?: Thinking Counterfactual Keywords Helps to Mitigate Hallucination in Large Multi-modal Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.626/)  
(KAIST, Mitigate hallu in VLM, Counterfactual prompt, Counterfactual keywords gen)
33. A Comprehensive Survey of Hallucination in Large Language, Image, Video and Audio Foundation Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.685/)  
(IIT India, Survey, Foundation model, Language+image+video+audio)
34. Pre-trained Language Models Return Distinguishable Probability Distributions to Unfaithfully Hallucinated Texts [[pdf]](https://aclanthology.org/2024.findings-emnlp.738/)  
(KoreaU, PLM return distinguishable probability distributions for hallu)
35. V-DPO: Mitigating Hallucination in Large Vision Language Models via Vision-Guided Direct Preference Optimization [[pdf]](https://aclanthology.org/2024.findings-emnlp.775/)  
(NUS, Mitigate hallu in VLM, Mitigate over-reliance on backbone, Preference learning)
36. Mitigating Hallucination in Fictional Character Role-Play [[pdf]](https://aclanthology.org/2024.findings-emnlp.846/)  
(UC San Diego, Evaluate & mitigate of hallu in fictional character role-play, Dataset)
37. CED: Comparing Embedding Differences for Detecting Out-of-Distribution and Hallucinated Text [[pdf]](https://aclanthology.org/2024.findings-emnlp.874/)  
(YonseiU, OOD detection)
38. RULE: Reliable Multimodal  RAG  for Factuality in Medical Vision Language Models [[pdf]](https://aclanthology.org/2024.emnlp-main.62/)  
(UNC-Chapel Hill, New method, Multimodal RAG, Factuality of Medical VLM)
39. Unveiling Factual Recall Behaviors of Large Language Models through Knowledge Neurons [[pdf]](https://aclanthology.org/2024.emnlp-main.420/)  
(⭐️⭐️CAS, Factual knowledge recall, Reasoning, Knowledge Neuron)
40. The Factuality Tax of Diversity-Intervened Text-to-Image Generation: Benchmark and Fact-Augmented Intervention [[pdf]](https://aclanthology.org/2024.emnlp-main.513/)  
(⭐️⭐️UCLA, Benchmark, T2I model, trade-off between diversity interventions and factuality)
41. Detecting Errors through Ensembling Prompts (DEEP): An End-to-End  LLM  Framework for Detecting Factual Errors [[pdf]](https://aclanthology.org/2024.emnlp-main.728/)  
(UTA, Detect factual errors in summarization, Ensembling prompts, without fine-tuning)
42. Temporally Consistent Factuality Probing for Large Language Models [[pdf]](https://aclanthology.org/2024.emnlp-main.887/)  
(IIT-India, Consistent Factuality Probing, Temporal)
43. FAME: Towards Factual Multi-Task Model Editing [[pdf]](https://aclanthology.org/2024.emnlp-main.894/)  
(⭐️BIT, Dataset, Model editing, Method)
44. Factuality of Large Language Models: A Survey [[pdf]](https://aclanthology.org/2024.emnlp-main.1088/)  
(⭐️MBZUAI, Survey, Compare several surveys about Factuality)
45. SYNFAC-EDIT: Synthetic Imitation Edit Feedback for Factual Alignment in Clinical Summarization [[pdf]](https://aclanthology.org/2024.emnlp-main.1120/)  
(UoMassachusetts, Factual alignment, Clinical summarization, GPT4 offer feedback)
46. OpenFactCheck: A Unified Framework for Factuality Evaluation of  LLMs [[pdf]](https://aclanthology.org/2024.emnlp-demo.23/)  
(MBZUAI, Framework for factuality evaluation)
47. SummaCoz: A Dataset for Improving the Interpretability of Factual Consistency Detection for Summarization [[pdf]](https://aclanthology.org/2024.findings-emnlp.210/)  
(IowaStateU, Interpretability, Factual consistency, Summarization, Dataset)
48. MoleculeQA: A Dataset to Evaluate Factual Accuracy in Molecular Comprehension [[pdf]](https://aclanthology.org/2024.findings-emnlp.216/)  
(THU, Molecule research, Factual, Dataset)
49. VeriScore: Evaluating the factuality of verifiable claims in long-form text generation [[pdf]](https://aclanthology.org/2024.findings-emnlp.552/)  
(UMass Amherst, Based on FActScore, Not every claim is verifiable, Benchmark)
50. Improving Factual Consistency of News Summarization by Contrastive Preference Optimization [[pdf]](https://aclanthology.org/2024.findings-emnlp.648/)  
(SCUT, News summarization, Factual consistency)
51. MAVEN-FACT: A Large-scale Event Factuality Detection Dataset [[pdf]](https://aclanthology.org/2024.findings-emnlp.651/)  
(HKUST, Event Factuality Detection)
52. SAFARI: Cross-lingual Bias and Factuality Detection in News Media and News Articles [[pdf]](https://aclanthology.org/2024.findings-emnlp.712/)  
(MZUAI, Bias and factuality detection, News media)  
53. FactAlign: Long-form Factuality Alignment of Large Language Models [[pdf]](https://aclanthology.org/2024.findings-emnlp.955/)  
(NTU, Factuality alignment, New method)
54. Dial  BeInfo for Faithfulness: Improving Factuality of Information-Seeking Dialogue via Behavioural Fine-Tuning [[pdf]](https://aclanthology.org/2024.findings-emnlp.998/)  
(PolyAI-London, Improving factuality by fine-tuning)  
[Top](#llm-hallucination-papers)


##  ACL 202408
#### Hallucination & Factuality
- Self-Alignment for Factuality: Mitigating Hallucinations in  LLMs via Self-Evaluation [[pdf]](https://aclanthology.org/2024.acl-long.107/)  
(CUHK，减轻模型幻觉，使用了TruthfulQA数据集，没提供代码)
- Unified Hallucination Detection for Multimodal Large Language Models [[pdf]](https://aclanthology.org/2024.acl-long.178/)  
(ZJU，多模态大模型幻觉Detection，提出数据集)
- Don’t Hallucinate, Abstain: Identifying LLM Knowledge Gaps via Multi-LLM Collaboration [[pdf]](https://aclanthology.org/2024.acl-long.786/)  
(UoW，前面遗漏的文章，提到了LLM幻觉和知识)
- UHGEval: Benchmarking the Hallucination of  Chinese Large Language Models via Unconstrained Generation [[pdf]](https://aclanthology.org/2024.acl-long.288/)  
(RUC，评估LLM幻觉，提出无限制生成数据集)
- ANAH: Analytical Annotation of Hallucinations in Large Language Models [[pdf]](https://aclanthology.org/2024.acl-long.442/)  
(HKUST，Measuring LLM幻觉，提出数据集)
- TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space [[pdf]](https://aclanthology.org/2024.acl-long.483/)  
(CAS，减轻幻觉，通过对特征进行映射，编辑等，**使用了TruthfulQA，完整保留了TruthfulQA代码，评估了生成generation任务和多选MC任务**)
- InterrogateLLM: Zero-Resource Hallucination Detection in  LLM-Generated Answers [[pdf]](https://aclanthology.org/2024.acl-long.506/)  
(Microsoft，Detecting 幻觉 in LLMs)
- RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models [[pdf]](https://aclanthology.org/2024.acl-long.585/)  
(UIUC，measure 幻觉 in RAG-based LLM)
- The Dawn After the Dark: An Empirical Study on Factuality Hallucination in Large Language Models  [[pdf]](https://aclanthology.org/2024.acl-long.586/)  
(RUC，提出HaluEval 2.0，测试了一系列用于减轻幻觉的技术)
- Less is More: Mitigating Multimodal Hallucination from an  EOS  Decision Perspective  [[pdf]](https://aclanthology.org/2024.acl-long.633/)  
(RUC，减轻LVLM幻觉)
- Investigating and Mitigating the Multimodal Hallucination Snowballing in Large Vision-Language Models  [[pdf]](https://aclanthology.org/2024.acl-long.648/)  
(HIT，发现LVLM的幻觉会越积累越多，减轻方法)
- VisDiaHalBench: A Visual Dialogue Benchmark For Diagnosing Hallucination in Large Vision-Language Models  [[pdf]](https://aclanthology.org/2024.acl-long.658/)  
(SYU，measure LVLM的幻觉，提出数据集)
- Analyzing  LLM  Behavior in Dialogue Summarization: Unveiling Circumstantial Hallucination Trends  [[pdf]](https://aclanthology.org/2024.acl-long.677/)  
(Northeastern University，measure LLM幻觉，提出数据集)
- Confabulation: The Surprising Value of Large Language Model Hallucinations  [[pdf]](https://aclanthology.org/2024.acl-long.770/)  
(McGill，LLM幻觉的潜在价值)
- TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models  [[pdf]](https://aclanthology.org/2024.findings-acl.197/)  
(Seoul National U，LLM agent和Hallucination结合，提出benchmark衡量角色幻觉)
- Chain-of-Verification Reduces Hallucination in Large Language Models  [[pdf]](https://aclanthology.org/2024.findings-acl.212/)  
(Meta AI，减轻LLM幻觉，让模型自己纠错，使用了FActScore，引用192，没提供代码)
- Before Generation, Align it! A Novel and Effective Strategy for Mitigating Hallucinations in Text-to-SQL  Generation [[pdf]](https://aclanthology.org/2024.findings-acl.324/)  
(HKU，减轻幻觉，Text-to-SQL生成)
- Mitigating Hallucinations in Large Vision-Language Models (LVLMs) via Language-Contrastive Decoding (LCD)  [[pdf]](https://aclanthology.org/2024.findings-acl.359/)  
(Bar Ilan University，减轻LVLM幻觉)
- Logical Closed Loop: Uncovering Object Hallucinations in Large Vision-Language Models [[pdf]](https://aclanthology.org/2024.findings-acl.414/)  
(CAS，检测并减轻LVLM幻觉)
- Visual Hallucinations of Multi-modal Large Language Models [[pdf]](https://aclanthology.org/2024.findings-acl.573/)  
(USTC，评估MLLM幻觉，提出benchnark)
- ACUEval: Fine-grained Hallucination Evaluation and Correction for Abstractive Summarization [[pdf]](https://aclanthology.org/2024.findings-acl.597/)  
(UNC Chapel Hill，检测摘要任务中的幻觉)
- Truth-Aware Context Selection: Mitigating Hallucinations of Large Language Models Being Misled by Untruthful Contexts [[pdf]](https://aclanthology.org/2024.findings-acl.645/)  
(CAS，减轻幻觉，识别输入中的虚假信息)
- Enhancing Hallucination Detection through Perturbation-Based Synthetic Data Generation in System Responses [[pdf]](https://aclanthology.org/2024.findings-acl.789/)  
(ASAPP，幻觉检测)
- Unsupervised Real-Time Hallucination Detection based on the Internal States of Large Language Models [[pdf]](https://aclanthology.org/2024.findings-acl.854/)  
(THU，利用LLM内部状态检测幻觉)
- Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding [[pdf]](https://aclanthology.org/2024.findings-acl.937/)  
(UHH，减轻LVLM幻觉)  
[Top](#llm-hallucination-papers)

## NAACL 202406
#### Hallucination & Factuality
- Volcano: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision [[pdf]](https://aclanthology.org/2024.naacl-long.23/)  
(KAIST AI，减轻LVLM幻觉，self-feedback)
- On Large Language Models’ Hallucination with Regard to Known Facts [[pdf]](https://aclanthology.org/2024.naacl-long.60/)  
(THU，从inference dynamics角度研究“LLM知道正确答案，依然出现幻觉的现象”，利用dynamics构建分类器检测幻觉)
- Language Models Hallucinate, but May Excel at Fact Verification [[pdf]](https://aclanthology.org/2024.naacl-long.62/)  
(THU，LLM as a Judge，与人的判断进行比较，像自己用GPT4衡量Truthfulqa)
- Can Knowledge Graphs Reduce Hallucinations in  LLMs? : A Survey [[pdf]](https://aclanthology.org/2024.naacl-long.219/)  
(Arizona State University，综述：利用知识图谱减轻幻觉)
- TofuEval: Evaluating Hallucinations of  LLMs on Topic-Focused Dialogue Summarization [[pdf]](https://aclanthology.org/2024.naacl-long.251/)  
(AWS，提出benchmark，检测LLM在Topic-Focused Dialogue Summarization上的幻觉表现)
- Deceptive Semantic Shortcuts on Reasoning Chains: How Far Can Models Go without Hallucination? [[pdf]](https://aclanthology.org/2024.naacl-long.424/)  
(UC Davis，结合幻觉和reasoning，语义联想引起的幻觉)
- Hallucination Diversity-Aware Active Learning for Text Summarization [[pdf]](https://aclanthology.org/2024.naacl-long.479/)  
(SJTU，减轻幻觉，检测语义框架中的细粒度幻觉)  
[Top](#llm-hallucination-papers)

## COLM 202410
#### Hallucination & Factuality
- Multi-FAct: Assessing Factuality of Multilingual LLMs using FActScore [[pdf]](https://openreview.net/forum?id=lkrH6ovzsj)  
(KAIST，检测Multilingual LLM使用不同语言，回答不同地理区域问题时的幻觉程度)
- PRobELM: Plausibility Ranking Evaluation for Language Models [[pdf]](https://openreview.net/forum?id=k8KS9Ps71d)
- Evaluating LLMs at Detecting Errors in LLM Responses [[pdf]](https://openreview.net/forum?id=dnwRScljXr)
- Fine-grained Hallucination Detection and Editing for Language Models [[pdf]](https://openreview.net/forum?id=dJMTn3QOWO)  
(U of Washington，**使用了factscore，直接调用FactScorer函数，使用retrieval+ChatGPT**)
- Fakes of Varying Shades: How Warning Affects Human Perception and Engagement Regarding LLM Hallucinations [[pdf]](https://openreview.net/forum?id=c30qeMg8dv)
- Training Language Models on the Knowledge Graph: Insights on Hallucinations and Their Detectability [[pdf]](https://openreview.net/forum?id=Zt1dwG8xrK)  
[Top](#llm-hallucination-papers)

## NeurIPS 202412
#### Test of Time Papers [link](https://blog.neurips.cc/2024/11/27/announcing-the-neurips-2024-test-of-time-paper-awards/)
1. Generative Adversarial Nets 
[[pdf]](https://proceedings.neurips.cc/paper_files/paper/2014/file/5ca3e9b122f61f8f06494c97b1afccf3-Paper.pdf)
[[arxiv]](https://arxiv.org/abs/1406.2661)  
(one of the foundational pieces for generative modeling)
2. Sequence to Sequence Learning with Neural Networks 
[[pdf]](https://proceedings.neurips.cc/paper_files/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)
[[arxiv]](https://arxiv.org/abs/1409.3215)  
(the cornerstone work that set the encoder-decoder architecture, inspiring later attention-based improvements)

#### Best Papers 
1. Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction [[arxiv]](https://arxiv.org/abs/2404.02905)
####  Papers 
1. I Don't Know: Explicit Modeling of Uncertainty with an [IDK] Token [[pdf]](https://arxiv.org/abs/2412.06676v1)



[Top](#llm-hallucination-papers)

## ICML 202407
[Top](#llm-hallucination-papers)

## ICLR 202405
[Top](#llm-hallucination-papers)

## Other 2024
[Top](#llm-hallucination-papers)

## ACL 202307
[Top](#llm-hallucination-papers)

## EMNLP 202312
[Top](#llm-hallucination-papers)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjY5NDU5NDQ2LDE5Mzc1NDgwMjUsMjEyND
A4ODU4MywtMTQ4MDg1NzgxMiwtMTY4NTY5MjI4MiwxMjgyMDAy
NDU5LDExNDIxMDQwOTEsLTg3NTM1NTkyMywxMDY2ODIzNzM3LD
E0ODUxMTcyMiwxNjU4NjUwMDI0LC0xMjkzNjQ3NzM0LC0xNzgz
Njc5ODAyLC0yMTIxNzI3MDI4LC0xNDAxNjYxODEyLC0yMDQwND
E5NzE2LDQ5MTM0MjgyNiwxODY3NjE0NDg3LDkwMTU5ODAyNSwt
MTQxMDU5Mzc3OV19
-->