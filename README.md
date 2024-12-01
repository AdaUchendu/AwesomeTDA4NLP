# Unveiling Topological Structures in Text: A Comprehensive Survey of Topological Data Analysis Applications in NLP

## Overview
The surge of data available on the internet has led to the adoption of various computational methods to analyze and extract valuable insights from this wealth of information. 
Among these, the field of Machine Learning (ML) has thrived by leveraging data to extract meaningful insights. However, ML techniques face notable challenges when dealing with real-world
data, often due to issues of imbalance, noise, insufficient labeling, and high dimensionality. To address these limitations, some researchers advocate for the adoption of Topological Data
Analysis (TDA), a statistical approach that discerningly captures the intrinsic shape of data despite noise. Despite its potential, TDA has not gained as much traction within the 
Natural Language Processing (NLP) domain compared to structurally distinct areas like computer vision. Nevertheless, a dedicated community of researchers has been exploring the application
of TDA in NLP, yielding 87 papers we comprehensively survey in this paper. Our findings categorize these efforts into theoretical and non-theoretical approaches. Theoretical
approaches aim to explain linguistic phenomena from a topological viewpoint, while non-theoretical approaches merge TDA with ML features, utilizing diverse numerical representation techniques. 
We conclude by exploring the challenges and unresolved questions that persist in this niche field.

![PDF file](tda_flow.png)


## BibTex
```
@article{uchendu2024unveiling,
  title={Unveiling Topological Structures in Text: A Comprehensive Survey of Topological Data Analysis Applications in NLP},
  author={Uchendu, Adaku and Le, Thai},
  journal={arXiv preprint arXiv:2411.10298},
  year={2024},
  url={https://arxiv.org/abs/2411.10298}, 
}
```

