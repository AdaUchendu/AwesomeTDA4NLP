# Unveiling Topological Structures from Language: A Comprehensive Survey of Topological Data Analysis Applications in NLP

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Arxiv](https://img.shields.io/badge/Arxiv-2411.10298-blue)](https://arxiv.org/abs/2411.10298)


## Overview
The surge of data available on the internet has led to the adoption of various computational methods to analyze and extract valuable insights from this wealth of information. 
Among these, the field of Machine Learning (ML) has thrived by leveraging data to extract meaningful insights. However, ML techniques face notable challenges when dealing with real-world
data, often due to issues of imbalance, noise, insufficient labeling, and high dimensionality. To address these limitations, some researchers advocate for the adoption of Topological Data
Analysis (TDA), a statistical approach that discerningly captures the intrinsic shape of data despite noise. Despite its potential, TDA has not gained as much traction within the 
Natural Language Processing (NLP) domain compared to structurally distinct areas like computer vision. Nevertheless, a dedicated community of researchers has been exploring the application
of TDA in NLP, yielding **97 papers** we comprehensively survey in this paper. Our findings categorize these efforts into theoretical and non-theoretical approaches. Theoretical
approaches aim to explain linguistic phenomena from a topological viewpoint, while non-theoretical approaches merge TDA with ML features, utilizing diverse numerical representation techniques. 
We conclude by exploring the challenges and unresolved questions that persist in this niche field.

![PDF file](tda_flow.png)


## How to cite the Repo or Paper
```bibtex
@article{uchendu2024unveiling,
  title={Unveiling Topological Structures in Text: A Comprehensive Survey of Topological Data Analysis Applications in NLP},
  author={Uchendu, Adaku and Le, Thai},
  journal={arXiv preprint arXiv:2411.10298},
  year={2024},
  url={https://arxiv.org/abs/2411.10298} 
}
```

## Table of Content
- [Overview](#overview)
- [Paper List](#paper-list)
  - [1. Theoretical Approaches](#1-theoretical-approaches)
    - [1a. Topological Space](#1a-topological-space)
      - [Semantic Topological Space](#semantic-topological-space)
      - [Syntactic Topological Space](#syntactic-topological-space)
    - [1b. Topology of Topic Evolution](#1b-topology-of-topic-evolution)
    - [1c. Topological "Shape" of Words](#1c-topological-shape-of-words)
  - [2. Non-Theoretical Approaches](#2-non-theoretical-approaches)
    - [2a. TF-IDF](#2a-tf-idf)
    - [2b. Pre-trained Embeddings](#2b-pre-trained-embeddings)
      - [Word2Vec](#word2vec)
      - [GloVe](#glove)
      - [FastText](#fasttext)
      - [ELMo](#elmo)
      - [Transformers](#transformers)
    - [2c. Symbolic Representation](#2c-symbolic-representation)
    - [2d. Multi-Modal Representation](#2d-multi-modal-representation)

- [Tutorials](#tutorials)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---
## Paper List

### 1. Theoretical Approaches

#### 1a. Topological Space

#### **Semantic Topological Space**
- **Discover the semantic topology in high-dimensional data.** IJ Chiang. *Expert Systems with Applications 33.1: 256-262* (2007) [[link]](https://www.sciencedirect.com/science/article/pii/S0957417406001813?casa_token=AFDmORbTOd8AAAAA:pEQ4ynuDICBcDwKakBq25lknW-JbKasH4PdLPmQr5oWUudRBsvsGOvYmFU-3uzOYgqOqJ-q94A)
- **Semantic topology.** Jussi Karlgren, Martin Bohman, Ariel Ekgren, Gabriel Isheden, Emelie Kullmann, and David Nilsson. *Proceedings of the 23rd ACM International Conference on Conference on Information and Knowledge Management* (2014) [[link]](https://www.sciencedirect.com/science/article/pii/S0957417406001813?casa_token=AFDmORbTOd8AAAAA:pEQ4ynuDICBcDwKakBq25lknW-JbKasH4PdLPmQr5oWUudRBsvsGOvYmFU-3uzOYgqOqJ-q94A)
- **Context-aware profiling of concepts from a semantic topological space.** *Knowledge-Based Systems* (2017) [[link]](https://www.sciencedirect.com/science/article/pii/S0950705117302198?casa_token=QrpNgi3Cj70AAAAA:s3piMOcr2QevkQKvG5Y_6yB2AFMdGKUhfS7SoodRW7c_wh86BGcbld75GfAV6xQEQVzDDfTbew)
- **Computational topology in text mining.** Hubert Wagner, Paweł Dłotko, and Marian Mrozek. *Computational Topology in Image Context: 4th International Workshop.* (2012) [[link]](https://link.springer.com/chapter/10.1007/978-3-642-30238-1_8)

#### **Syntactic Topological Space**
- **Persistent topology of syntax.** Alexander Port, Iulia Gheorghita, Daniel Guth, John M Clark, Crystal Liang, Shival Dasu, and Matilde Marcolli. *Mathematics in Computer Science.* (2018) [[link]](https://link.springer.com/article/10.1007/s11786-017-0329-x) 
- **Topological analysis of syntactic structures.** Alexander Port, Taelin Karidi, and Matilde Marcolli. *Mathematics in Computer Science* (2022) [[link]](https://link.springer.com/article/10.1007/s11786-021-00520-5)
  

#### 1b. Topology of Topic Evolution
- **A simplified topological representation of text for local and global context.** Ishrat Rahman Sami and Katayoun Farrahi. *Proceedings of the 25th ACM International Conference on Multimedia.* (2017) [[link]](https://dl.acm.org/doi/abs/10.1145/3123266.3123330?casa_token=v3xCm-nq5ukAAAAA:B7FMsoEvD9_M5FrOJ6MHgqFzCj4KfHM2eAO2RQOh3V5dQeCKUUdck-QnciUl2FqpbdYPJFiEzTmE)
  

#### 1c. Topological “Shape” of Words
- **The shape of word embeddings: Quantifying non-isometry with topological data analysis.** Ondˇrej Draganov and Steven Skiena. *Findings of the Association for Computational Linguistics: EMNLP 2024.* (2024) [[link]](https://aclanthology.org/2024.findings-emnlp.705/)
- **The shape of words-topological structure in natural language data.** Stephen Fitz. *Topological, Algebraic, and Geometric Learning Workshops 2022.* (2022) [[link]](https://proceedings.mlr.press/v196/fitz22a.html)
- **Hidden holes: topological aspects of language models.** Stephen Fitz, Peter Romero, and Jiyan Jonas Schneider. *arXiv preprint arXiv:2406.05798.* (2024) [[link]](https://arxiv.org/pdf/2406.05798)
- **Linguistics from a topological viewpoint.** Rui Dong. *arXiv preprint arXiv:2403.15440.* (2024) [[link]](https://arxiv.org/abs/2403.15440)
- **An application of persistent homology and the graph theory to linguistics: The case of Tifinagh and Phoenician scripts.** Hajar Bouazzaoui, Mohamed Abdou Elomary, My Ismail Mamouni. *Statistics in Transition new series 22.3.* (2021) [[link]](https://web.archive.org/web/20220519112014id_/https://www.exeley.com/exeley/journals/statistics_in_transition/22/3/pdf/10.21307_stattrans-2021-031.pdf) 


### 2. Non-theoretical Approaches

#### 2a. TF-IDF
- **Persistent homology: An introduction and a new text representation for natural language processing.** Xiaojin Zhu. *IJCAI* (2013) [[link]](https://link.springer.com/chapter/10.1007/978-3-642-30238-1_8)
- **Text Classification via Topological Data Analysis.** Bendik Løvlie. *Master’s thesis, Norwegian University of Science and Technology (NTNU)* (2023) [[link]](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/3080989/no.ntnu%3Ainspera%3A142441053%3A34433481.pdf?sequence=1)
- **Movie genre detection using topological data analysis.** Pratik Doshi and Wlodek Zadrozny. *Statistical Language and Speech Processing: 6th International Conference, SLSP 2018* (2018) [[link]](https://link.springer.com/chapter/10.1007/978-3-030-00810-9_11)
- **Genre classification: A topological data analysis approach.** Kevin Shin. (2019) [[link]](https://github.com/kevin-shin/TopologyNLP)
- **Text Mining via Homology.** Blaž Sovdat. *Master's thesis, UNIVERSITY OF LJUBLJANA* (2016) [[link]](https://www.researchgate.net/profile/Blaz-Sovdat/publication/305993593_Text_Mining_via_Homology/links/57a8f8cc08ae0107eee71812/Text-Mining-via-Homology.pdf)
- **Topological data analysis for discourse semantics?** Ketki Savle, Wlodek Zadrozny, and Minwoo Lee. *Proceedings of the 13th International Conference on Computational Semantics-Student Papers* (2019) [[link]](https://aclanthology.org/W19-0605/)
- **Does the geometry of word embeddings help document classification?** Paul Michel, Abhilasha Ravichander, and Shruti Rijhwani. *Proceedings of the 2nd Workshop on Representation Learning for NLP.* (2017) [[link]](https://aclanthology.org/W17-2628/)
- **A topological collapse for document summarization.** Hui Guan, Wen Tang, Hamid Krim, James Keiser, Andrew Rindos, and Radmila Sazdanovic. *2016 IEEE 17th International Workshop on Signal Processing Advances in Wireless Communications (SPAWC).* (2016) [[link]](https://ieeexplore.ieee.org/abstract/document/7536867?casa_token=yPYmyL1A6qwAAAAA:aVh63dwqFeXTjDi8kXnAFYuwlNvjsYv10S0japLvS94ihs14-wo_1VCtZCBboPd2RTXhq4x4)
- **Topic detection in Twitter using topology data analysis.** Pablo Torres-Tramón, Hugo Hromic, and Bahareh Rahmanzadeh Heravi. *Current Trends in Web Engineering.* (2015) [[link]](https://link.springer.com/chapter/10.1007/978-3-319-24800-4_16)
- **Extractive text summarization using topological features.** Ankit Kumar and Apurba Sarkar. *International Workshop on Combinatorial Image Analysis.* (2022) [[link]](https://link.springer.com/chapter/10.1007/978-3-031-23612-9_7)
- **Novel topological shapes of model interpretability.** Hendrik Jacob van Veen. *TDA and Beyond at the 34th Conference on Neural Information Processing Systems (NeurIPS 2020).* (2020) [[link]](https://openreview.net/pdf?id=G-kWQ9WvBMq)
- **An introduction to a new text classification and visualization for natural language processing using topological data analysis.** Naiereh Elyasi and Mehdi Hosseini Moghadam. *arXiv preprint arXiv:1906.01726.* (2019) [[link]](https://arxiv.org/abs/1906.01726)
- **Topological data analysis of open-ended responses.** Bright Effah. *Ph.D. thesis, University of Cape Coast* (2017) [[link]](https://tspace.library.utoronto.ca/handle/1807/126591)
- **The shape of poems.** Lamis Maadarani and Sayonita Ghosh Hajra. *Sac State Scholars' Fall Poster Forum* (2020) [[link]](https://s3.amazonaws.com/na-st01.ext.exlibrisgroup.com/01CALS_USL/storage/alma/B9/EE/E1/5F/09/E1/D1/AD/9F/1D/2A/1A/7B/5F/1C/40/Maadarani_Lamis_FallPosterForum2019.pdf?response-content-type=application%2Fpdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20241130T212253Z&X-Amz-SignedHeaders=host&X-Amz-Expires=119&X-Amz-Credential=AKIAJN6NPMNGJALPPWAQ%2F20241130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=10d7cec232eba4cf1eb22800616c78c77838358a9dd8d72504751e620e96de6d)

#### 2b. Pre-trained Embeddings 
#### **Word2Vec**
- **Story trees: Representing documents using topological persistence.** Pantea Haghighatkhah, Antske Fokkens, Pia Sommerauer, Bettina Speckmann, and Kevin Verbeek. *Proceedings of the Thirteenth LREC 2022* (2022) [[link]](https://aclanthology.org/2022.lrec-1.258/)
- **Topological analysis of contradictions in text.** Xiangcheng Wu, Xi Niu, and Ruhani Rahman. *Proceedings of the 45th International ACM SIGIR.* (2022) [[link]](https://dl.acm.org/doi/abs/10.1145/3477495.3531881)
- **Comparison of word embeddings of unaligned audio and text data using persistent homology.** Zhandos Yessenbayev and Zhanibek Kozhirbayev. *International Conference on Speech and Computer.* (2022) [[link]](https://link.springer.com/chapter/10.1007/978-3-031-20980-2_59)
- **Use of riemannian distance metric to verify topological similarity of acoustic and text domains.** Zhandos Yessenbayev and Zhanibek Kozhirbayev. *International Conference on Artificial Neural Networks.* (2024) [[link]](https://link.springer.com/chapter/10.1007/978-3-031-72350-6_25)
- **An explainable topological search engine with giotto-tda.** Filip Cornell. *gtda-challenge-2020.* (2020) [[link]](https://github.com/giotto-ai/gtda-challenge-2020/blob/master/filco306/A_topological_search_engine.ipynb)
- **Topological analysis of averaged sentence embeddings.** Wesley J Holmes. *Master’s thesis, Wright State University.* (2020) [[link]](https://etd.ohiolink.edu/acprod/odb_etd/etd/r/1501/10?clear=10&p10_accession_num=wright1609351352688467)
- **Topological data analysis for word sense disambiguation.** Michael Rawson, Samuel Dooley, Mithun Bharadwaj, and Rishabh Choudhary. *arXiv preprint arXiv:2203.00565.* (2022) [[link]](https://arxiv.org/abs/2203.00565)
- **Local homology of word embeddings.** Tadas Tem{\v{c}}inas. *arXiv preprint arXiv:1810.10136.* (2018) [[link]](https://arxiv.org/abs/1810.10136)
- **Geometry of textual data augmentation: Insights from large language models.** Sherry JH Feng, Edmund MK Lai, and Weihua Li. *Electronics.* (2024) [[link]](https://www.mdpi.com/2079-9292/13/18/3781)
- **Con connections: Detecting fraud from abstracts using topological data analysis.** Sarah Tymochko, Julien Chaput, Timothy Doster, Emilie Purvine, Jackson Warley, and Tegan Emerson. *20th IEEE International Conference on Machine Learning and Applications (ICMLA).* (2021) [[link]](https://ieeexplore.ieee.org/abstract/document/9680219?casa_token=WQTnSEnBCPkAAAAA:NYNNH5Xfhxh1FfXeXMwwM8PmlypDpzdd9R7DncUInVRCkzMkGXiBJ_XzR575in8cn8alVJTY)
- **Topological data analysis on simple english wikipedia articles.** Matthew Wright and Xiaojun Zheng. *The PUMP Journal of Undergraduate Research.* (2020) [[link]](https://arxiv.org/abs/2007.00063)
- **Argumentative topology: Finding loop (holes) in logic.** Sarah Tymochko, Zachary New, Lucius Bynum, Emilie Purvine, Timothy Doster, Julien Chaput, and Tegan Emerson. *arXiv preprint arXiv:2011.08952.* (2020) [[link]](https://arxiv.org/pdf/2011.08952)
- **Prediction of disease type from topological features of time series.** Giovanni Petri and Antonio Leitao. *gtda-challenge-2020.* (2020) [[link]](https://github.com/giotto-ai/gtda-challenge-2020/blob/master/lordgrilo/symbolic-disease-prediction.ipynb)
- **Summary and distance between sets of texts based on topological data analysis.** Eduardo Paluzo Hidalgo, Rocío González Díaz, and Miguel Ángel Gutiérrez Naranjo. *arXiv preprint arXiv:1912.09253.* (2019) [[link]](https://arxiv.org/abs/1912.09253)
- **Detecting Narrative Shifts through Persistent Structures: A Topological Analysis of Media Discourse.** Mark M. Bailey, Mark I. Heiligman. *arXiv preprint arXiv:2506.14836.* (2025) [[link]](https://arxiv.org/pdf/2506.14836)

#### **GloVe**
- **Topological signature of 19th century novelists: Persistent homology in text mining.** Shafie Gholizadeh, Armin Seyeditabari, and Wlodek Zadrozny. *Big Data and Cognitive Computing* (2018) [[link]](https://www.mdpi.com/2504-2289/2/4/33)
- **A novel method of extracting topological features from word embeddings.** Shafie Gholizadeh, Armin Seyeditabari, and Wlodek Zadrozny. *arXiv preprint arXiv:2003.13074.* (2020) [[link]](https://arxiv.org/abs/2003.13074)
- **Topological interpretability for deep learning.** Adam Spannaus, Heidi A Hanson, Georgia Tourassi, and Lynne Penberthy. *Proceedings of the Platform for Advanced Scientific Computing Conference.* (2024) [[link]](https://dl.acm.org/doi/abs/10.1145/3659914.3659935?casa_token=Wy1AFtY9xYEAAAAA:1o0Yj0toy6mKpEYhOVvLxJMTEkr_csBtq7UeRX3kUkN08kfWh9O4B-L16FaaPRpcFjrjtz2dzXwx)
- **A note on argumentative topology: Circularity and syllogisms as unsolved problems.** Wlodek W Zadrozny. *arXiv preprint arXiv:2102.03874.* (2021) [[link]](https://arxiv.org/abs/2102.03874)
- **The Hidden Shape of Data: Topological Data Analysis for Anxiety Detection in Text.** Morgan Byers. *Ph.D. thesis, Texas State University.* (2021) [[link]](https://digital.library.txst.edu/server/api/core/bitstreams/bc96a6c7-7a67-4d30-b1c3-e8ebac22e33e/content)
- **Unsupervised geometric and topological approaches for cross-lingual sentence representation and comparison.** Shaked Haim Meirom and Omer Bobrowski. *Proceedings of the 7th Workshop on Representation Learning for NLP @ ACL 2022* (2022) [[link]](https://aclanthology.org/2022.repl4nlp-1.18/)
- **Abstraction, reasoning and deep learning: A study of the" look and say" sequence.** Wlodek W Zadrozny. *arXiv preprint arXiv:2109.12755.* (2021) [[link]](https://arxiv.org/abs/2109.12755)
- **Topological data analysis helps to improve accuracy of deep learning models for fake news detection trained on very small training sets.** Ran Deng and Fedor Duzhin. *Big Data and Cognitive Computing* (2022) [[link]](https://www.mdpi.com/2504-2289/6/3/74)
- **Network and topological analysis of scholarly metadata: A platform to model and predict collaboration.** Lance Novak. *Master’s thesis, Purdue University.* (2019) [[link]](https://www.proquest.com/docview/2827703668?fromopenview=true&pq-origsite=gscholar&sourcetype=Dissertations%20&%20Theses)

#### **FastText**
- **Topology of word embeddings: Singularities reflect polysemy.** Alexander Jakubowski, Milica Gasic, and Marcus Zibrowius. *Proceedings of the Ninth Joint Conference on Lexical and Computational Semantics* (2020) [[link]](https://aclanthology.org/2020.starsem-1.11/)
- **Analysis of word embeddings: A clustering and topological approach.** Jonas Folkvord Triki. *Master’s thesis, The University of Bergen.* (2021) [[link]](https://bora.uib.no/bora-xmlui/handle/11250/2769947)
- **An analysis of the effect of polysemy on the topology of the latent manifold.** Denis Shehu. *Master’s thesis, Eindhoven University of Technology.* (2024) [[link]](https://pure.tue.nl/ws/portalfiles/portal/333617770/Shehu_D.pdf)

#### **ELMo**
- **Con connections: Detecting fraud from abstracts using topological data analysis.** Sarah Tymochko, Julien Chaput, Timothy Doster, Emilie Purvine, Jackson Warley, and Tegan Emerson. *20th IEEE International Conference on Machine Learning and Applications (ICMLA).* (2021) [[link]](https://ieeexplore.ieee.org/abstract/document/9680219?casa_token=WQTnSEnBCPkAAAAA:NYNNH5Xfhxh1FfXeXMwwM8PmlypDpzdd9R7DncUInVRCkzMkGXiBJ_XzR575in8cn8alVJTY)


#### **Transformers**

*CLS*
- **Intrinsic dimension estimation for robust detection of ai-generated texts.** Eduard Tulchinskii, Kristian Kuznetsov, Laida Kushnareva, Daniil Cherniavskii, Sergey Nikolenko, Evgeny Burnaev, Serguei Barannikov, and Irina Piontkovskaya. *Advances in Neural Information Processing Systems.* (2024) [[link]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7baa48bc166aa2013d78cbdc15010530-Abstract-Conference.html)
- **Ai-generated text boundary detection with roft.** Laida Kushnareva, Tatiana Gaintseva, German Magai, Serguei Barannikov, Dmitry Abulkhanov, Kristian Kuznetsov, Eduard Tulchinskii, Irina Piontkovskaya, and Sergey Nikolenko. *1st Conference on Language Modeling (COLM).* (2024) [[link]](https://openreview.net/pdf?id=kzzwTrt04Z)
- **Estimating class separability of text embeddings with persistent homology.** Kostis Gourgoulias, Najah Ghalyan, Maxime Labonne, Sean Moran, Joseph Sabelja. *Transactions on Machine Learning Research.* (2024) [[link]](https://openreview.net/pdf?id=8DWrIMuLya)
- **Topobert: Exploring the topology of fine-tuned word representations.** Archit Rathore, Yichu Zhou, Vivek Srikumar, and Bei Wang. *Information Visualization* (2023) [[link]](https://journals.sagepub.com/doi/full/10.1177/14738716231168671?casa_token=dGPubl3-b60AAAAA%3AV_Kw4pv1WTJvjYCb-TzBZD3iR14yda6nG5Qh27DibQ6EeBpl0s_E6y_HGhxa1pBWFgSOrybOHygX)
- **Combining topological signature with text embeddings: Multi-modal approach to fake news detection.** Rachel Lavery, Anna Jurek-Loughrey, and Lu Bai. *35th Irish Signals and Systems Conference (ISSC)* (2024) [[link]](https://ieeexplore.ieee.org/abstract/document/10603336?casa_token=KudZzv9Ylz8AAAAA:RUcUL17eaT7Qq-DBQEN8NadxwSWdbZ0BDUitk0D5zBkah26UJ4Dgvh2r5np2sKbv02fK5lhY)
- **Persistence homology of tedtalk: Do sentence embeddings have a topological shape?** Shouman Das, Syed A Haque, and Md Iftekhar Tanveer. *arXiv preprint arXiv:2103.14131.* (2021) [[link]](https://arxiv.org/abs/2103.14131) 
- **Topic modeling with topological data analysis.** Ciarán Byrne, Danijela Horak, Karo Moilanen, and Amandla Mabona. *Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing.* (2022) [[link]](https://aclanthology.org/2022.emnlp-main.792/)
- **Short-PHD: Detecting Short LLM-generated Text with Topological Data Analysis After Off-topic Content Insertion.** Dongjun Wei, Minjia Mao, Xiao Fang, Michael Chau. *arXiv preprint arXiv:2504.02873* (2025) [[link]](https://arxiv.org/pdf/2504.02873)
- **Topological Data Analysis for Distinguishing Human-Written and AI-Generated Abstracts.** Ann Guilinger, Eli Best, Vinay Awasthi. *preprints.org* (2025) [[link]](https://www.preprints.org/manuscript/202505.0097/v1)
- **Topo Goes Political: TDA-Based Controversy Detection in Imbalanced Reddit Political Data.** Arvindh Arun, Karuna K Chandra, Akshit Sinha, Balakumar Velayutham, Jashn Arora, Manish Jain, Ponnurangam Kumaraguru. *Companion Proceedings of the ACM on Web Conference 2025.* (2025) [[link]](https://dl.acm.org/doi/abs/10.1145/3701716.3717535)


*Hidden*
- **Topformer: Topology-aware authorship attribution of deepfake texts with diverse writing styles.** Adaku Uchendu, Thai Le, and Dongwon Lee. *ECAI 2024.* (2024) [[link]](https://ebooks.iospress.nl/doi/10.3233/FAIA240647)
- **Applications of topological data analysis to natural language processing and computer vision.** Jason S Garcia. *Ph.D. thesis, Colorado State University.* (2022) [[link]](https://www.proquest.com/docview/2670154139?pq-origsite=gscholar&fromopenview=true&sourcetype=Dissertations%20&%20Theses)
- **Persistent topological features in large language models.** Yuri Gardinazzi, Giada Panerai, Karthik Viswanathan, Alessio Ansuini, Alberto Cazzaniga, and Matteo Biagetti. *ICML 2025* (2025) [[link]](https://arxiv.org/abs/2410.11042)
- **Topological interpretations of GPT-3.** Tianyi Sun and Bradley Nelson. *arXiv preprint arXiv:2308.03565* (2023) [[link]](https://arxiv.org/abs/2308.03565)
- **Bertops: Studying BERT representations under a topological lens.** Jatin Chauhan and Manohar Kaul. *International Joint Conference on Neural Networks (IJCNN).*  (2022) [[link]](https://ieeexplore.ieee.org/abstract/document/9891897?casa_token=buBPJ1znZcUAAAAA:nxoeTqub6wzYdMf1wNHz5fDxSRBWerUAsnivfCU_3pFnjweOSg5My0SLMrFad5J5w64llcNI)
- **Relative representations: Topological and geometric perspectives.** Alejandro García-Castellanos, Giovanni Luca Marchetti, Danica Kragic, and Martina Scolamiero. *arXiv preprint arXiv:2409.10967.* (2024) [[link]](https://arxiv.org/abs/2409.10967)
- **Local topology measures of contextual language model latent spaces with applications to dialogue term extraction.** Benjamin Matthias Ruppik, Michael Heck, Carel van Niekerk, Renato Vukovic, Hsien-chin Lin, Shutong Feng, Marcus Zibrowius, and Milica Gaši´c. *Proceedings of the 25th Meeting of the Special Interest Group on Discourse and Dialogue.* (2024) [[link]](https://aclanthology.org/2024.sigdial-1.31/)
- **The more polypersonal the better - A short look on space geometry of fine-tuned layers.** Sergei Kudriashov, Veronika Zykova, Angelina Stepanova, Jacob Raskind, and Eduard Klyshinsky. *International Conference on Neuroinformatics.* (2024) [[link]](https://publications.hse.ru/en/chapters/979170791)
- **A Green AI Methodology Based on Persistent Homology for Compressing BERT** Luis Balderas, Miguel Lastra, and José M. Benítez. *Applied Sciences.* (2025) [[link]](https://www.mdpi.com/2076-3417/15/1/390)
- **Topological Data Mapping of Online Hate Speech, Misinformation, and General Mental Health: A Large Language Model Based Study.** Alexander, Andrew, and Hongbin Wang. *arXiv preprint arXiv:2309.13098.* (2023) [[link]](https://arxiv.org/pdf/2309.13098) 


*Attention*
- **Artificial text detection via examining the topology of attention maps.** Laida Kushnareva, Daniil Cherniavskii, Vladislav Mikhailov, Ekaterina Artemova, Serguei Barannikov, Alexander Bernstein, Irina Piontkovskaya, Dmitri Piontkovski, and Evgeny Burnaev. *Proceedings of the 2021 EMNLP* (2021) [[link]](https://aclanthology.org/2021.emnlp-main.50/)
- **Acceptability judgements via examining the topology of attention maps.** Daniil Cherniavskii, Eduard Tulchinskii, Vladislav Mikhailov, Irina Proskurina, Laida Kushnareva, Ekaterina Artemova, Serguei Barannikov, Irina Piontkovskaya, Dmitri Piontkovski, and Evgeny Burnaev. *Findings of the Association for Computational Linguistics: EMNLP 2022.* (2022) [[link]](https://aclanthology.org/2022.findings-emnlp.7/)
- **Can BERT eat RuCola? Topological data analysis to explain.** Irina Proskurina, Ekaterina Artemova, and Irina Piontkovskaya. *Proceedings of the 9th Workshop on Slavic Natural Language Processing 2023 (SlavicNLP 2023).* (2023) [[link]](https://aclanthology.org/2023.bsnlp-1.15/)
- **Beyond words: A topological exploration of coherence in text documents.** Samyak Jain, Rishi Singhal, Sriram Krishna, Yaman K Singla, and Rajiv Ratn Shah. *The Second Tiny Papers Track at ICLR 2024.* (2024) [[link]](https://openreview.net/pdf?id=QJxVhljAyS)
- **Uncertainty estimation of transformers’ predictions via topological analysis of the attention matrices.** Elizaveta Kostenok, Daniil Cherniavskii, and Alexey Zaytsev. *arXiv preprint arXiv:2308.11295.* (2023) [[link]](https://arxiv.org/abs/2308.11295)
- **The topological bert: Transforming attention into topology for natural language processing.** Ilan Perez and Raphael Reinauer. *arXiv preprint arXiv:2206.15195.* (2022) [[link]](https://arxiv.org/abs/2206.15195)
- **Detecting out-of-distribution text using topological features of transformer-based language models.** Andres Pollano, Anupam Chaudhuri, and Anj Simmons. *The IJCAI-2024 AISafety Workshop.* (2024) [[link]](https://arxiv.org/abs/2311.13102)
- **Beyond simple averaging: Improving nlp ensemble performance with topological-data-analysis-based weighting.** Polina Proskura and Alexey Zaytsev. *IEEE 11th International Conference on Data Science and Advanced Analytics (DSAA)* (2024) [[link]](https://ieeexplore.ieee.org/abstract/document/10722805?casa_token=V6AqtXODPjkAAAAA:vuELpOVUlLEhX33fuEm-bdiuJKaSQq3ghwOo-nYmMQWUszBawm_D0DYsLPjvl5CDBNTPayI7) OR [[link]](https://arxiv.org/abs/2402.14184)
- **Vulnerability Detection via Topological Analysis of Attention Maps.** Pavel Snopov and Andrey Nikolaevich Golubinskiy. *arXiv preprint arXiv:2410.03470* (2024) [[link]](https://arxiv.org/pdf/2410.03470)
- **Topological data analysis for speech processing.** Eduard Tulchinskii, Kristian Kuznetsov, Daniil Cherniavskii, Serguei Barannikov, Sergey Nikolenko, and Evgeny Burnaev. *Proceedings of the Annual Conference of the International Speech Communication Association, INTERSPEECH.* (2023) [[link]](https://www.isca-archive.org/interspeech_2023/tulchinskii23_interspeech.pdf)
- **Dialogue term extraction using transfer learning and topological data analysis.** Renato Vukovic, Michael Heck, Benjamin Ruppik, Carel van Niekerk, Marcus Zibrowius, and Milica Gasic. *Proceedings of the 23rd Annual Meeting of the Special Interest Group on Discourse and Dialogue.* (2022) [[link]](https://aclanthology.org/2022.sigdial-1.53/)
- **Authorship Attribution by Attention Pattern of BERT with Topological Data Analysis and UMAP.** Wataru Sakurai, Masato Asano, Daisuke Imoto, Masakatsu Honma, and Kenji Kurosawa. *2025 International Conference on Artificial Intelligence in Information and Communication (ICAIIC).* (2025) [[link]](https://ieeexplore.ieee.org/abstract/document/10920755?casa_token=BFPmwK4v3scAAAAA:iwfpffUEe7Cbg26dEp6AuOHfgDb2Fj5A07XUi5vU1GPx8o34sdDXI7ccLl_A-NiFfZ4rW9W5)
- **Hallucination Detection in LLMs via Topological Divergence on Attention Graphs.** Alexandra Bazarova, Aleksandr Yugay, Andrey Shulga, Alina Ermilova, Andrei Volodichev, Konstantin Polev, Julia Belikova, Rauf Parchiev, Dmitry Simakov, Maxim Savchenko, Andrey Savchenko, Serguei Barannikov, Alexey Zaytsev. *arxiv preprint arXiv:2504.10063.* (2025) [[link]](https://arxiv.org/pdf/2504.10063)



#### 2c. Symbolic Representation
- **Tongue twisters detection in Ukrainian by using tda.** Iryna Yurchuk and Olga Gurnik. *CEUR Workshop Proceedings.* (2023) [[link]](https://ceur-ws.org/Vol-3396/paper13.pdf)
- **Topological structure of Ukrainian tongue twisters based on speech sound analysis.** Tetiana Kovaliuk, Iryna Yurchuk, and Olga Gurnik. *MoDaST-2024: 6th International Workshop on Modern Data Science Technologies.* (2024) [[link]](https://ceur-ws.org/Vol-3723/paper18.pdf)


#### 2d. Multi-Modal Representation
- **Topological data analysis of human vowels: Persistent homologies across representation spaces.** Guillem Bonafos, Jean-Marc Freyermuth, Pierre Pudlo, Samuel Tronçon, and Arnaud Rey. *arXiv preprint arXiv:2310.06508.* (2023) [[link]](https://arxiv.org/abs/2310.06508)
- **Dirichlet process mixture model based on topologically augmented signal representation for clustering infant vocalizations.** Guillem Bonafos, Clara Bourot, Pierre Pudlo, Jean-Marc Freyermuth, Laurence Reboul, Samuel
Tronçon, and Arnaud Rey. *Interspeech 2024.* (2024) [[link]](https://www.isca-archive.org/interspeech_2024/bonafos24_interspeech.pdf)
- **Towards emotion recognition: a persistent entropy application.** Rocio Gonzalez-Diaz, Eduardo Paluzo-Hidalgo, and José F Quesada. *Computational Topology in Image Context: 7th International Workshop, CTIC 2019.* (2019) [[link]](https://link.springer.com/chapter/10.1007/978-3-030-10828-1_8)
- **Emotion recognition in talking-face videos using persistent entropy and neural networks.** Eduardo Paluzo-Hidalgo, Rocio Gonzalez-Diaz, and Guillermo Aguirre-Carrazana. *Electronic Research Archive.* (2022) [[link]](https://www.aimspress.com/article/doi/10.3934/era.2022034)
- **Topological data analysis to engineer features from audio signals for depression detection.** ML Tlachac, Adam Sargent, Ermal Toto, Randy Paffenroth, and Elke Rundensteiner. *19th IEEE International Conference on Machine Learning and Applications (ICMLA).* (2020) [[link]](https://ieeexplore.ieee.org/abstract/document/9356319?casa_token=mo6k8UBExnkAAAAA:YZO16Xc-sysnNbPU2PkJB_sIpe8yta8qGYIjHMgAgk7Qpmi-pbMuTNnJ86G2pjiRiSLvNS3P)
- **Topology-enhanced machine learning for consonant recognition.** Y Zhu, P Feng, S Yi, Q Qu, and Z Yu. *Research Square.* (2024) [[link]](https://www.researchsquare.com/article/rs-3978261/v1)
- **Bridging Topological Persistence and Machine Learning for Music Information Retrieval.** Luca Sassone, Marco Manetti, Mattia G Bergomi, and Massimo Ferri. *Ph.D. thesis, Sapienza – University of Rome.* (2022) [[link]](https://www.dm.unibo.it/home/ferri/hm/tesi/tesiSassone.pdf)
- **Dynamical and topological tools for (modern) music analysis.** Mattia Giuseppe Bergomi. *Ph.D. thesis, Université Pierre et Marie Curie-Paris VI; Università degli studi (Milan, Italie).* (2015) [[link]](https://theses.hal.science/tel-01293602/)
- **Topological Signatures of Adversaries in Multimodal Alignments.** Minh Vu, Geigh Zollicoffer, Huy Mai, Ben Nebgen, Boian Alexandrov, Manish Bhattarai. *arXiv preprint arXiv:2501.18006.* (2025) [[link]](https://arxiv.org/pdf/2501.18006)


## Tutorials
- **A Tutorial on Topological Data Analysis in Text Mining.** Shafie Gholizadeh, Wlodek Zadrozny. *IEEE BigData 2020.* (2020) [[link]](https://bigdataieee.org/BigData2020/files/IEEE_BigData_2020_Tutorial5_TDA_Tutorial.pdf)
- **Topological Data Analysis in Natural Language Processing - A Tutorial.** Wlodek Zadrozny. *The International FLAIRS Conference Proceedings (FLAIRS-36).* (2023) [[link]](https://www.researchgate.net/publication/370838263_A_Tutorial_on_Topological_Data_Analysis_in_Natural_Language_Processing)


## Resources
To learn more about TDA techniques, libraries for implementing TDA in Python, R, etc., go to [FatemehTarashi's TDA repo](https://github.com/FatemehTarashi/awesome-tda) and [list of conferences and workshops](https://people.clas.ufl.edu/peterbubenik/conferences/)

## Contributing
We welcome contributions from the community. If you have a paper applying TDA in NLP tasks, please submit a pull request or open an issue.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---

## Contact
For any questions or inquiries, please contact [Adaku Uchendu](mailto:akuuche301@gmail.com) and [Thai Le](mailto:tle@iu.edu).
