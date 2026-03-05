# A Comprehensive Survey of Multimodal LLMs for Scientific Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<video src="https://github.com/user-attachments/assets/d91ea824-d101-4d6d-ac10-7323cc2791b0"></video>


[[Project Page]](https://bagayalus.github.io/S3-Bench/) [[Preprint]](https://www.preprints.org/manuscript/202602.1847) [[OpenReview]](https://openreview.net/forum?id=HSz1Kr5BeC)

Author list: [Liang Yan](https://divinyan.com/)†‡, [Xu Jiang](https://openreview.net/profile?id=~Xu_Jiang9)‡, [Jian Ma](https://openreview.net/profile?id=~Jian_Ma8)‡, [Yuhang Liu](https://openreview.net/profile?id=~Yuhang_Liu21), [Tian Bian](https://scholar.google.com/citations?user=rxmCzYIAAAAJ&hl=zh-TW), [Qichao Wang](https://qichaowang.me/), [Abhishek Basu](https://abasu.ai/), [Yu Rong](https://royrong.me/), [Tingyang Xu](https://scholar.google.com/citations?user=6gIs5YMAAAAJ&hl=zh-CN),[Pengcheng Wu](https://scholar.google.com/citations?user=kX_GFDIAAAAJ&hl=en), [Le Song](https://dasongle.github.io/), [Imran Razzak](https://imranrazzak.github.io/), [Junchi Yan](https://thinklab.sjtu.edu.cn/)§, [Zengfeng Huang](https://zengfenghuang.github.io/)§, [Yutong Xie](https://ytongxie.github.io/)§

(† Project Lead, ‡ Equal Contribution, § Corresponding Author)

Recent advances in artificial intelligence (AI), especially large language models, have accelerated the integration of multimodal data in scientific research. Given that scientific fields involve diverse data types, ranging from text and images to complex biological sequences, graphs, and structures, multimodal large language models (MLLMs) have emerged as powerful tools to bridge these modalities, enabling more comprehensive data analysis and intelligent decision-making. This work, S3−Bench, provides a comprehensive overview of recent advances in MLLMs, focusing on their diverse applications across science. We systematically review the progress of MLLMs in key scientific domains, including drug discovery, molecular & protein design, materials science, and genomics. The work highlights model architectures, domain-specific adaptations, benchmark datasets, and promising future directions. Our work aims to serve as a valuable resource for both researchers and practitioners interested in the rapidly evolving landscape of multimodal AI for science.



*If you find this repository or our survey helpful in your research, please kindly cite our paper:*

```bibtex
@article{202602.1847,
	doi = {10.20944/preprints202602.1847.v1},
	url = {https://doi.org/10.20944/preprints202602.1847.v1},
	year = 2026,
	month = {February},
	publisher = {Preprints},
	author = {Liang Yan and Xu Jiang and Jian Ma and Yuhang Liu and Tian Bian and Qichao Wang and Abhishek Basu and Yu Rong and Tingyang Xu and Pengcheng Wu and Le Song and Imran Razzak and Junchi Yan and Zengfeng Huang and Yutong Xie},
	title = {A Comprehensive Survey of Multimodal LLMs for Scientific Discovery},
	journal = {Preprints}
}
```




## News & Updates

- **2026-02-27:**  Our preprint is available online at [Preprints.org](https://preprints.org/) ! Check [here](https://www.preprints.org/manuscript/202602.1847).
- **2025-11-13:** The first version of S3Bench are accepted by [NeurIPS 2025 VLM4RWD Workshop](https://mozhgan91.github.io/vlm4rwd-neurips25-ws/) ! Check our [project page](https://bagayalus.github.io/S3-Bench/).


## 1. Related Survery Work

### 1.1 Survery for General LLMs

1. **A Survey of Large Language Models**. Arxiv 2023. [[paper](https://arxiv.org/abs/2303.18223)] [[project page](https://github.com/RUCAIBox/LLMSurvey)]. Mar 31, 2023.
2. **A survey on evaluation of large language models**. ACM Transactions on Intelligent Systems and Technology 2024. [[paper](https://arxiv.org/abs/2307.03109)] [[project page](https://github.com/MLGroupJLU/LLM-eval-survey)]. Jul 6, 2023.
3. **A comprehensive overview of large language models**. Arxiv 2024. [[paper](https://arxiv.org/abs/2307.06435)] [[project page](https://github.com/humza909/LLM_Survey)]. Jul 12, 2023.
4. **Efficient large language models: A survey**. TMLR 2024. [[paper](https://arxiv.org/abs/2312.03863)] [[project page](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey)]. Dec 6, 2023.
5. **Large Language Models: A Survey**. Arxiv 2024. [[paper](https://arxiv.org/abs/2402.06196)]. Feb 9, 2024.
6. **A survey on large language models: Applications, challenges, limitations, and practical usage**. TechRxiv 2025. [[paper](10.36227/techrxiv.23589741.v8)] [[project page](https://github.com/anas-zafar/LLM-Survey)]. Jan 14, 2025.

### 1.2 Survery for General MLLMs

1. **A Survey on Multimodal Large Language Models**. National Science Review 2024. [[paper](https://arxiv.org/abs/2306.13549)] [[project page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)]. Jun 23, 2023.
2. **Multimodal large language models: A survey**. IEEE BigData 2023. [[paper](https://arxiv.org/abs/2311.13165)]. Nov 22, 2023.
3. **The revolution of multimodal large language models: a survey**. ACL 2024 (Findings). [[paper](https://arxiv.org/abs/2402.12451)]. Feb 19, 2024.
4. **Efficient Multimodal Large Language Models: A Survey**. Arxiv 2024. [[paper](https://arxiv.org/abs/2405.10739)] [[project page](https://github.com/swordlidev/Efficient-Multimodal-LLMs-Survey)]. May 17, 2024.
5. **A Survey of Multimodal Large Language Model from A Data-centric Perspective**. Arxiv 2024. [[paper](https://arxiv.org/abs/2405.16640)] [[project page](https://github.com/beccabai/Data-centric_multimodal_LLM?tab=readme-ov-file)]. May 26, 2024.
6. **A Survey of Multimodel Large Language Models**. CAICE 2024. [[paper](https://dl.acm.org/doi/10.1145/3672758.3672824)]. Aug 06, 2024.
7. **A Comprehensive Survey of Multimodal Large Language Models: Concept, Application and Safety**. Arxiv 2024. [[paper](https://www.researchgate.net/publication/385012837_A_Comprehensive_Survey_of_Multimodal_Large_Language_Models_Concept_Application_and_Safety)]. Oct 18, 2024.

### 1.3 Survery for LLMs&MLLMs for Medicine

1. **Large language models in medicine**. Nature Medicine 2023. [[paper](https://www.nature.com/articles/s41591-023-02448-8)]. July 17, 2023.
2. **A Survey of Large Language Models in Medicine: Progress, Application, and Challenge**. Arxiv 2023. [[paper](https://arxiv.org/abs/2311.05112)] [[project page](https://github.com/AI-in-Health/MedLLMsPracticalGuide)]. Nov 9, 2023.
3. **A survey of large language models for healthcare: from data, technology, and applications to accountability and ethics**. Arxiv 2023. [[paper](https://arxiv.org/abs/2310.05694)] [[project page](https://github.com/KaiHe-better/LLM-for-Healthcare)]. Oct 9, 2023.
4. **A comprehensive survey of large language models and multimodal large language models in medicine**. Arxiv 2024. [[paper](https://arxiv.org/abs/2405.08603)]. May 14, 2024.
5. **Large language models for medicine: a survey**. Arxiv 2024. [[paper](https://arxiv.org/abs/2405.13055)]. May 20, 2024.
6. **A Survey on Medical Large Language Models: Technology, Application, Trustworthiness, and Future Directions**. Arxiv 2024.  [[paper](https://arxiv.org/abs/2406.03712)]. June 6, 2024.
7. **Large language models in medical and healthcare fields: applications, advances, and challenges**. Artificial Intelligence Review 2024. [[paper](https://link.springer.com/article/10.1007/s10462-024-10921-0)]. Sep 20, 2024.
8. **Large Language Model for Medical Images: A Survey of Taxonomy, Systematic Review, and Future Trends**. Big Data Mining and Analytics 2025. [[paper](https://ieeexplore.ieee.org/document/10856853)]. Jan 28, 2025.

### 1.4 Survery for LLMs&MLLMs for Science

1. **Scientific Large Language Models: A Survey on Biological & Chemical Domains**. Arxiv 2024. [[paper](https://arxiv.org/abs/2401.14656)] [[project page](https://github.com/HICAI-ZJU/Scientific-LLM-Survey)]. Jan 26, 2024.
2. **A Comprehensive Survey of Scientific Large Language Models and Their Applications in Scientific Discovery**. EMNLP 2024. [[paper](https://arxiv.org/abs/2406.10833)] [[project page](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models)]. July 16, 2024.

## 2. MLLMs for Drug&Molecule

### 2.1 Molecular Representation Learning, Property and Interaction Prediction

1. **Exploring bitter and sweet: the application of large language models in molecular taste prediction**. Journal of Chemical Information and Modeling 2024. [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00681)]. May 7, 2024.
2. **ChemBERTa: Large-scale self-supervised learning for molecular property prediction**. Arxiv 2020. [[paper](https://arxiv.org/abs/2010.09885)]. Oct 19, 2020.
3. **Molecular representation learning with language models and domain-relevant auxiliary tasks**. Arxiv 2020. [[paper](https://arxiv.org/abs/2011.13230)]. Nov 26, 2020.
4. **SMILES Transformer: Pre-trained Molecular Fingerprint for Low Data Drug Discovery**. Arxiv 2019. [[paper](https://arxiv.org/abs/1911.04738)]. Nov 12, 2019.
5. **Effective and explainable molecular property prediction by chain-of-thought enabled large language models and multi-modal molecular information fusion**. Journal of Chemical Information and Modeling 2025. [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.5c00577)] [[code](https://github.com/jinchang1223/LLM-MPP)]. May 20, 2025.
6. **Pharmabench: Enhancing admet benchmarks with large language models**. Nature Scientific Data 2024. [[paper](https://www.nature.com/articles/s41597-024-03793-0)] [[code](https://github.com/mindrank-ai/PharmaBench)]. Sep 10, 2024.
7. **Drugrealign: a multisource prompt framework for drug repurposing based on large language models**. BMC Biology 2024. [[paper](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-024-02028-3)] [[code](https://github.com/kkkayle/DrugReAlign)]. Oct 8, 2024.
8. **Dti-lm: language model powered drug–target interaction prediction**. Bioinformatics 2024. [[paper](https://academic.oup.com/bioinformatics/article/40/9/btae533/7747660)] [[code](https://github.com/compbiolabucf/DTI-LM/)]. Sep 2, 2024.
9. **Drugagent: Multi-agent large language model-based reasoning for drug-target interaction prediction**. Arxiv 2024. [[paper](https://arxiv.org/abs/2408.13378)]. Aug 23, 2024.
10. **Ddi-gpt: Explainable prediction of drug-drug interactions using large language models enhanced with knowledge graphs**. BioRxiv 2024. [[paper](https://www.biorxiv.org/content/10.1101/2024.12.06.627266v1)] [[code](https://github.com/Mew233/ddigpt)]. Dec 09, 2024.
11. **Cotel-d3x: A chain-of-thought enhanced large language model for drug–drug interaction triplet extraction**. Expert Systems with Applications 2025. [[paper](https://www.sciencedirect.com/science/article/pii/S0957417425005755)]. May 10, 2025.

### 2.2 De Novo Molecular Generation with LLMs

1. **MolGPT: Molecular generation using a transformer-decoder model**. Journal of Chemical Information and Modeling 2021. [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600)] [[code](https://github.com/devalab/molgpt)]. Oct 25, 2021.
2. **Chatmol: interactive molecular discovery with natural language**. Bioinformatics 2024. [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600)] [[code](https://github.com/Ellenzzn/ChatMol)]. Sep 02, 2024.
3. **Drugllm: Open large language model for few-shot molecule generation**. Arxiv 2024. [[paper](https://arxiv.org/abs/2405.06690)]. May 07, 2024.
4. **CogMol: Target-specific and selective drug design for covid-19 using deep generative models**. NeurIPS 2020. [[paper](https://arxiv.org/abs/2004.01215)]. Jun 24, 2020.
5. **X-MOL: large-scale pre-training for molecular understanding and diverse molecular analysis**. BioRxiv 2020. [[paper](https://www.biorxiv.org/content/10.1101/2020.12.23.424259v2.full)]. Jan 1, 2021.
6. **Molecular representation learning with language models and domain-relevant auxiliary tasks**. Arxiv 2020. [[paper](https://arxiv.org/abs/2011.13230)] [[code](https://github.com/BenevolentAI/MolBERT)]. Nov 26, 2020.

### 2.3 Controlled Molecule Optimization and Editing

1. **Leveraging language model for advanced multiproperty molecular optimization via prompt engineering.** Nature Machine Intelligence 2024. [[paper](https://www.nature.com/articles/s42256-024-00916-5)] [[code](https://github.com/wzxxxx/Prompt-MolOpt)]. Oct 21, 2024.
2. **Small molecule optimization with large language models**. Arxiv 2024. [[paper](https://arxiv.org/abs/2407.18897)] [[code](https://github.com/yerevann/chemlactica)]. July 26, 2024.
3. **Lico: Large language models for in-context molecular optimization**. ICLR 2025. [[paper](https://openreview.net/forum?id=yu1vqQqKkx)] [[code](https://github.com/tung-nd/LICO)]. June 27, 2024.
4. **Not just another molecule generator: Artificial intelligence in drug discovery**. TBA
5. **MolT5: Translation between Molecules and Natural Language**.  EMNLP 2022. [[paper](https://arxiv.org/abs/2204.11817)] [[code](https://github.com/blender-nlp/MolT5)]. April 25, 2022.
6. **Mollm: Multi-objective large language model for molecular design–optimizing with experts**. Arxiv 2025. [[paper](https://arxiv.org/html/2502.12845v1)]. Feb 18, 2025.
7. **Drugassist: A large language model for molecule optimization**. Briefings in Bioinformatics 2024. [[paper](https://academic.oup.com/bib/article/26/1/bbae693/7942355)] [[code](https://github.com/blazerye/DrugAssist)]. Dec 28, 2023.

### 2.4 Chemical Reaction Prediction and Synthesis Planning

1. **Retrosynthetic Reaction Prediction Using Neural Sequence-to-Sequence Models**. ACS Central Science 2017. [[paper](https://pubs.acs.org/doi/10.1021/acscentsci.7b00303)] [[code](https://github.com/pandegroup/reaction_prediction_seq2seq)]. Sep 5, 2017.
2. **Mapping the space of chemical reactions using attention-based neural networks**. Nature Machine Intelligence 2021. [[paper](https://www.nature.com/articles/s42256-020-00284-w)] [[code](https://rxn4chemistry.github.io/rxnfp/)]. Jan 28, 2021.
3. **State-of-the-art augmented NLP transformer models for direct and single-step retrosynthesis**. Nature Communications 2020. [[paper](https://www.nature.com/articles/s41467-020-19266-y)] [[code](https://github.com/bigchem/synthesis)]. Nov 04, 2020.
4. **Bridging chemistry and artificial intelligence by a reaction description language**. Nature Machine Intelligence 2025. [[paper](https://www.nature.com/articles/s42256-025-01032-8)] [[code](https://github.com/jiachengxiong/ReactSeq)]. May 13, 2025.
5. **Reactgpt: Understanding of chemical reactions via in-context tuning**. AAAI 2025. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/31983)]. April 11, 2025.

### 2.5 Multi-Modal LLMs and Chemistry-Focused Agents

1. **ChemCrow: Augmenting large-language models with chemistry tools**. Nature Machine Intelligence 2024. [[paper](https://www.nature.com/articles/s42256-024-00832-8)] [[code](https://github.com/ur-whitelab/chemcrow-runs)]. May 08, 2024.
2. **Molx: Enhancing large language models for molecular learning with a multi-modal extension**. Arxiv 2024. [[paper](https://arxiv.org/abs/2406.06777)] [[code](https://github.com/ur-whitelab/chemcrow-runs)]. June 10, 2024.
3. **Git-mol: A multi-modal large language model for molecular science with graph, image, and text**. Computers in Biology and Medicine 2024. [[paper](https://www.sciencedirect.com/science/article/pii/S0010482524001574)] [[code](https://github.com/AI-HPC-Research-Team/GIT-Mol)]. Feb 6, 2024.
4. **Token-mol 1.0: tokenized drug design with large language models**. Nature Communications 2025. [[paper](https://www.nature.com/articles/s41467-025-59628-y)] [[code](https://github.com/jkwang93/Token-Mol)]. May 13, 2024.
5. **Uni-mol: A universal 3d molecular representation learning framework**. ICLR 2023. [[paper](https://openreview.net/forum?id=6K2RM6wVqKu)] [[code](https://github.com/deepmodeling/Uni-Mol)]. Feb 27, 2023.
6. **BioGPT: Generative pre-trained transformer for biomedical text generation and mining**. Briefings in Bioinformatics 2022. [[paper](https://academic.oup.com/bib/article/23/6/bbac409/6713511)] [[code](https://github.com/microsoft/BioGPT)]. Feb 27, 2023.
7. **Multi-modal representation learning for molecular property prediction: sequence, graph, geometry**. Arxiv 2024. [[paper](https://arxiv.org/abs/2401.03369)] [[code](https://github.com/Vencent-Won/SGGRL)]. Jan 9, 2024.
8. **Instructmol: Multi-modal integration for building a versatile and reliable molecular assistant in drug discovery**. COLING 2025. [[paper](https://aclanthology.org/2025.coling-main.25/)] [[code](https://github.com/IDEA-XL/InstructMol)]. Dec 19, 2024.
9. **Incorporating molecular knowledge in large language models via multimodal modeling**.  IEEE Transactions on Computational Social Systems 2025. [[paper](https://aclanthology.org/2025.coling-main.25/)] [[code](https://github.com/IDEA-XL/InstructMol)]. Jan 13, 2025.
10. **MoleculeScribe: describing and designing molecules with multi-modal large language models**. TBA
11. **Text-augmented multimodal llms for chemical reaction condition recommendation**. Arxiv 2024. [[paper](https://arxiv.org/abs/2407.15141)] [[code](https://github.com/IDEA-XL/InstructMol)]. July 21, 2024.
12. **ChemToolAgent: The impact of tools on language agents for chemistry problem solving**. Arxiv 2024. [[paper](https://arxiv.org/abs/2411.07228)] [[code](https://github.com/OSU-NLP-Group/ChemToolAgent)]. Nov 11, 2024.
13. **Chemagent: Self-updating memories in large language models improves chemical reasoning**. ICLR 2025. [[paper](https://openreview.net/forum?id=kuhIqeVg0e)] [[code](https://github.com/gersteinlab/ChemAgent)]. Mar 12, 2025.
14. **Chemthinker: Thinking like a chemist with multi-agent llms for deep molecular insights**. Arxiv 2025. [[paper](https://openreview.net/forum?id=zlAUnwhE2v)]. Sep 28, 2024.

## 3. MLLMs for Protein

### 3.1 LLMs_related work

### 3.2 MLLMs_related work
#### 3.2.1 Protein Sequence-Language Integration
1. **A Text-guided Protein Design Dramework.**. Nature Machine Intelligence 2025. [[paper][https://www.nature.com/articles/s42256-025-01011-z]]. Mar 27, 2025
2.	**ProtT3: Protein-to-Text Generation for Text-based Protein Understanding.** ACL 2024. [[paper][https://aclanthology.org/2024.acl-long.324/]]. May 21, 2024.  ￼
3.	**ProtCLIP: Function-Informed Protein Multi-Modal Learning.** AAAI 2025. [[paper][https://ojs.aaai.org/index.php/AAAI/article/view/34456/36611]]. Dec 28, 2024.  ￼
4.	**OntoProtein: Protein Pretraining With Gene Ontology Embedding.** ICLR 2022. [[paper][https://arxiv.org/abs/2201.11147]]. Jan 23, 2022.
5.	**BioMedGPT: Open Multimodal Generative Pre-trained Transformer for BioMedicine.** arXiv 2023. [[paper][https://arxiv.org/abs/2308.09442]]. Aug 18, 2023.
6.	**ProtLLM: An Interleaved Protein-Language LLM with Protein-as-Word Pre-Training.** arXiv 2024. [[paper][https://arxiv.org/abs/2403.07920]]. Feb 28, 2024.
7.	**ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing.** arXiv 2024. [[paper][https://arxiv.org/abs/2402.16445]]. Feb 26, 2024.
8.	**InstructProtein: Aligning Human and Protein Language via Knowledge Instruction.** ACL 2024. [[paper][https://aclanthology.org/2024.acl-long.62/]]. Aug, 2024.
9.	**ESM-AA: Multi-scale Protein Language Model for Unified Molecular Modeling.** ICML 2024. [[paper][https://arxiv.org/abs/2403.12995]]. Mar 20, 2024.
10.	**BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations.** EMNLP 2023. [[paper][https://aclanthology.org/2023.emnlp-main.70.pdf]]. Dec 2023
11.	**BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning.** Findings of ACL 2024. [[paper][https://aclanthology.org/2024.findings-acl.71/]]. Aug 2024.
12.	**Galactica: A Large Language Model for Science.** arXiv 2022. [[paper][https://arxiv.org/abs/2211.09085]]. Nov 16, 2022.
13.	**ProtChatGPT: Towards Understanding Proteins with Large Language Models.** arXiv 2024. [[paper][https://arxiv.org/abs/2402.09649]]. Feb 15, 2024.  
#### 3.2.2 Protein Structure-Sequence-Language Integration

#### 3.2.3 Protein Interactions and Specialized Application

---

## 4. MLLMs for Material

### 4.1 LLMs-Related Work

1. Crystal Structure Generation with Autoregressive Large Language Modeling.
2. Fine-Tuned Language Models Generate Stable Inorganic Materials as Text.
3. FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions.
4. Invariant Tokenization of Crystalline Materials for Language Model Enabled Generation.
5. LLMatDesign: Autonomous Materials Discovery with Large Language Models
6. MechGPT, a Language-Based Strategy for Mechanics and Materials Modeling That Connects Knowledge Across Scales, Disciplines, and Modalities
7. Leveraging Large Language Models for Explaining Material Synthesis Mechanisms: The Foundation of Materials Discovery
8. Large language models for material property predictions: elastic constant tensor prediction and materials design
9. MaScQA: investigating materials science knowledge of large language models
10. Large-language models: The game-changers for materials science research
11. Material transformers: deep learning language models for generative materials design
12. LLaMP: Large Language Model Made Powerful for High-fidelity Materials Knowledge Retrieval and Distillation
13. 34 Examples of LLM Applications in Materials Science and Chemistry: Towards Automation, Assistants, Agents, and Accelerated Scientific Discovery
14. Reflections from the 2024 Large Language Model (LLM) Hackathon for Applications in Materials Science and Chemistry
15. AtomAgents: Alloy design and discovery through physics-aware multi-modal multi-agent artificial intelligence
16. From Tokens to Materials: Leveraging Language Models for Scientific Discovery
17. Accelerating scientific discovery with generative knowledge extraction, graph-based representation, and multimodal intelligent graph reasoning
18. MatExpert: Decomposing Materials Discovery by Mimicking Human Experts
19. Evaluating the performance and robustness of LLMs in materials science Q&A and property predictions

### 4.2 MLLMs-Related Work

1. Multi-modal conditional diffusion model using signed distance functions for metal-organic frameworks generation
2. GenMS: Generative Hierarchical Materials Search
3. Probing the limitations of multimodal language models for chemistry and materials research
4. MatterChat: A Multi-Modal LLM for Material Science
5. LLM-Fusion: A Novel Multimodal Fusion Model for Accelerated Material Discovery
6. Multimodal Foundation Models for Material Property Prediction and Discovery
7. Automating alloy design and discovery with physics-aware multimodal multiagent AI
8. Multimodal Machine Learning for Materials Science: Discovery of Novel Li-Ion Solid Electrolytes
9. TDCM25: A Multi-Modal Multi-Task Benchmark for Temperature-Dependent Crystalline Materials

---

## 5. MLLMs for Gene

### 5.1 LLMs-Related Work

1. GP-GPT: Large Language Model for Gene-Phenotype Mapping
2. Genetic Transformer: An Innovative Large Language Model Driven Approach for Rapid and Accurate Identification of Causative Variants in Rare Genetic Diseases
3. Evaluation of large language models for discovery of gene set function
4. Assessing the utility of large language models for phenotype-driven gene prioritization in the diagnosis of rare genetic disease
5. Harnessing large language models (LLMs) for candidate gene prioritization and selection
6. Gene-associated Disease Discovery Powered by Large Language Models
7. GeneGPT: augmenting large language models with domain tools for improved access to biomedical information
8. Assessing the Utility of Large Language Models for Phenotype-Driven Gene Prioritization in Rare Genetic Disorder Diagnosis
9. Enhancing gene set overrepresentation analysis with large language models
10. Benchmarking large language models for genomic knowledge with GeneTuring
11. A large language model framework for literature-based disease–gene association prediction
12. Cancer gene identification through integrating causal prompting large language model with omics data–driven causal inference
13. Large language models generate functional protein sequences across diverse families
14. FGeneBERT: function-driven pre-trained gene language model for metagenomics
15. Genetic Instruct: Scaling up Synthetic Generation of Coding Instructions for Large Language Models
16. QWENDY: Gene Regulatory Network Inference Enhanced by Large Language Model and Transformer
17. Exploring Genomic Large Language Models: Bridging the Gap between Natural Language and Gene Sequences
18. Language modelling techniques for analysing the impact of human genetic variation
19. Integrating unsupervised language model with triplet neural networks for protein gene ontology prediction
20. Genomic Language Models (gLMs) decode bacterial genomes for improved gene prediction and translation initiation site identification
21. Can Large Language Models Predict Antimicrobial Resistance Gene?
22. Automating Candidate Gene Prioritization with Large Language Models: Development and Benchmarking of an API-Driven Workflow Leveraging GPT-4
23. GENATATOR: de novo Gene Annotation With DNA Language Mode
24. Database-Augmented Transformer-Based Large Language Models Achieve High Accuracy in Mapping Gene-Phenotype Relationships
25. Identification of gene function using prediction by partial matching (PPM) language models
26. Survey of Genetic Programming and Large Language Models
27. Small, Open-Source Text-Embedding Models as Substitutes to OpenAI Models for Gene Analysis
28. OntoProtein: Protein Pretraining With Gene Ontology Embedding
29. DNABERT: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome

### 5.2 MLLMs-Related Work

1. Geneverse: A collection of Open-source Multimodal Large Language Models for Genomic and Proteomic Research
2. GexMolGen: cross-modal generation of hit-like molecules via large language model encoding of gene expression signatures
3. Towards multimodal foundation models in molecular cell biology
4. GeneChat: A Multi-Modal Large Language Model for Gene Function Prediction
5. A multimodal conversational agent for DNA, RNA and protein tasks

