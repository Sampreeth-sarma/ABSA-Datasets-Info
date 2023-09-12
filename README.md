# ABSA-Datasets-Info

This survey of datasets for aspect-based sentiment analysis was published at IJCNLP-AACL 2023: *[A Review of Datasets for Aspect-based Sentiment Analysis
](https://arxiv.org/pdf/2204.05232.pdf). Siva Uday Sampreeth Chebolu, Franck Dernoncourt, Nedim Lipka, Thamar Solorio. IJCNLP-AACL 2023*.

Aspect-based sentiment analysis (ABSA) is a natural language processing problem that requires analyzing user-generated reviews to determine: a) The target entity being reviewed, b) The high-level aspect to which it belongs, and c) The sentiment expressed toward the targets and the aspects. 
Numerous yet scattered corpora for ABSA make it difficult for researchers to identify corpora best suited for a specific ABSA subtask quickly. This repository provides a list of all the publicly available datasets for Aspect-based Sentiment Analysis along with the matching subtasks for each of the datasets. 

We provide the following information in the form of tables:
- [What are the exisiting subtasks of ABSA? What are the inputs and expected outputs of each Subtask and when it was introduced?](Tables/Subtasks-Info.md)
- [What are the publicly available datasets for ABSA without the aspect category annotations?](Tables/Datasets-without-Aspect-Categories.md)
- [What are the publicly available datasets for ABSA with the aspect category annotations?](Tables/Datasets-with-Aspect-Categories.md)
- [Which datasets could be used for which subtasks and which subtasks could be tackled using which datasets?](Tables/Datasets-Subtasks.md)

If you want to add any new tasks or datasets or change any information, please create a pull request, so that we can verify it and commit the change.

If you use our work in your research, please cite the following paper: 
[Survey of Aspect-based Sentiment Analysis Datasets](https://arxiv.org/abs/2204.05232)
```
@inproceedings{chebolu2023survey,
      title={Survey of Aspect-based Sentiment Analysis Datasets}, 
      author={Siva Uday Sampreeth Chebolu and Franck Dernoncourt and Nedim Lipka and Thamar Solorio},
      booktitle = "Proceedings of the 3rd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 13th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)",
      month = nov,
      year = "2023",
      publisher = "Association for Computational Linguistics"
}
```