## Table of Content
- [Overview](#overview)
- [Paper List](#paper-list)
  - [1. Theoretical Approaches](#1-theoretical-approaches)
    - [1a. Topological Space](#1a-topological-space)
    - [1b. Topology of Topic Evolution](#1b-topology-of-topic-evolution)
    - [1c. Topological "Shape" of Words](#1c-topological-shape-of-words)
  - [2. Non-Theoretical Approaches](#2-non-theoretical-approaches)
    - [2a. TF-IDF](#2a-tf-idf)
    - [2b. Pre-trained Embeddings](#2b-pre-trained-embeddings)
    - [2c. Symbolic Representation](#2c-symbolic-representation)
    - [2d. Multi-Modal Representation](#2d-multi-modal-representation)
    
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---
## Paper List

### 1. Theoretical Approaches

#### 1a. Topological Space

**Semantic Topological Space**
- **Discover the semantic topology in high-dimensional data.** IJ Chiang. *Expert Systems with Applications 33.1: 256-262* (2007) [[link]](https://www.sciencedirect.com/science/article/pii/S0957417406001813?casa_token=AFDmORbTOd8AAAAA:pEQ4ynuDICBcDwKakBq25lknW-JbKasH4PdLPmQr5oWUudRBsvsGOvYmFU-3uzOYgqOqJ-q94A)
- **Semantic topology.** Jussi Karlgren, Martin Bohman, Ariel Ekgren, Gabriel Isheden, Emelie Kullmann, and David Nilsson. *Proceedings of the 23rd ACM International Conference on Conference on Information and Knowledge Management* (2014) [[link]](https://www.sciencedirect.com/science/article/pii/S0957417406001813?casa_token=AFDmORbTOd8AAAAA:pEQ4ynuDICBcDwKakBq25lknW-JbKasH4PdLPmQr5oWUudRBsvsGOvYmFU-3uzOYgqOqJ-q94A)
- **Context-aware profiling of concepts from a semantic topological space.** *Knowledge-Based Systems* (2017) [[link]](https://www.sciencedirect.com/science/article/pii/S0950705117302198?casa_token=QrpNgi3Cj70AAAAA:s3piMOcr2QevkQKvG5Y_6yB2AFMdGKUhfS7SoodRW7c_wh86BGcbld75GfAV6xQEQVzDDfTbew)
- **Computational topology in text mining.** Hubert Wagner, Paweł Dłotko, and Marian Mrozek. *Computational Topology in Image Context: 4th International Workshop.* (2012) [[link]](https://link.springer.com/chapter/10.1007/978-3-642-30238-1_8)

**Syntactic Topological Space**
- **Persistent topology of syntax.** Alexander Port, Iulia Gheorghita, Daniel Guth, John M Clark, Crystal Liang, Shival Dasu, and Matilde Marcolli. *Mathematics in Computer Science.* (2018) [[link]](https://link.springer.com/article/10.1007/s11786-017-0329-x) 
- **Topological analysis of syntactic structures.** Alexander Port, Taelin Karidi, and Matilde Marcolli. *Mathematics in Computer Science* (2022) [[link]](https://link.springer.com/article/10.1007/s11786-021-00520-5)
  

#### 1b. Topology of Topic Evolution
- **A simplified topological representation of text for local and global context.** Ishrat Rahman Sami and Katayoun Farrahi. *Proceedings of the 25th ACM International Conference on Multimedia.* (2017) [[link]](https://dl.acm.org/doi/abs/10.1145/3123266.3123330?casa_token=v3xCm-nq5ukAAAAA:B7FMsoEvD9_M5FrOJ6MHgqFzCj4KfHM2eAO2RQOh3V5dQeCKUUdck-QnciUl2FqpbdYPJFiEzTmE)
  

#### 1c. Topological “Shape” of Words
- **The shape of word embeddings: Quantifying non-isometry with topological data analysis.** Ondˇrej Draganov and Steven Skiena. *Findings of the Association for Computational Linguistics: EMNLP 2024.* (2024) [[link]](https://aclanthology.org/2024.findings-emnlp.705/)
- **The shape of words-topological structure in natural language data.** Stephen Fitz. *Topological, Algebraic, and Geometric Learning Workshops 2022.* (2022) [[link]](https://proceedings.mlr.press/v196/fitz22a.html)
- **Hidden holes: topological aspects of language models.** Stephen Fitz, Peter Romero, and Jiyan Jonas Schneider. *arXiv preprint arXiv:2406.05798.* (2024) [[link]](https://arxiv.org/pdf/2406.05798)
- **Linguistics from a topological viewpoint.** Rui Dong. *arXiv preprint arXiv:2403.15440.* (2024) [[link]](https://arxiv.org/abs/2403.15440)

### 2. Non-theoretical Approaches

#### 2a. TF-IDF
- **Persistent homology: An introduction and a new text representation for natural language processing.** Xiaojin Zhu. *IJCAI* (2013) [[link]](https://link.springer.com/chapter/10.1007/978-3-642-30238-1_8)
- **Text Classification via Topological Data Analysis.** Bendik Løvlie. *Master’s thesis, Norwegian University of Science and Technology (NTNU)* (2023) [[link]](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/3080989/no.ntnu%3Ainspera%3A142441053%3A34433481.pdf?sequence=1)
- **Movie genre detection using topological data analysis.** Pratik Doshi and Wlodek Zadrozny. *Statistical Language and Speech Processing: 6th International Conference, SLSP 2018* (2018) [[link]](https://link.springer.com/chapter/10.1007/978-3-030-00810-9_11)
- **Genre classification: A topological data analysis approach.** Kevin Shin. (2019) [[link]](https://github.com/kevin-shin/TopologyNLP)
- **Topological data analysis for discourse semantics?** Ketki Savle, Wlodek Zadrozny, and Minwoo Lee. *Proceedings of the 13th International Conference on Computational Semantics-Student Papers* (2019) [[link]](https://aclanthology.org/W19-0605/)
- **Does the geometry of word embeddings help document classification?** Paul Michel, Abhilasha Ravichander, and Shruti Rijhwani. *Proceedings of the 2nd Workshop on Representation Learning for NLP.* (2017) [[link]](https://aclanthology.org/W17-2628/)
- **A topological collapse for document summarization.** Hui Guan, Wen Tang, Hamid Krim, James Keiser, Andrew Rindos, and Radmila Sazdanovic. *2016 IEEE 17th International Workshop on Signal Processing Advances in Wireless Communications (SPAWC).* (2016) [[link]](https://ieeexplore.ieee.org/abstract/document/7536867?casa_token=yPYmyL1A6qwAAAAA:aVh63dwqFeXTjDi8kXnAFYuwlNvjsYv10S0japLvS94ihs14-wo_1VCtZCBboPd2RTXhq4x4)
- **Topic detection in Twitter using topology data analysis.** Pablo Torres-Tramón, Hugo Hromic, and Bahareh Rahmanzadeh Heravi. *Current Trends in Web Engineering.* (2015) [[link]](https://link.springer.com/chapter/10.1007/978-3-319-24800-4_16)
- **Extractive text summarization using topological features.** Ankit Kumar and Apurba Sarkar. *International Workshop on Combinatorial Image Analysis.* (2022) [[link]](https://link.springer.com/chapter/10.1007/978-3-031-23612-9_7)
- **Novel topological shapes of model interpretability.** Hendrik Jacob van Veen. *TDA and Beyond at the 34th Conference on Neural Information Processing Systems (NeurIPS 2020).* (2020) [[link]](https://openreview.net/pdf?id=G-kWQ9WvBMq)
- **An introduction to a new text classification and visualization for natural language processing using topological data analysis.** Naiereh Elyasi and Mehdi Hosseini Moghadam. *arXiv preprint arXiv:1906.01726.* (2019) [[link]](https://arxiv.org/abs/1906.01726)
- **Topological data analysis of open-ended responses.** Bright Effah. *Ph.D. thesis, University of Cape Coast* (2017) [[link]](https://tspace.library.utoronto.ca/handle/1807/126591)
- **The shape of poems.** Lamis Maadarani and Sayonita Ghosh Hajra. *Sac State Scholars' Fall Poster Forum* [[link]](https://s3.amazonaws.com/na-st01.ext.exlibrisgroup.com/01CALS_USL/storage/alma/B9/EE/E1/5F/09/E1/D1/AD/9F/1D/2A/1A/7B/5F/1C/40/Maadarani_Lamis_FallPosterForum2019.pdf?response-content-type=application%2Fpdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20241130T212253Z&X-Amz-SignedHeaders=host&X-Amz-Expires=119&X-Amz-Credential=AKIAJN6NPMNGJALPPWAQ%2F20241130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=10d7cec232eba4cf1eb22800616c78c77838358a9dd8d72504751e620e96de6d)

#### 2b. Pre-trained Embeddings 
**Word2Vec**
- **Story trees: Representing documents using topological persistence.** Pantea Haghighatkhah, Antske Fokkens, Pia Sommerauer, Bettina Speckmann, and Kevin Verbeek. *Proceedings of the Thirteenth LREC 2022* (2022) [[link]](https://aclanthology.org/2022.lrec-1.258/)
- **Topological analysis of contradictions in text.** Xiangcheng Wu, Xi Niu, and Ruhani Rahman. *Proceedings of the 45th International ACM SIGIR.* (2022) [[link]](https://dl.acm.org/doi/abs/10.1145/3477495.3531881)
- **Comparison of word embeddings of unaligned audio and text data using persistent homology.** Zhandos Yessenbayev and Zhanibek Kozhirbayev. *International Conference on Speech and Computer.* (2022) [[link]](https://link.springer.com/chapter/10.1007/978-3-031-20980-2_59)
- **Use of riemannian distance metric to verify topological similarity of acoustic and text domains.** Zhandos Yessenbayev and Zhanibek Kozhirbayev. *International Conference on Artificial Neural Networks.* (2024) [[link]](https://link.springer.com/chapter/10.1007/978-3-031-72350-6_25)
- **An explainable topological search engine with giotto-tda.** Filip Cornell. *gtda-challenge-2020.* (2020) [[link]](https://github.com/giotto-ai/gtda-challenge-2020/blob/master/filco306/A_topological_search_engine.ipynb)
- **Topological analysis of aver- aged sentence embeddings.** Wesley J Holmes. *Master’s thesis, Wright State University.* [[link]](https://etd.ohiolink.edu/acprod/odb_etd/etd/r/1501/10?clear=10&p10_accession_num=wright1609351352688467)
- **Topological data analysis for word sense disambiguation.** Michael Rawson, Samuel Dooley, Mithun Bharadwaj, and Rishabh Choudhary. *arXiv preprint arXiv:2203.00565.* (2022) [[link]](https://arxiv.org/abs/2203.00565)
- **Local homology of word embeddings.** Tadas Tƒemˇcinas. *arXiv preprint arXiv:1810.10136.* (2018) [[link]](https://arxiv.org/abs/1810.10136)
- **Geometry of textual data augmentation: Insights from large language models.** Sherry JH Feng, Edmund MK Lai, and Weihua Li. *Electronics, 13(18):3781.* (2024) [[link]](https://www.mdpi.com/2079-9292/13/18/3781)
- **Con connections: Detecting fraud from abstracts using topological data analysis.** Sarah Tymochko, Julien Chaput, Timothy Doster, Emilie Purvine, Jackson Warley, and Tegan Emerson. *20th IEEE International Conference on Machine Learning and Applications (ICMLA).* (2020) [[link]](https://ieeexplore.ieee.org/abstract/document/9680219?casa_token=WQTnSEnBCPkAAAAA:NYNNH5Xfhxh1FfXeXMwwM8PmlypDpzdd9R7DncUInVRCkzMkGXiBJ_XzR575in8cn8alVJTY)
- **Topological data analysis on simple english wikipedia articles.** Matthew Wright and Xiaojun Zheng. *The PUMP Journal of Undergraduate Research, 3:308–328.* (2020) [[link]](https://arxiv.org/abs/2007.00063)
- **Summary and distance between sets of texts based on topological data analysis.** Eduardo Paluzo Hidalgo, Rocío González Díaz, and Miguel Ángel Gutiérrez Naranjo. *arXiv preprint arXiv:1912.09253.* (2019) [[link]](https://arxiv.org/abs/1912.09253)

**GloVe**

**FastText**

**ELMo**

**Transformers**


#### 2c. Symbolic Representation


#### 2d. Multi-Modal Representation



## Contributing
We welcome contributions from the community. If you have a paper applying TDA in NLP tasks, please submit a pull request or open an issue.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---

## Contact
For any questions or inquiries, please contact [Adaku Uchendu](mailto:akuuche301@gmail.com) and [Thai Le](mailto:tle@iu.edu).
