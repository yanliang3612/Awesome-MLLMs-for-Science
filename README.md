# A Comprehensive Survey of Multimodal LLMs for Scientific Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<img src="src/logo.png" alt="logo">

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
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [UniRep: Unified Rational Protein Engineering with Sequence-based Deep Representation Learning](https://www.nature.com/articles/s41592-019-0598-1) | Nature Methods | Oct 21, 2019 | [code](https://github.com/churchlab/UniRep) |
| [ProtTrans: Towards Cracking the Language of Life’s Code Through Self-Supervised Deep Learning and High Performance Computing](https://arxiv.org/abs/2007.06225) | IEEE TPAMI | Jul 13, 2021 | [code](https://github.com/agemagician/ProtTrans) |
| [ESM: Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences](https://www.science.org/doi/10.1126/science.ade2574) | Science | Jan, 2023 | [code](https://github.com/facebookresearch/esm) |
| [MSA Transformer: Transformer Protein Language Models Are Unsupervised Structure Learners](https://www.biorxiv.org/content/10.1101/2021.02.12.430858v1) | bioRxiv | Feb 14, 2021 | [code](https://github.com/facebookresearch/esm/blob/main/esm/model/msa_transformer.py) |
| [TCR-BERT: Learning the Grammar of T-Cell Receptor Sequences with Self-Supervised Learning](https://www.biorxiv.org/content/10.1101/2021.11.18.469186v1) | bioRxiv | Nov 18, 2021 | [code](https://github.com/wukevin/tcr-bert) |
| [ProteinBERT: A Universal Deep-Learning Model of Protein Sequence and Function](https://pubmed.ncbi.nlm.nih.gov/35020807/) | Bioinformatics | Apr 12, 2022 | [code](https://github.com/nadavbra/protein_bert) |
| [AlphaFold2: Highly Accurate Protein Structure Prediction with Deep Learning](https://www.nature.com/articles/s41586-021-03819-2) | Nature | Jul 15, 2021 | [code](https://github.com/deepmind/alphafold) |
| [ESMFold: End-to-End Single-Sequence Protein Structure Prediction Using a Language Model](https://www.science.org/doi/10.1126/science.ade2574) | Science | Mar, 2023 | [code](https://github.com/facebookresearch/esm) |
| [ESM-IF1: Protein Sequence Design from Structure Using Inverse Folding Language Models](https://www.biorxiv.org/content/10.1101/2022.04.10.487779v1) | bioRxiv | Apr 10, 2022 | [code](https://github.com/facebookresearch/esm) |
| [GearNet: Geometric Graph Neural Network for Protein Representation Learning](https://arxiv.org/abs/2203.06125) | ICLR | Mar 11, 2022 | [code](https://github.com/DeepGraphLearning/GearNet) |
| [SaProt: Protein Language Modeling with Structure-Aware Tokens](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v1) | biRxiv | Oct 01, 2023 | [code](https://github.com/westlake-repl/SaProt) |
| [OntoProtein: Protein Pretraining with Ontology-based Knowledge](https://arxiv.org/abs/2201.11147) | ICLR | Jan 23 2022 | [code](https://github.com/zjunlp/OntoProtein) |
| [ProGen: Language Models of Protein Sequences at the Scale of Evolution Enable Accurate Structure and Function Prediction](https://www.nature.com/articles/s41587-022-01618-2) |  Nature Biotechnology | Jan 26, 2023 | [code](https://github.com/salesforce/progen) |
| [ProtGPT2: Deep Unsupervised Language Modeling for Protein Design](https://doi.org/10.1038/s41467-022-32007-7) | Nature Communications | Jul 27, 2022 | [code](https://github.com/nferruz/ProtGPT2) |
| [ProGen2: Exploring the Boundaries of Protein Language Models](https://arxiv.org/abs/2206.13517) | arXiv | Jun 27, 2022 | [code](https://github.com/salesforce/progen) |
| [IgLM: Infilling Language Models Enable Scalable Design of Antibodies](https://pubmed.ncbi.nlm.nih.gov/37909045/) | Cell | Nov 15, 2023 | [code](https://github.com/Graylab/IgLM) |
| [PALM-H3: Protein Language Model for Antibody Design and Optimization](https://www.nature.com/articles/s41467-024-50903-y) | Nature Communications | Aug 10, 2024 | [code](https://github.com/nyuolab/PALM-H3) |
### 3.2 MLLMs related work
#### 3.2.1 Protein Sequence-Language Integration
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [ProteinDT: A Text-guided Protein Design Framework](https://www.nature.com/articles/s42256-025-01011-z) | Nature Machine Intelligence | Mar 27, 2025 | [code](https://github.com/chao1224/ProteinDT) |
| [ProtT3: Protein-to-Text and Text-to-Protein Generation with Language Models](https://aclanthology.org/2024.acl-long.324/) | ACL | May 21, 2024 | [code](https://github.com/acharkq/ProtT3) |
| [ProtCLIP: Contrastive Language–Protein Pre-training for Protein Representation Learning](https://ojs.aaai.org/index.php/AAAI/article/view/34456/36611) | AAAI | Dec 28, 2024 | [code](https://github.com/diaoshaoyou/ProtCLIP) |
| [OntoProtein: Protein Pretraining with Ontology-based Knowledge](https://arxiv.org/abs/2201.11147) | ICLR | Jan 23, 2022 | [code](https://github.com/zjunlp/OntoProtein) |
| [BioMedGPT: A Generalist Vision–Language Foundation Model for Biomedical Tasks](https://arxiv.org/abs/2308.09442) | arXiv | Aug 18, 2023 | - |
| [ProtLLM: Large Language Models for Protein Representation and Reasoning](https://arxiv.org/abs/2403.07920) | arXiv | Feb 28, 2024 | [code](https://github.com/ProtLLM/ProtLLM) |
| [ProLLaMA: Protein Large Language Model for Sequence Understanding and Generation](https://arxiv.org/abs/2402.16445) | arXiv | Feb 26, 2024 | [code](https://github.com/PKU-YuanGroup/ProLLaMA) |
| [InstructProtein: Aligning Protein Language Models with Natural Language Instructions](https://aclanthology.org/2024.acl-long.62/) | ACL | Aug, 2024 | [code](https://github.com/HICAI-ZJU/InstructProtein) |
| [ESM-AA: Large Language Models for Amino Acid Sequence Modeling and Generation](https://arxiv.org/abs/2403.12995) | ICML | Mar 20, 2024 | [code](https://github.com/zhengkangjie/ESM-AA) |
| [BioT5: Pretrained Text-to-Text Transformer for Biomedical Natural Language Processing](https://aclanthology.org/2023.emnlp-main.70.pdf) | EMNLP | Dec, 2023 | [code](https://github.com/QizhiPei/BioT5) |
| [BioT5+: A Unified Text-to-Text Framework for Biomedical Natural Language Processing](https://aclanthology.org/2024.findings-acl.71/) | Findings of ACL | Aug, 2024 | [code](https://github.com/QizhiPei/BioT5) |
| [Galactica: A Large Language Model for Science](https://arxiv.org/abs/2211.09085) | arXiv | Nov 16, 2022 | [code](https://github.com/paperswithcode/galai) |



#### 3.2.2 Protein Structure-Sequence-Language Integration
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [ESM3: Simulating 500 Million Years of Protein Evolution with a Language Model](https://www.science.org/doi/10.1126/science.ads0018) | Science | Jan 16, 2025 | - |
| [ProseLM: Protein Structure and Sequence Language Model for Unified Protein Representation Learning](https://www.biorxiv.org/content/10.1101/2024.08.03.606485v1) | bioRXiv | Aug 3, 2024 | [code](https://github.com/Profluent-AI/proseLM-public) |
| [SaProt: Protein Language Modeling with Structure-aware Tokens](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v3) | bioRXiv | Oct 1, 2023 | [code](https://github.com/westlake-repl/SaProt) |
| [FoldToken: Learning Protein Fold Representations via Discrete Tokenization](https://arxiv.org/abs/2403.09673) | arXiv | Feb 4, 2024 | [code](https://github.com/A4Bio/FoldToken_open) |
| [EvoLa: Evolutionary Language Models for Protein Representation and Generation](https://www.biorxiv.org/content/10.1101/2025.01.05.630192v1) | biRXiv | Jan 5, 2025 | - |
| [DPLM-2: Diffusion Protein Language Models for Scalable Protein Design](https://arxiv.org/abs/2410.13782) | arXiv | Oct 17, 2024 | [code](https://github.com/bytedance/dplm) |
| [ProTokens: Structure-aware Tokenization for Protein Language Modeling](https://www.biorxiv.org/content/10.1101/2023.11.27.568722v2) | bioRXiv | Nov 27, 2023 | - |
| [ProSST: Protein Sequence-Structure Transformer for Unified Protein Modeling](https://www.biorxiv.org/content/10.1101/2024.04.15.589672v2) | bioRXiv | Apr 15, 2024 | [code](https://github.com/openmedlab/ProSST) |
| [ProteinGPT: Large Language Models for Protein Structure and Function Generation](https://arxiv.org/abs/2408.11363) | arXiv | Aug 21, 2024 | [code](https://github.com/OviaLabs/ProteinGPT) |
| [ProtChatGPT: A Large Language Model Framework for Protein Knowledge Understanding and Generation](https://arxiv.org/abs/2402.09649) | arXiv | Feb 15, 2024 | - |
| [STELLA: Structure-Enhanced Large Language Model for Protein Modeling](https://arxiv.org/abs/2506.03800) | arXiv | Jun 4, 2025 | - |
| [InstructBioMol: Instruction-Tuned Multimodal Language Models for Biomolecular Understanding](https://arxiv.org/abs/2410.07919) | arXiv | Oct 10, 2024 | [code](https://github.com/HICAI-ZJU/InstructBioMol) |
#### 3.2.3 Protein Interactions and Specialized Application
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [BioBridge: Bridging Biomedical Foundation Models via Knowledge Graphs for Multimodal Biological Understanding](https://arxiv.org/abs/2310.03320) | arXiv | Oct 5, 2023 | [code](https://github.com/RyanWangZf/BioBridge) |
| [MolBind: Multimodal Learning for Molecular Binding Prediction](https://arxiv.org/abs/2403.08167) | ariXiv | Mar 13, 2024 | [code](https://github.com/amelie-iska/MolBind) |
| [LLAPA: Large Language Models Meet Protein–Protein Interaction Prediction](https://aclanthology.org/2025.acl-long.554.pdf) | ACL | 2025 | [code](https://github.com/HHW-zhou/LLAPA) |
| [BioTranslator: Cross-modal Translation for Integrative Biomedical Representation Learning](https://www.nature.com/articles/s41467-023-36476-2) | Nature Communications | Feb 10, 2023 | [code](https://github.com/HanwenXuTHU/BioTranslatorProject) |
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
| Title | Venue | Date | Code |
|:--------|:--------:|:--------:|:--------:|
| [Multi-modal conditional diffusion model using signed distance functions for metal-organic frameworks generation](https://www.nature.com/articles/s41467-024-55390-9) | Nature Communications | Jul 5, 2024 | [code](https://github.com/parkjunkil/MOFFUSION) |
| [GenMS: Generative Hierarchical Materials Search](https://arxiv.org/abs/2409.06762) | NeurIPS 2024 | Sep 10, 2024 | - |
| [Probing the limitations of multimodal language models for chemistry and materials research](https://www.nature.com/articles/s43588-025-00836-3) | Nature Computational Science | Nov 25, 2024 | [code](https://github.com/lamalab-org/mac-bench) |
| [MatterChat: A Multi-Modal LLM for Material Science](https://arxiv.org/abs/2502.13107) | arXiv | Feb 18, 2025 | - |
| [LLM-Fusion: A Novel Multimodal Fusion Model for Accelerated Material Discovery](https://arxiv.org/abs/2503.01022) | AAAI 2025 Workshop (AI2ASE) | Mar 2, 2025 | - |
| [Multimodal Foundation Models for Material Property Prediction and Discovery](https://arxiv.org/abs/2312.00111) | Newton | Nov 30, 2023 | [code](https://github.com/vmoro1/multimat) |
| [Automating alloy design and discovery with physics-aware multimodal multiagent AI](https://www.pnas.org/doi/10.1073/pnas.2414074122) | PNAS | Jan 24, 2025 | [code](https://github.com/lamm-mit/AtomAgents) |
| [Multimodal Machine Learning for Materials Science: Discovery of Novel Li-Ion Solid Electrolytes](https://pubs.acs.org/doi/10.1021/acs.chemmater.4c02257) | Chemistry of Materials | Nov 29, 2024 | [code](https://github.com/shenggong1996/COSNet) |
| [TDCM25: A Multi-Modal Multi-Task Benchmark for Temperature-Dependent Crystalline Materials](https://openreview.net/forum?id=bNB5SQTqKL) | AI4Mat-ICLR 2025 | Mar 3, 2025 | [code](https://github.com/KurbanIntelligenceLab/TDCM25) |






## 5. MLLMs for Gene

### 5.1 LLMs-Related Work
|  Title  |   Category  |   Venue  |   Date   |   Code   |
|:--------|:----------:|:--------:|:--------:|:--------:|
| [GexMolGen: Cross-modal Generation of Hit-like Molecules via Large Language Model Encoding of Gene Expression Signatures](https://www.biorxiv.org/content/10.1101/2023.11.11.566725v4) | Gene Expression Analysis | Briefings in Bioinformatics | Nov 11, 2023 | [code](https://github.com/Bunnybeibei/GexMolGen) |
| [GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information](https://pubmed.ncbi.nlm.nih.gov/38341654/) | Gene QA | Bioinformatics | Feb 1, 2024 | [code](https://github.com/ncbi/GeneGPT) |
| [GeneT: Genetic Transformer for Rapid and Accurate Identification of Causative Variants in Rare Genetic Diseases](https://www.medrxiv.org/content/10.1101/2024.07.18.24310666v1) | Variant Discovery | medRxiv | Jul 18, 2024 | - |
| [A Large Language Model Framework for Literature-based Disease–Gene Association Prediction](https://pubmed.ncbi.nlm.nih.gov/39998433/) | Gene Prediction | Briefings in Bioinformatics | Nov 22, 2024 | – |
| [Cancer Gene Identification through Integrating Causal Prompting Large Language Model with Omics Data-Driven Causal Inference](https://academic.oup.com/bib/article/26/2/bbaf113/8071687) | Cancer Gene Discovery | Briefings in Bioinformatics | Mar 12, 2025 | – |
| [Qwendy: Gene Regulatory Network Inference Enhanced by Large Language Model and Transformer](https://www.biorxiv.org/content/10.1101/2025.02.22.639640v1) | Regulatory Inference | bioRxiv | Feb 22, 2025 | – |
| [FGeneBERT: Function-Driven Pre-trained Gene Language Model for Metagenomics](https://arxiv.org/abs/2402.16901) | Gene Function Prediction | arXiv | Feb 24, 2024 | – |
| [Integrating Unsupervised Language Model with Triplet Neural Networks for Protein Gene Ontology Prediction](https://pubmed.ncbi.nlm.nih.gov/36548439/) | Protein Function Prediction | Bioinformatics | Dec 22, 2022 | – |
| [GenoLLM: A Large Language Model Framework for Genomic Analysis and Reasoning](https://www.biorxiv.org/content/10.1101/2024.02.26.581496v1) | Multi-task | bioRxiv | Feb 26, 2024 | [code](https://github.com/Huatsing-Lau/GenoLLM) |
| [GenATator: De Novo Gene Annotation with DNA Language Models](https://openreview.net/forum?id=sla2edDxc3) | Gene Annotation | ICLR 2025 Workshop | Mar 5, 2025 | – |

### 5.2 MLLMs Related Work
|  Title  |   Category  |   Venue  |   Date   |   Code   |
|:--------|:----------:|:--------:|:--------:|:--------:|
| [GeneChat: A Multimodal Large Language Model for Gene Function Prediction and Biological Knowledge Discovery](https://www.biorxiv.org/content/10.1101/2025.06.05.658031v1) | Function Prediction | bioRxiv | Jun 5, 2025 | [code](https://github.com/Shashi-Sekar/GeneChat) |
| [ChatNT: A Multimodal Foundation Model for Nucleotide Sequence Understanding and Reasoning](https://www.nature.com/articles/s42256-025-01047-1) | Multi-task | Nature Machine Intelligence | Jun 6, 2025 | [code](https://huggingface.co/InstaDeepAI/ChatNT) |
| [LLaMA-Gene: Large Language Models for Interpretable Genomic Analysis](https://arxiv.org/abs/2412.00471) | Multi-task | arXiv | Nov 30, 2024 | [code](https://github.com/maris205/llama-gene) |
| [OmniCellTOSG: A Multimodal Large Language Model for Single-Cell Omics Reasoning and Generation](https://arxiv.org/abs/2504.02148) | Multi-task | arXiv | Apr 2, 2025 | [code](https://github.com/FuhaiLiAiLab/OmniCellTOSG) |
| [Geneverse: A Large Language Model Framework for Multimodal Genomics Reasoning](https://arxiv.org/abs/2406.15534) | Multi-task | arXiv | Jul 21, 2024 | [code](https://github.com/HelloWorldLTY/Geneverse) |
| [GenoMAS: A Multimodal Artificial Intelligence System for Gene Expression Analysis](https://arxiv.org/abs/2507.21035) | Gene Expression Analysis | arXiv | Jul 8, 2025 | [code](https://github.com/GenomicsAI/GenoMAS) |
| [cGSA: Context-aware Gene Set Analysis with Large Language Models](https://arxiv.org/abs/2506.04303) | Gene Expression Analysis | arXiv | Jun 4, 2025 | - |
| [GTA: Gene Transformer Architecture for Integrative Transcriptomic Analysis](https://arxiv.org/abs/2410.01858) | Gene Expression Analysis | arXiv | Oct 2, 2024 | - |
| [LLM4GRN: Large Language Models for Gene Regulatory Network Inference](https://arxiv.org/abs/2410.15828) | Regulatory | arXiv | Oct 21, 2024 | - |
| [GeneBERT: A Pretrained Model for Gene Regulatory Sequence Analysis](https://arxiv.org/abs/2110.05231) | Regulatory | arXiv | Oct 11, 2021 | - |
| [GeneCompass: Deciphering Gene Regulatory Networks with Foundation Models](https://www.biorxiv.org/content/10.1101/2023.09.26.559542v1) | Regulatory | bioRxiv | Sep 28, 2023 | [code](https://github.com/xCompass-AI/GeneCompass) |