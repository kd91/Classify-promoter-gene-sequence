# Classify-promoter-gene-sequence
Classification of E. coli promoter gene sequences (DNA) using NLP and ML

E. coli promoter gene sequences (DNA) with associated imperfect domain theory:
Promoters have a region where a protein (RNA polymerase) must make contact and the helical DNA sequence must have a valid conformation so that the two pieces of the contact region spatially align. Prolog notation is used. promoter :- contact, conformation.


Data source:
https://archive.ics.uci.edu/ml/machine-learning-databases/molecular-biology/promoter-gene-sequences/

Attribute information:
- attributes predicted: member/non-member of class of sequences with biological promoter activity (promoters initiate the process of gene expression)
- Class Distribution: 50% (53 positive instances, 53 negative instances)
- class : One of {+/-}, indicating the class ("+" = promoter)
- instance_name : (non-promoters named by position in the 1500-long nucleotide sequence provided by T. Record)
- gene_sequence : 57 sequential nucleotide ("base-pair") positions


ML classification models used in this project with NLP:
1. Decision tree
2. Random Forest
3. Multinomial Naive Bayes
