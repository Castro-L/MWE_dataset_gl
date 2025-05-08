# MWE_dataset_gl

# Description

This dataset comprises 240 noun-adjective multi-word expressions (MWEs) in Galician, which account for 322 different senses. For expressions and their constituents, we provide frequency, ambiguity, and productivity data. These expressions are contextualized in up to four examples that were extracted from corpora. Please note that there exist a shortage of around 6% of contexts, as no valid examples could be found in some instances.

Additionally, human judments on compositionality levels were obtained for all senses. Thus, mean compositionality scores for compounds, heads, and depedents are provided. These mean values come from 2 sets of ratings. We are currently increasing the number of ratings, which will also be released. The dataset can be found in dataset_noun_adj. More information about its contents can be found in information.txt. 

# Citation

If you use the expressions, senses, and sentences of this dataset, please cite the following [paper](https://link.springer.com/chapter/10.1007/978-3-031-73503-5_19):

```
@InProceedings{10.1007/978-3-031-73503-5_19,
author="Castro, Laura
and Temerko, Anna
and Garcia, Marcos",
editor="Santos, Manuel Filipe
and Machado, Jos{\'e}
and Novais, Paulo
and Cortez, Paulo
and Moreira, Pedro Miguel",
title="Compositionality and Ambiguity in Multiword Expressions: A Dataset for the Evaluation of Language Models in Galician",
booktitle="Progress in Artificial Intelligence",
year="2025",
publisher="Springer Nature Switzerland",
address="Cham",
pages="228--240",
abstract="This paper presents a new dataset of noun-adjective multiword expressions with different degrees of compositionality and semantic ambiguity in Galician. It is composed of 240 MWEs, which can convey one or different senses depending on the context. For each sense, a language expert manually created two sentences and selected from corpora four additional examples that included the target MWEs, thus resulting in a useful resource for exploring potential data contamination when evaluating language models. Each MWE in context was then classified as idiomatic, partially idiomatic, or compositional. Therefore, the dataset comprises MWEs with stable meanings, and two types of ambiguous expressions: 1) potential idiomatic expressions (e.g., red flag), and 2) polysemy-based ambiguous MWEs, whose various senses are due to the ambiguity of one of the constituent words (e.g., common noun as a type of noun or a noun that is common). To illustrate the potential of this resource, a comparison of three BERT models for Galician was performed, shedding light on the representation of ambiguous MWEs in Transformers. This is a valuable resource for evaluating the semantic capabilities of current language models in a low-resource variety, bearing in mind that idiomaticity is one of the linguistic phenomena whose modeling poses the greatest challenges for computational approaches.",
isbn="978-3-031-73503-5"
}

```

If you use the property data and/or compositionality ratings of this dataset, please cite the following [paper](https://aclanthology.org/2025.mwe-1.5/):

```
@inproceedings{castro-garcia-2025-gathering,
    title = "Gathering Compositionality Ratings of Ambiguous Noun-Adjective Multiword Expressions in {G}alician",
    author = "Castro, Laura  and
      Garcia, Marcos",
    editor = {Ojha, Atul Kr.  and
      Giouli, Voula  and
      Mititelu, Verginica Barbu  and
      Constant, Mathieu  and
      Korvel, Gra{\v{z}}ina  and
      Do{\u{g}}ru{\"o}z, A. Seza  and
      Rademaker, Alexandre},
    booktitle = "Proceedings of the 21st Workshop on Multiword Expressions (MWE 2025)",
    month = may,
    year = "2025",
    address = "Albuquerque, New Mexico, U.S.A.",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.mwe-1.5/",
    pages = "32--40",
    ISBN = "979-8-89176-243-5",
    abstract = "Multiword expressions pose numerous challenges to most NLP tasks, and so do their compositionality and semantic ambiguity. The need for resources that make it possible to explore such phenomena is rather pressing, even more so in the case of low-resource languages. In this paper, we present a dataset of noun-adjective compounds in Galician with compositionality scores at token level. These MWEs are ambiguous due to being potentially idiomatic expressions, as well as due to the ambiguity and productivity of their constituents. The dataset comprises 240 MWEs that amount to 322 senses, which are contextualized in two sets of sentences, manually created, and extracted from corpora, totaling 1,858 examples. For this dataset, we gathered human judgments on compositionality levels for compounds, heads, and modifiers. Furthermore, we obtained frequency, ambiguity, and productivity data for compounds and their constituents, and we explored potential correlations between mean compositionality scores and these three properties in terms of compounds, heads, and modifiers. This valuable resource helps evaluate language models on (non-)compositionality and ambiguity, key challenges in NLP, and is especially relevant for Galician, a low-resource variety lacking annotated datasets for such linguistic phenomena."
}
```

# Contact

To get in contact, please send an e-mail to Laura Castro (laura.castro@usc.gal) or Marcos Garcia (marcos.garcia.gonzalez@usc.gal).

Centro Singular de Investigación en Tecnoloxías Intelixentes, Universidade de Santiago de Compostela (Galicia, Spain).
