# Reaction-Classification

This repository contains the code for Yunlong Masters' Thesis, Comparison of unsupervised, supervised and semi-supervised chemical reaction embeddings for reaction classification.

![Logo](https://t4.ftcdn.net/jpg/05/63/41/63/240_F_563416386_ruJPhBmQZTDGN90VyCbDFMnVy5sbwkeb.jpg)


## Data

For legal reasons, the exact (processed, labeled and annotated) data that was used during this project at Elsevier can not be shared. 

### USPTO 1k TPL
We identified suitable public datasets USPTO 1k TPL here. which consists of 445k reactions divided into 1000 template labels. These labels were derived through a multi-step process: first, the USPTO dataset was atom-mapped using RXNMapper. Then, the template extraction workflow by Thakkar et al. was applied to identify the reaction templates. Finally, reactions corresponding to the 1,000 most frequent template hashes were selected and designated as class labels. The USPTO 1k TPL dataset is characterised by a significant imbalance in class distribution.

The data set can be downloaded from:
https://ibm.ent.box.com/v/MappingChemicalReactions



## Notebooks

We included all the necessary steps use for data preprocessing, model fine-tune, reaction embeddings and evaluation. 

However, for legal reasons, the pre-trained Bert Model, and all the fine-tune models were used during this project at Elsevier can not be shared. 

For more details about DRFP and RXNFP, please refer to https://rxn4chemistry.github.io/rxnfp// and https://github.com/reymond-group/drfp/tree/main


## Acknowledgement

I would like to express my deepest gratitude for the continuous support and guidance provided by Prof. Dr. P. T. Groth from the University of Amsterdam. I also extend my heartfelt thanks to Kinga Szarkowska, Dr. Timur Madzhidov, and Markus Schwörer for their invaluable contributions and encouragement throughout this project. Their expertise and insights have been instrumental in the development and success of the Reaction Classification project.
