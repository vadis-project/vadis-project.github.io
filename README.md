![logo](VADIS-logo_small.png).

Welcome to the homepage of the DFG-funded project **VAriable Detection, Interlinking and Summarization** (VADIS).

[News](#news) - [Project overview](#overview) - [Project results](#results) - [Advisory board](#board) - [Team](#team) - [Funding](#funding)

## <a name="news"></a> News

* VADIS 2 proposal submitted
* Public demo of the VADIS search [https://demo-vadis.gesis.org/](https://demo-vadis.gesis.org/).
* VADIS has been presented in the course "Data Science Techniques for Survey Researchers" at the GESIS Summer School in Survey Methodology in August 2023.
* The Shared Task [SV-Ident 2022: Survey Variable Identification in Social Science Publications](https://vadis-project.github.io/sv-ident-sdp2022/) organized by VADIS will run in co-location with the 3rd Workshop on Scholarly Document Processing at COLING 2022. 
* The VADIS team met for a first face2face meeting in Mannheim, October 29, 2021.

## <a name="overview"></a> Project overview
Nowadays there is a growing trend in many scientific disciplines to support researchers by providing enhanced information access through linking of publications and underlying datasets. Open Science encourages scientiﬁc practices in which all research data is interlinked and contextualized to enhance reproducibility and reusability of research results. Ideally, publications that report on a result of an empirical study should thus contain a direct link to the cited dataset and lead the reader directly to the research data that underlies the publication.

However, in practice, standards for referencing between primary text and the cited data and its variables are often missing. A recent user study conducted by GESIS reveals that researchers would considerably benefit from increased linking and semantic annotation of scientific publications. In addition, researchers also demand that data citations should include information at the right granular level of the cited data, thus facilitating the identification and verification of the part of data that actually supports a specific claim. Improving access to scientific publications along the FAIR best practices also requires semantic indexing of texts with salient entities and specific variables that make up the focus of the study – requirements which are rarely addressed today.

The **key vision behind VADIS is to allow for searching und using survey variables in context and thereby help to increase the reproducibility of research results**. We achieve this by combining text mining techniques and semantic web technologies that identify and exploit links between publications, their topics, and the specific variables that are covered in the surveys. These semantic links in scientific texts build the basis for the development of applications to give users better access to scientific literature such as passage search, summarization, and information retrieval.

To achieve this, **we will analyze and link variables in context by identifying references to survey variables within the full text of research literature, creating semantic links based on these references and making the resulting data available as Linked Open Data**. Next, we will develop data-driven profiles of survey variable on the basis of both context-independent and context-dependent metrics. Finally, we will improve the access to survey and literature by providing information on variables from surveys, the developed metrics as well as textual summaries of linked literature. As a result of this, our project will be able to provide improved access to research literature in the social sciences based on the seamless integration within existing infrastructures. To quantify the effectiveness of our framework we design several use case scenarios for a target group of researchers that will be implemented as interfaces for exploration and research. The improvements on information access from experts will be thoroughly investigated in a user study.

### Work packages

Overview of the Work Packages (WPs) of the VADIS project. The colors indicate the lead partners for each of the different WPs. 

![WPs of VADIS](VADIS-WPs.png)

## <a name="results"></a>Project results

### Software
- Public demo of the VADIS search [https://demo-vadis.gesis.org/](https://demo-vadis.gesis.org/).
- [Summarization](https://github.com/vadis-project/vadis_summarization_api)
- [Variable Search](https://demo-vadis.gesis.org/variable_search/)
- [VADIS Knowledge Graph](vadiskg.md)
- [Variable citation visualizer on VADIS KG](https://github.com/vadis-project/vadiskg-timeline)
- [Variable topic visualizer on VADIS KG](https://colab.research.google.com/drive/1jzLZGmxyga5ty24HBQGeX_VA8w8plELy?usp=sharing)

### Publications (project publications)

* Zielinski, A., Spolwind, C., & Kroll, H. (2024). Evaluating Local Explanations for Survey Variable Detection in Scientific Publications. Workshop on Scientific Document Understanding 2024. Conference on Artificial Intelligence 2024. [https://publica.fraunhofer.de/handle/publica/470257](https://publica.fraunhofer.de/handle/publica/470257) 
* Sotaro Takeshita, Simone Paolo Ponzetto, and Kai Eckert. GenGO: ACL Paper Explorer with Semantic Features. ACL 2024 System demonstration track [https://aclanthology.org/2024.acl-demos.12/](https://aclanthology.org/2024.acl-demos.12/)
* Tornike Tsereteli, Daniel Ruffinelli, and Simone Paolo Ponzetto. (Under Review) Enriching Social Science Research via Survey Item Linking.
* Kartal, Y. S., Shahid, M. A., Takeshita, S., Tsereteli, T., Zielinski, A., Zapilko, B., & Mayr, P. (2024). VADIS – a VAriable Detection, Interlinking and Summarization system. ECIR Demo Track. [2312.13423.pdf](https://arxiv.org/pdf/2312.13423.pdf)
* Sotaro Takeshita, Simone Paolo Ponzetto, and Kai Eckert. ROUGE-K: Do your summaries have keywords? *SEM 2024, Long Paper Award [https://aclanthology.org/2024.starsem-1.6/](https://aclanthology.org/2024.starsem-1.6/)
* Sotaro Takeshita, Tommaso Green, Ines Reinig, Kai Eckert and Simone Paolo Ponzetto. ACLSum: A New Dataset for Aspect-based Summarization of Scientific Publications. To appear at NAACL 2024 [https://aclanthology.org/2024.naacl-long.371/](https://aclanthology.org/2024.naacl-long.371/).
* Tornike Tsereteli and Simone Paolo Ponzetto. 2023. A Lexico-semantic System for Survey Variable Search. 9th International Conference on Computational Social Science.
* Sotaro Takeshita, Tommaso Green, Niklas Friedrich, Kai Eckert, and Simone Paolo Ponzetto. (2023). Cross-lingual extreme summarization of scholarly documents. International Journal on Digital Libraries (2023) [https://doi.org/10.1007/s00799-023-00373-2](https://doi.org/10.1007/s00799-023-00373-2)
* Tornike Tsereteli, Yavuz Selim Kartal, Simone Paolo Ponzetto, Andrea Zielinski, Kai Eckert, and Philipp Mayr. 2022. Overview of the SV-Ident 2022 Shared Task on Survey Variable Identification in Social Science Publications. Proceedings of the Third Workshop on Scholarly Document Processing. 2022. [https://aclanthology.org/2022.sdp-1.29/](https://aclanthology.org/2022.sdp-1.29/)
* Hövelmeyer, Alica, and Yavuz Selim Kartal. Varanalysis@ sv-ident 2022: Variable detection and disambiguation based on semantic similarity. Proceedings of the Third Workshop on Scholarly Document Processing. 2022. [https://aclanthology.org/2022.sdp-1.30/](https://aclanthology.org/2022.sdp-1.30/) 
* Kartal, Y. S., Takeshita, S., Tsereteli, T., Eckert, K., Kroll, H., Mayr, P., Ponzetto, S. P., Zapilko, B., & Zielinski, A. (2022). Towards Automated Survey Variable Search and Summarization in Social Science Publications (arXiv:2209.06804). [http://arxiv.org/abs/2209.06804](http://arxiv.org/abs/2209.06804)
* Sotaro Takeshita, Tommaso Green, Niklas Friedrich, Kai Eckert, and Simone Paolo Ponzetto. 2022. X-SCITLDR: cross-lingual extreme summarization of scholarly documents. In Proceedings of the 22nd ACM/IEEE Joint Conference on Digital Libraries (JCDL '22). Association for Computing Machinery, New York, NY, USA, Article 4, 1–12. [https://doi.org/10.1145/3529372.3530938](https://doi.org/10.1145/3529372.3530938)

### Workshops

**Kickoff workshop**

The kickoff workshop is planned to be on two afternoons in **September 23-24, 2021** (Thursday/Friday). 
All details about the workshop are here: [Schedule of the workshop](workshop2021.md).

**Final workshop**

The final workshop of VADIS will take place on **November 12, 2024**.
All details about the final worshop can be found here: [Schedule of the workshop](workshop2024.md).


## <a name="board"></a> Advisory board
- Sören Auer: TIB Hannover, Germany 
- Elizabeth Bishop: GESIS, Cologne, Germany  
- Jan Goebel: SOEP. Berlin, Germany
- Dirk Hovy: Bocconi University, Milano, Italy
- Florian Keusch: University of Mannheim, Germany
- Federico Nanni: the Alan Turing Institute, London, United Kingdom
- Franciska de Jong: University Utrecht, The Netherlands

## <a name="team"></a> Team
![Team](team.jpeg)

### Contact
Dr. [Philipp Mayr](https://philippmayr.github.io/), philipp.mayr@gesis.org

### Partners
- [GESIS](https://www.gesis.org/en/home) - Leibniz Institute for the Social Sciences, Benjamin Zapilko (PI), Philipp Mayr (PI), Yavuz Selim Kartal (PhD student), Ahsan Shahid (Developer)
- [University of Mannheim](https://www.uni-mannheim.de/en/), Simone Ponzetto (PI), Tornike Tsereteli (PhD student)
- [Stuttgart Media University](https://www.hdm-stuttgart.de/en), Kai Eckert (PI), Sotaro Takeshita (PhD student)
- [Fraunhofer Institute for Systems and Innovation Research ISI](https://www.isi.fraunhofer.de/en.html), Henning Kroll (PI), Andrea Zielinski (PI)

### Related Publications

1.	Boland, K., Ritze, D., Eckert, K., & Mathiak, B. (2012). Identifying references to datasets in publications. In International Conference on Theory and Practice of Digital Libraries (pp. 150-161). Springer, Berlin, Heidelberg. DOI: http://doi.org/10.1007/978-3-642-33290-6_17
2.	Lauscher, A., Glavaš, G., & Eckert, K. (2017). University of Mannheim@ CLSciSumm-17: Citation-based summarization of scientific articles using semantic textual similarity. In CEUR workshop proceedings (Vol. 2002, pp. 33-42). RWTH.
3.	Lauscher, A., Glavaš, G., Ponzetto, S. P., & Eckert, K. (2018a). Investigating the role of argumentation in the rhetorical analysis of scientific publications with neural multi-task learning models. In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing (EMNLP) (pp. 3326-3338). https://www.aclweb.org/anthology/D18-1370
4.	Lauscher, A., Glavaš, G., & Eckert, K. (2018b). Arguminsci: A tool for analyzing argumentation and rhetorical aspects in scientific writing. Proceedings of the 5th Workshop on Argument Mining (ArgMining@EMNLP 2018), pp. 22-28. https://www.aclweb.org/anthology/W18-5203/
5.	Nanni, F., Dietz, L., Faralli, S., Glavaš, G., & Ponzetto, S. P. (2016). Capturing interdisciplinarity in academic abstracts. D-lib magazine, 22(9/10). http://doi.org/10.1045/september2016-nanni
6.	Nanni, F., Ponzetto, S. P., & Dietz, L. (2017). Building entity-centric event collections. In 2017 ACM/IEEE Joint Conference on Digital Libraries (JCDL) (pp. 199-208). IEEE.
7.	Nanni, F., Ponzetto, S. P., & Dietz, L. (2018). Entity-aspect linking: providing fine-grained semantics of entities in context. In Proceedings of the 18th ACM/IEEE on Joint Conference on Digital Libraries (pp. 49-58).
8.	Zapilko, B., Boland, K., & Kern, D. (2018). A LOD backend infrastructure for scientific search portals. In European Semantic Web Conference (pp. 729-744). Springer, Cham.
9.	Zielinski, A., & Mutschke, P. (2017). Mining Social Science Publications for Survey Variables. In Proceedings of the Second Workshop on NLP and Computational Social Science (NLP+CSS), pp. 47-52. http://www.aclweb.org/anthology/W17-2907
10.	Zielinski, A., & Mutschke, P. (2018). Towards a Gold Standard Corpus for Variable Detection and Linking in Social Science Publications. In International Conference on Language Resources and Evaluation (LREC).

## <a name="funding"></a>Funding
This project is funded by the DFG in the program e-Research Technologies, [project number 448491925](https://gepris-extern.dfg.de/gepris/projekt/448491925), runtime 2021-2024.

