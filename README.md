# LLM-Hallucination-Papers

## Contents

|  Year  | [Conference](#conference-papers) |                      |                      |
| :---:  |    :----:        |        :---:         |        :---:         |
|  2024  | [ACL](#acl-2024) | [EMNLP](#emnlp-2024) | [NAACL](#naacl-2024) |
|  2023  | [ACL](#acl-2023) | [EMNLP](#emnlp-2023) |                      |
|  2022  | [ACL](#acl-2022) | [EMNLP](#emnlp-2022) | [NAACL](#naacl-2022) |
|  2021  | [ACL](#acl-2021) | [EMNLP](#emnlp-2021) | [NAACL](#naacl-2021) |

## Conference Papers

###  EMNLP 2024
Coming ...

###  ACL 2024
- Self-Alignment for Factuality: Mitigating Hallucinations in  LLMs via Self-Evaluation [[pdf]](https://aclanthology.org/2024.acl-long.107/)  
(CUHK，减轻模型幻觉，使用了TruthfulQA数据集，没提供代码)

- Unified Hallucination Detection for Multimodal Large Language Models [[pdf]](https://aclanthology.org/2024.acl-long.178/)  
(ZJU，多模态大模型幻觉Detection，提出数据集)
- UHGEval: Benchmarking the Hallucination of  Chinese Large Language Models via Unconstrained Generation [[pdf]](https://aclanthology.org/2024.acl-long.288/)  
(RUC，评估LLM幻觉，提出无限制生成数据集)
- ANAH: Analytical Annotation of Hallucinations in Large Language Models [[pdf]](https://aclanthology.org/2024.acl-long.442/)  
(HKUST，Measuring LLM幻觉，提出数据集)
- TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space [[pdf]](https://aclanthology.org/2024.acl-long.483/)  
(CAS，减轻幻觉，通过对特征进行映射，编辑等，使用了TruthfulQA)
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
(Meta AI，减轻LLM幻觉，让模型自己纠错)
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



### NAACL 2024
- Volcano: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision [[pdf]](https://aclanthology.org/2024.naacl-long.23/)  
(KAIST AI，减轻LVLM幻觉，self-feedback)
- On Large Language Models’ Hallucination with Regard to Known Facts [[pdf]](https://aclanthology.org/2024.naacl-long.60/)  
(THU，从inference dynamics角度研究“LLM知道正确答案，依然出现幻觉的现象”，利用dynamics构建分类器检测幻觉)
- Language Models Hallucinate, but May Excel at Fact Verification [[pdf]](https://aclanthology.org/2024.naacl-long.62/)  
(THU，LLM as a Judge，与人的判断进行比较，像自己用GPT4衡量Truthfulqa)
- Can Knowledge Graphs Reduce Hallucinations in  LLMs? : A Survey [[pdf]](https://aclanthology.org/2024.naacl-long.219/)  
(Arizona State University，综述：利用知识图谱减轻幻觉)
- TofuEval: Evaluating Hallucinations of  LLMs on Topic-Focused Dialogue Summarization [[pdf]](https://aclanthology.org/2024.naacl-long.251/)  
- Deceptive Semantic Shortcuts on Reasoning Chains: How Far Can Models Go without Hallucination? [[pdf]](https://aclanthology.org/2024.naacl-long.424/)
- Hallucination Diversity-Aware Active Learning for Text Summarization [[pdf]](https://aclanthology.org/2024.naacl-long.479/)

### ACL 2023
- Detecting and Mitigating Hallucinations in Machine Translation: Model Internal Workings Alone Do Well, Sentence Similarity  Even Better [[pdf]](https://aclanthology.org/2023.acl-long.3/)
- Scene Graph as Pivoting: Inference-time Image-free Unsupervised Multimodal Machine Translation with Visual Scene Hallucination [[pdf]](https://aclanthology.org/2023.acl-long.329/)
- Optimal Transport for Unsupervised Hallucination Detection in Neural Machine Translation [[pdf]](https://aclanthology.org/2023.acl-long.770/)
- Towards Fewer Hallucinations in Knowledge-Grounded Dialogue Generation via Augmentative and Contrastive Knowledge-Dialogue [[pdf]](https://aclanthology.org/2023.acl-short.148/)
- RHO: Reducing Hallucination in Open-domain Dialogues with Knowledge Grounding [[pdf]](https://aclanthology.org/2023.findings-acl.275/)
- CaPE: Contrastive Parameter Ensembling for Reducing Hallucination in Abstractive Summarization [[pdf]](https://aclanthology.org/2023.findings-acl.685/)
### EMNLP 2023
- Evaluating Object Hallucination in Large Vision-Language Models [[pdf]](https://aclanthology.org/2023.emnlp-main.20/)
- HalOmi: A Manually Annotated Benchmark for Multilingual Hallucination and Omission Detection in Machine Translation [[pdf]](https://aclanthology.org/2023.emnlp-main.42/)
- Enhancing Uncertainty-Based Hallucination Detection with Stronger Focus [[pdf]](https://aclanthology.org/2023.emnlp-main.58/)
- The Troubling Emergence of Hallucination in Large Language Models - An Extensive Definition, Quantification, and Prescriptive Remediations [[pdf]](https://aclanthology.org/2023.emnlp-main.155/)
- Critic-Driven Decoding for Mitigating Hallucinations in Data-to-text Generation [[pdf]](https://aclanthology.org/2023.emnlp-main.172/)
- Why  LLMs Hallucinate, and How to Get (Evidential) Closure: Perceptual, Intensional, and Extensional Learning for Faithful Natural Language Generation [[pdf]](https://aclanthology.org/2023.emnlp-main.192/)
- The Curious Case of Hallucinatory (Un)answerability: Finding Truths in the Hidden States of Over-Confident Large Language Models [[pdf]](https://aclanthology.org/2023.emnlp-main.220/)
- Fine-tuned  LLMs Know More, Hallucinate Less with Few-Shot Sequence-to-Sequence Semantic Parsing over  Wikidata [[pdf]](https://aclanthology.org/2023.emnlp-main.353/)
- HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models [[pdf]](https://aclanthology.org/2023.emnlp-main.397/)
- Continuing soon ...
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MDc3NzAxNzMsLTE3MDgyNzkxOTMsMT
U1NjUwMDQxMywtMTcwOTE3MDg3NCwtMTYwODYxMTQxMSwyMDAx
MzEwMDcsMjEzMjcxMDE4MywxNjQyMTUxNDIyLC05MDE3ODk5Nj
YsNzA1NzczNDg0LC0yODY3Mzc4NCwxNTM5NDEyODYxLC0zOTE4
MDQwNDIsLTY5NzkyODExMywtMzg5NDYwMzc3LC03MTA0MDMxND
gsMTk5OTQ5Nzg5MywtMTc5ODU2MzAyOSwtNjY3MjYxMTIyLDg4
ODU2MTA5NF19
-->