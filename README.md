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
- **2025-11-13:** The first version of S3Bench is accepted by [NeurIPS 2025 VLM4RWD Workshop](https://mozhgan91.github.io/vlm4rwd-neurips25-ws/) ! Check our [project page](https://bagayalus.github.io/S3-Bench/).


## 1. Related Survery Work



### 1.1 Survey for General LLMs
|  Title  |   Venue  |   Date   |   Project Page   |
|:--------|:--------:|:--------:|:----------------:|
| [A Survey of Large Language Models](https://arxiv.org/abs/2303.18223) | arXiv | Mar 31, 2023 | [project page](https://github.com/RUCAIBox/LLMSurvey) |
| [A survey on evaluation of large language models](https://arxiv.org/abs/2307.03109) | ACM Transactions on Intelligent Systems and Technology | Jul 6, 2023 | [project page](https://github.com/MLGroupJLU/LLM-eval-survey) |
| [A comprehensive overview of large language models](https://arxiv.org/abs/2307.06435) | arXiv | Jul 12, 2023 | [project page](https://github.com/humza909/LLM_Survey) |
| [Efficient large language models: A survey](https://arxiv.org/abs/2312.03863) | TMLR | Dec 6, 2023 | [project page](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey) |
| [Large Language Models: A Survey](https://arxiv.org/abs/2402.06196) | arXiv | Feb 9, 2024 | - |
| [A survey on large language models: Applications, challenges, limitations, and practical usage](https://doi.org/10.36227/techrxiv.23589741.v8) | TechRxiv | Jan 14, 2025 | [project page](https://github.com/anas-zafar/LLM-Survey) |


### 1.2 Survey for General MLLMs
|  Title  |   Venue  |   Date   |   Project Page   |
|:--------|:--------:|:--------:|:----------------:|
| [A Survey on Multimodal Large Language Models](https://arxiv.org/abs/2306.13549) | National Science Review | Jun 23, 2023 | [project page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) |
| [Multimodal large language models: A survey](https://arxiv.org/abs/2311.13165) | IEEE BigData 2023 | Nov 22, 2023 | - |
| [The revolution of multimodal large language models: a survey](https://arxiv.org/abs/2402.12451) | ACL 2024 (Findings) | Feb 19, 2024 | - |
| [Efficient Multimodal Large Language Models: A Survey](https://arxiv.org/abs/2405.10739) | arXiv | May 17, 2024 | [project page](https://github.com/swordlidev/Efficient-Multimodal-LLMs-Survey) |
| [A Survey of Multimodal Large Language Model from A Data-centric Perspective](https://arxiv.org/abs/2405.16640) | arXiv | May 26, 2024 | [project page](https://github.com/beccabai/Data-centric_multimodal_LLM?tab=readme-ov-file) |
| [A Survey of Multimodel Large Language Models](https://dl.acm.org/doi/10.1145/3672758.3672824) | CAICE 2024 | Aug 06, 2024 | - |
| [A Comprehensive Survey of Multimodal Large Language Models: Concept, Application and Safety](https://www.researchgate.net/publication/385012837_A_Comprehensive_Survey_of_Multimodal_Large_Language_Models_Concept_Application_and_Safety) | arXiv | Oct 18, 2024 | - |


### 1.3 Survey for LLMs&MLLMs for Medicine
|  Title  |   Venue  |   Date   |   Project Page   |
|:--------|:--------:|:--------:|:----------------:|
| [Large language models in medicine](https://www.nature.com/articles/s41591-023-02448-8) | Nature Medicine | Jul 17, 2023 | - |
| [A Survey of Large Language Models in Medicine: Progress, Application, and Challenge](https://arxiv.org/abs/2311.05112) | arXiv | Nov 9, 2023 | [project page](https://github.com/AI-in-Health/MedLLMsPracticalGuide) |
| [A survey of large language models for healthcare: from data, technology, and applications to accountability and ethics](https://arxiv.org/abs/2310.05694) | arXiv | Oct 9, 2023 | [project page](https://github.com/KaiHe-better/LLM-for-Healthcare) |
| [A comprehensive survey of large language models and multimodal large language models in medicine](https://arxiv.org/abs/2405.08603) | arXiv | May 14, 2024 | - |
| [Large language models for medicine: a survey](https://arxiv.org/abs/2405.13055) | arXiv | May 20, 2024 | - |
| [A Survey on Medical Large Language Models: Technology, Application, Trustworthiness, and Future Directions](https://arxiv.org/abs/2406.03712) | arXiv | Jun 6, 2024 | - |
| [Large language models in medical and healthcare fields: applications, advances, and challenges](https://link.springer.com/article/10.1007/s10462-024-10921-0) | Artificial Intelligence Review | Sep 20, 2024 | - |
| [Large Language Model for Medical Images: A Survey of Taxonomy, Systematic Review, and Future Trends](https://ieeexplore.ieee.org/document/10856853) | Big Data Mining and Analytics | Jan 28, 2025 | - |



### 1.4 Survey for LLMs&MLLMs for Science
|  Title  |   Venue  |   Date   |   Project Page   |
|:--------|:--------:|:--------:|:----------------:|
| [Scientific Large Language Models: A Survey on Biological & Chemical Domains](https://arxiv.org/abs/2401.14656) | arXiv | Jan 26, 2024 | [project page](https://github.com/HICAI-ZJU/Scientific-LLM-Survey) |
| [A Comprehensive Survey of Scientific Large Language Models and Their Applications in Scientific Discovery](https://arxiv.org/abs/2406.10833) | EMNLP 2024 | Jul 16, 2024 | [project page](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models) |

## 2. MLLMs for Drug&Molecule


### 2.1 Molecular Representation Learning, Property and Interaction Prediction
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Exploring bitter and sweet: the application of large language models in molecular taste prediction](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00681) | Journal of Chemical Information and Modeling | May 7, 2024 | - |
| [ChemBERTa: Large-scale self-supervised learning for molecular property prediction](https://arxiv.org/abs/2010.09885) | arXiv | Oct 19, 2020 | - |
| [Molecular representation learning with language models and domain-relevant auxiliary tasks](https://arxiv.org/abs/2011.13230) | arXiv | Nov 26, 2020 | - |
| [SMILES Transformer: Pre-trained Molecular Fingerprint for Low Data Drug Discovery](https://arxiv.org/abs/1911.04738) | arXiv | Nov 12, 2019 | - |
| [Effective and explainable molecular property prediction by chain-of-thought enabled large language models and multi-modal molecular information fusion](https://pubs.acs.org/doi/10.1021/acs.jcim.5c00577) | Journal of Chemical Information and Modeling | May 20, 2025 | [code](https://github.com/jinchang1223/LLM-MPP) |
| [Pharmabench: Enhancing admet benchmarks with large language models](https://www.nature.com/articles/s41597-024-03793-0) | Nature Scientific Data | Sep 10, 2024 | [code](https://github.com/mindrank-ai/PharmaBench) |
| [Drugrealign: a multisource prompt framework for drug repurposing based on large language models](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-024-02028-3) | BMC Biology | Oct 8, 2024 | [code](https://github.com/kkkayle/DrugReAlign) |
| [Dti-lm: language model powered drug–target interaction prediction](https://academic.oup.com/bioinformatics/article/40/9/btae533/7747660) | Bioinformatics | Sep 2, 2024 | [code](https://github.com/compbiolabucf/DTI-LM/) |
| [Drugagent: Multi-agent large language model-based reasoning for drug-target interaction prediction](https://arxiv.org/abs/2408.13378) | arXiv | Aug 23, 2024 | - |
| [Ddi-gpt: Explainable prediction of drug-drug interactions using large language models enhanced with knowledge graphs](https://www.biorxiv.org/content/10.1101/2024.12.06.627266v1) | bioRxiv | Dec 09, 2024 | [code](https://github.com/Mew233/ddigpt) |
| [Cotel-d3x: A chain-of-thought enhanced large language model for drug–drug interaction triplet extraction](https://www.sciencedirect.com/science/article/pii/S0957417425005755) | Expert Systems with Applications | May 10, 2025 | - |


### 2.2 De Novo Molecular Generation with LLMs
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [MolGPT: Molecular generation using a transformer-decoder model](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) | Journal of Chemical Information and Modeling | Oct 25, 2021 | [code](https://github.com/devalab/molgpt) |
| [Chatmol: interactive molecular discovery with natural language](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) | Bioinformatics | Sep 02, 2024 | [code](https://github.com/Ellenzzn/ChatMol) |
| [Drugllm: Open large language model for few-shot molecule generation](https://arxiv.org/abs/2405.06690) | arXiv | May 07, 2024 | - |
| [CogMol: Target-specific and selective drug design for covid-19 using deep generative models](https://arxiv.org/abs/2004.01215) | NeurIPS 2020 | Jun 24, 2020 | - |
| [X-MOL: large-scale pre-training for molecular understanding and diverse molecular analysis](https://www.biorxiv.org/content/10.1101/2020.12.23.424259v2.full) | bioRxiv | Jan 1, 2021 | - |
| [Molecular representation learning with language models and domain-relevant auxiliary tasks](https://arxiv.org/abs/2011.13230) | arXiv | Nov 26, 2020 | [code](https://github.com/BenevolentAI/MolBERT) |


### 2.3 Controlled Molecule Optimization and Editing
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Leveraging language model for advanced multiproperty molecular optimization via prompt engineering](https://www.nature.com/articles/s42256-024-00916-5) | Nature Machine Intelligence | Oct 21, 2024 | [code](https://github.com/wzxxxx/Prompt-MolOpt) |
| [Small molecule optimization with large language models](https://arxiv.org/abs/2407.18897) | arXiv | Jul 26, 2024 | [code](https://github.com/yerevann/chemlactica) |
| [Lico: Large language models for in-context molecular optimization](https://openreview.net/forum?id=yu1vqQqKkx) | ICLR 2025 | Jun 27, 2024 | [code](https://github.com/tung-nd/LICO) |
| Not just another molecule generator: Artificial intelligence in drug discovery | TBA | TBA | - |
| [MolT5: Translation between Molecules and Natural Language](https://arxiv.org/abs/2204.11817) | EMNLP 2022 | Apr 25, 2022 | [code](https://github.com/blender-nlp/MolT5) |
| [Mollm: Multi-objective large language model for molecular design–optimizing with experts](https://arxiv.org/html/2502.12845v1) | arXiv | Feb 18, 2025 | - |
| [Drugassist: A large language model for molecule optimization](https://academic.oup.com/bib/article/26/1/bbae693/7942355) | Briefings in Bioinformatics | Dec 28, 2023 | [code](https://github.com/blazerye/DrugAssist) |


### 2.4 Chemical Reaction Prediction and Synthesis Planning
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Retrosynthetic Reaction Prediction Using Neural Sequence-to-Sequence Models](https://pubs.acs.org/doi/10.1021/acscentsci.7b00303) | ACS Central Science | Sep 5, 2017 | [code](https://github.com/pandegroup/reaction_prediction_seq2seq) |
| [Mapping the space of chemical reactions using attention-based neural networks](https://www.nature.com/articles/s42256-020-00284-w) | Nature Machine Intelligence | Jan 28, 2021 | [code](https://rxn4chemistry.github.io/rxnfp/) |
| [State-of-the-art augmented NLP transformer models for direct and single-step retrosynthesis](https://www.nature.com/articles/s41467-020-19266-y) | Nature Communications | Nov 04, 2020 | [code](https://github.com/bigchem/synthesis) |
| [Bridging chemistry and artificial intelligence by a reaction description language](https://www.nature.com/articles/s42256-025-01032-8) | Nature Machine Intelligence | May 13, 2025 | [code](https://github.com/jiachengxiong/ReactSeq) |
| [Reactgpt: Understanding of chemical reactions via in-context tuning](https://ojs.aaai.org/index.php/AAAI/article/view/31983) | AAAI 2025 | Apr 11, 2025 | - |



### 2.5 Multi-Modal LLMs and Chemistry-Focused Agents
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [ChemCrow: Augmenting large-language models with chemistry tools](https://www.nature.com/articles/s42256-024-00832-8) | Nature Machine Intelligence | May 08, 2024 | [code](https://github.com/ur-whitelab/chemcrow-runs) |
| [Molx: Enhancing large language models for molecular learning with a multi-modal extension](https://arxiv.org/abs/2406.06777) | arXiv | Jun 10, 2024 | [code](https://github.com/ur-whitelab/chemcrow-runs) |
| [Git-mol: A multi-modal large language model for molecular science with graph, image, and text](https://www.sciencedirect.com/science/article/pii/S0010482524001574) | Computers in Biology and Medicine | Feb 6, 2024 | [code](https://github.com/AI-HPC-Research-Team/GIT-Mol) |
| [Token-mol 1.0: tokenized drug design with large language models](https://www.nature.com/articles/s41467-025-59628-y) | Nature Communications | May 13, 2024 | [code](https://github.com/jkwang93/Token-Mol) |
| [Uni-mol: A universal 3d molecular representation learning framework](https://openreview.net/forum?id=6K2RM6wVqKu) | ICLR 2023 | Feb 27, 2023 | [code](https://github.com/deepmodeling/Uni-Mol) |
| [BioGPT: Generative pre-trained transformer for biomedical text generation and mining](https://academic.oup.com/bib/article/23/6/bbac409/6713511) | Briefings in Bioinformatics | Feb 27, 2023 | [code](https://github.com/microsoft/BioGPT) |
| [Multi-modal representation learning for molecular property prediction: sequence, graph, geometry](https://arxiv.org/abs/2401.03369) | arXiv | Jan 9, 2024 | [code](https://github.com/Vencent-Won/SGGRL) |
| [Instructmol: Multi-modal integration for building a versatile and reliable molecular assistant in drug discovery](https://aclanthology.org/2025.coling-main.25/) | COLING 2025 | Dec 19, 2024 | [code](https://github.com/IDEA-XL/InstructMol) |
| [Incorporating molecular knowledge in large language models via multimodal modeling](https://aclanthology.org/2025.coling-main.25/) | IEEE Transactions on Computational Social Systems | Jan 13, 2025 | [code](https://github.com/IDEA-XL/InstructMol) |
| MoleculeScribe: describing and designing molecules with multi-modal large language models | TBA | TBA | - |
| [Text-augmented multimodal llms for chemical reaction condition recommendation](https://arxiv.org/abs/2407.15141) | arXiv | Jul 21, 2024 | [code](https://github.com/IDEA-XL/InstructMol) |
| [ChemToolAgent: The impact of tools on language agents for chemistry problem solving](https://arxiv.org/abs/2411.07228) | arXiv | Nov 11, 2024 | [code](https://github.com/OSU-NLP-Group/ChemToolAgent) |
| [Chemagent: Self-updating memories in large language models improves chemical reasoning](https://openreview.net/forum?id=kuhIqeVg0e) | ICLR 2025 | Mar 12, 2025 | [code](https://github.com/gersteinlab/ChemAgent) |
| [Chemthinker: Thinking like a chemist with multi-agent llms for deep molecular insights](https://openreview.net/forum?id=zlAUnwhE2v) | arXiv | Sep 28, 2024 | - |





## 3. MLLMs for Protein

### 3.1 LLMs related work

### 3.2 MLLMs related work
#### 3.2.1 Protein Sequence-Language Integration
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [A Text-guided Protein Design Dramework.](https://www.nature.com/articles/s42256-025-01011-z) | Nature Machine Intelligence | Mar 27, 2025 | [code](https://github.com/chao1224/ProteinDT) |
| [ProtT3: Protein-to-Text Generation for Text-based Protein Understanding.](https://aclanthology.org/2024.acl-long.324/) | ACL | May 21, 2024 | [code](https://github.com/acharkq/ProtT3) |
| [ProtCLIP: Function-Informed Protein Multi-Modal Learning.](https://ojs.aaai.org/index.php/AAAI/article/view/34456/36611) | AAAI | Dec 28, 2024 | [code](https://github.com/diaoshaoyou/ProtCLIP) |
| [OntoProtein: Protein Pretraining With Gene Ontology Embedding.](https://arxiv.org/abs/2201.11147) | ICLR | Jan 23, 2022 | [code](https://github.com/zjunlp/OntoProtein) |
| [BioMedGPT: Open Multimodal Generative Pre-trained Transformer for BioMedicine.](https://arxiv.org/abs/2308.09442) | arXiv | Aug 18, 2023 | - |
| [ProtLLM: An Interleaved Protein-Language LLM with Protein-as-Word Pre-Training.](https://arxiv.org/abs/2403.07920) | arXiv | Feb 28, 2024 | [code](https://github.com/ProtLLM/ProtLLM) |
| [ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing.](https://arxiv.org/abs/2402.16445) | arXiv | Feb 26, 2024 | [code](https://github.com/PKU-YuanGroup/ProLLaMA) |
| [InstructProtein: Aligning Human and Protein Language via Knowledge Instruction.](https://aclanthology.org/2024.acl-long.62/) | ACL | Aug, 2024 | [code](https://github.com/HICAI-ZJU/InstructProtein) |
| [ESM-AA: Multi-scale Protein Language Model for Unified Molecular Modeling.](https://arxiv.org/abs/2403.12995) | ICML | Mar 20, 2024 | [code](https://github.com/zhengkangjie/ESM-AA) |
| [BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations.](https://aclanthology.org/2023.emnlp-main.70.pdf) | EMNLP | Dec 2023 | [code](https://github.com/QizhiPei/BioT5) |
| [BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning.](https://aclanthology.org/2024.findings-acl.71/) | Findings of ACL | Aug 2024 | [code](https://github.com/QizhiPei/BioT5) |
| [Galactica: A Large Language Model for Science.](https://arxiv.org/abs/2211.09085) | arXiv | Nov 16, 2022 | [code](https://github.com/paperswithcode/galai) |




#### 3.2.2 Protein Structure-Sequence-Language Integration
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Simulating 500 Million Years of Evolution with a Language Model.](https://www.science.org/doi/10.1126/science.ads0018) | Science | Jan 16, 2025 | - |
| [Adapting protein language models for structure-conditioned design.](https://www.biorxiv.org/content/10.1101/2024.08.03.606485v1) | bioRXiv | Aug 3, 2024 | [code](https://github.com/Profluent-AI/proseLM-public) |
| [SaProt: Protein Language Modeling with Structure-Aware Vocabulary](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v3) | bioRXiv | Oct 1, 2023 | [code](https://github.com/westlake-repl/SaProt) |
| [FoldToken: Learning Protein Language via Vector Quantization and Beyond.](https://arxiv.org/abs/2403.09673) | arXiv | Feb 4, 2024 | [code](https://github.com/A4Bio/FoldToken_open) |
| [Decoding the Molecular Language of Proteins with Evola.](https://www.biorxiv.org/content/10.1101/2025.01.05.630192v1) | biRXiv | Jan 5, 2025 | - |
| [DPLM-2: A Multimodal Diffusion Protein Language Model.](https://arxiv.org/abs/2410.13782) | arXiv | Oct 17, 2024 | [code](https://github.com/bytedance/dplm) |
| [ProTokens: A Machine-Learned Language for Compact and Informative Encoding of Protein 3D Structures.](https://www.biorxiv.org/content/10.1101/2023.11.27.568722v2) | bioRXiv | Nov 27, 2023 | - |
| [ProSST: Protein Language Modeling with Quantized Structure and Disentangled Attention.](https://www.biorxiv.org/content/10.1101/2024.04.15.589672v2) | bioRXiv | Apr 15, 2024 | [code](https://github.com/openmedlab/ProSST) |
| [ProteinGPT: Multimodal LLM for Protein Property Prediction and Structure Understanding.](https://arxiv.org/abs/2408.11363) | arXiv | Aug 21, 2024 | [code](https://github.com/OviaLabs/ProteinGPT) |
| [ProtChatGPT: Towards Understanding Proteins with Large Language Models.](https://arxiv.org/abs/2402.09649) | arXiv | Feb 15, 2024 | - |
| [STELLA: Towards Protein Function Prediction with Multimodal LLMs Integrating Sequence-Structure Representations.](https://arxiv.org/abs/2506.03800) | arXiv | Jun 4, 2025 | - |
| [Advancing biomolecular understanding and design following human instructions.](https://arxiv.org/abs/2410.07919) | arXiv | Oct 10, 2024 | [code](https://github.com/HICAI-ZJU/InstructBioMol) |
#### 3.2.3 Protein Interactions and Specialized Application
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [BioBridge: Bridging Biomedical Foundation Models via Knowledge Graphs.](https://arxiv.org/abs/2310.03320) | arXiv | Oct 5, 2023 | [code](https://github.com/RyanWangZf/BioBridge) |
| [MolBind: Multimodal Alignment of Language, Molecules, and Proteins.](https://arxiv.org/abs/2403.08167) | ariXiv | Mar 13, 2024 | [code](https://github.com/amelie-iska/MolBind) |
| [Large language and protein assistant for protein-protein interactions prediction.](https://aclanthology.org/2025.acl-long.554.pdf) | ACL | 2025 | [code](https://github.com/HHW-zhou/LLAPA) |
| [Multilingual translation for zero-shot biomedical classification using BioTranslato.](https://www.nature.com/articles/s41467-023-36476-2) | Nature Communications | Feb 10, 2023 | [code](https://github.com/HanwenXuTHU/BioTranslatorProject) |
---

## 4. MLLMs for Material


### 4.1 LLMs-Related Work
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Crystal Structure Generation with Autoregressive Large Language Modeling](https://arxiv.org/abs/2307.04340) | arXiv | Jul 10, 2023 | [code](https://github.com/lantunes/CrystaLLM) |
| [Fine-Tuned Language Models Generate Stable Inorganic Materials as Text](https://arxiv.org/abs/2402.04379) | arXiv | Feb 6, 2024 | [code](https://github.com/facebookresearch/crystal-text-llm) |
| [FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions](https://arxiv.org/abs/2410.23405) | arXiv | Oct 30, 2024 | [code](https://github.com/facebookresearch/flowmm) |
| [Invariant Tokenization of Crystalline Materials for Language Model Enabled Generation](https://openreview.net/forum?id=18FGRNd0wZ) | NeurIPS 2024 | Sep 25, 2024 | [code](https://github.com/divelab/AIRS/tree/main/OpenMat/Mat2Seq) |
| [LLMatDesign: Autonomous Materials Discovery with Large Language Models](https://arxiv.org/abs/2406.13163) | arXiv | Jun 19, 2024 | [code](https://github.com/Fung-Lab/LLMatDesign) |
| [MechGPT, a Language-Based Strategy for Mechanics and Materials Modeling That Connects Knowledge Across Scales, Disciplines, and Modalities](https://arxiv.org/abs/2310.10445) | arXiv | Oct 16, 2023 | - |
| [Leveraging Large Language Models for Explaining Material Synthesis Mechanisms: The Foundation of Materials Discovery](https://arxiv.org/html/2407.08922v1) | NeurIPS 2024 AI4Mat Workshop | Jul 12, 2024 | [code](https://github.com/Dandelionym/llm_for_mechanisms) |
| [Large language models for material property predictions: elastic constant tensor prediction and materials design](https://arxiv.org/abs/2411.12280) | arXiv | Nov 19, 2024 | [code](https://github.com/Grenzlinie/ElaTBot) |
| [MaScQA: investigating materials science knowledge of large language models](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d3dd00188a) | Digital Discovery | Dec 20, 2023 | [code](https://github.com/M3RG-IITD/MaScQA) |
| [Large-language models: The game-changers for materials science research](https://www.sciencedirect.com/science/article/pii/S2949747724000344) | Artificial Intelligence Chemistry | Aug 2024 | - |
| [Material transformers: deep learning language models for generative materials design](https://ui.adsabs.harvard.edu/abs/2023MLS%26T...4a5001F/abstract) | Machine Learning: Science and Technology | Jan 5, 2023 | [code](https://github.com/usccolumbia/mtransformer) |
| [LLaMP: Large Language Model Made Powerful for High-fidelity Materials Knowledge Retrieval and Distillation](https://arxiv.org/abs/2401.17244) | arXiv | Jan 30, 2024 | [code](https://github.com/chiang-yuan/llamp) |
| [34 Examples of LLM Applications in Materials Science and Chemistry: Towards Automation, Assistants, Agents, and Accelerated Scientific Discovery](https://arxiv.org/abs/2505.03049) | arXiv | May 5, 2025 | [code](https://llmhackathon.github.io/projects/) |
| [Reflections from the 2024 Large Language Model (LLM) Hackathon for Applications in Materials Science and Chemistry](https://arxiv.org/abs/2411.15221) | arXiv | Nov 20, 2024 | [code](https://llmhackathon.github.io/projects/) |
| [AtomAgents: Alloy design and discovery through physics-aware multi-modal multi-agent artificial intelligence](https://arxiv.org/abs/2407.10022) | arXiv | Jul 13, 2024 | [code](https://github.com/lamm-mit/AtomAgents) |
| [From Tokens to Materials: Leveraging Language Models for Scientific Discovery](https://arxiv.org/abs/2410.16165) | arXiv | Oct 21, 2024 | [code](https://github.com/MasterAI-EAM/MatEmbedding) |
| [Accelerating scientific discovery with generative knowledge extraction, graph-based representation, and multimodal intelligent graph reasoning](https://arxiv.org/abs/2403.11996) | arXiv | Mar 18, 2024 | [code](https://github.com/lamm-mit/GraphReasoning) |
| [MatExpert: Decomposing Materials Discovery by Mimicking Human Experts](https://arxiv.org/abs/2410.21317) | arXiv | Oct 26, 2024 | [code](https://github.com/BangLab-UdeM-Mila/MatExpert) |
| [Evaluating the performance and robustness of LLMs in materials science Q&A and property predictions](https://arxiv.org/abs/2409.14572) | arXiv | Sep 22, 2024 | - |




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


### 5.2 MLLMs Related Work
|  Title  |   Category  |   Venue  |   Date   |   Code   |
|:--------|:----------:|:--------:|:--------:|:--------:|
| [GeneChat](https://www.biorxiv.org/content/10.1101/2025.06.05.658031v1) | Function Prediction | bioRxiv | Jun 5, 2025 | [code](https://github.com/Shashi-Sekar/GeneChat) |
| [ChatNT](https://www.nature.com/articles/s42256-025-01047-1) | Multi-task | Nature Machine Intelligence | Jun 6, 2025 | [code](https://huggingface.co/InstaDeepAI/ChatNT) |
| [LLaMA-Gene](https://arxiv.org/abs/2412.00471) | Multi-task | arXiv | Nov 30, 2024 | [code](https://github.com/maris205/llama-gene) |
| [OmniCellTOSG](https://arxiv.org/abs/2504.02148) | Multi-task | arXiv | Apr 2, 2025 | [code](https://github.com/FuhaiLiAiLab/OmniCellTOSG) |
| [Geneverse](https://arxiv.org/abs/2406.15534) | Multi-task | arXiv | Jul 21, 2024 | [code](https://github.com/HelloWorldLTY/Geneverse) |
| [GenoMAS](https://arxiv.org/abs/2507.21035) | Gene Expression Analysis | arXiv | Jul 8, 2025 | [code](https://github.com/GenomicsAI/GenoMAS) |
| [cGSA](https://arxiv.org/abs/2506.04303) | Gene Expression Analysis | arXiv | Jun 4, 2025 | - |
| [GTA](https://arxiv.org/abs/2410.01858) | Gene Expression Analysis | arXiv | Oct 2, 2024 | - |
| [LLM4GRN](https://arxiv.org/abs/2410.15828) | Regulatory | arXiv | Oct 21, 2024 | - |
| [GeneBERT](https://arxiv.org/abs/2110.05231) | Regulatory | arXiv | Oct 11, 2021 | - |
| [GeneCompass](https://www.biorxiv.org/content/10.1101/2023.09.26.559542v1) | Regulatory | bioRxiv | Sep 28, 2023 | [code](https://github.com/xCompass-AI/GeneCompass) |