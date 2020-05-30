
# **Inference Attacks Against Differentially-PrivateQuery Results from Genomic Datasets Including Dependent Tuples**
To be Presented in the ISMB2020 Conference: https://www.iscb.org/cms_addon/conferences/ismb2020/proceedings.php 
Described in the Bioinformatics journal paper (2020) by Almadhoun et al. at: 
## Abstract:
The rapid decrease in the sequencing technology costs leads to a revolution in medical research and clinical care.
Today, researchers have access to large genomic datasets to study associations between variants and complex traits.
However, availability of such genomic datasets also results in new privacy concerns about personal information of the
participants in genomic studies. Differential privacy (DP) is one of the rigorous privacy concepts, which received
widespread interest for sharing summary statistics from genomic datasets while protecting the privacy of participants
against inference attacks. However, DP has a known drawback as it does not consider the correlation between dataset
tuples. Therefore, privacy guarantees of DP-based mechanisms may degrade if the dataset includes dependent tuples,
which is a common situation for genomic datasets due to the inherent correlations between genomes of family
members.

## Result:
In this article, using two real-life genomic datasets, we show that exploiting the correlation between the dataset
participants results in significant information leak from differentially private results of complex queries. We formulate
this as an attribute inference attack and show the privacy loss in minor allele frequency (MAF) and chi-square queries.
Our results show that using the results of differentially private MAF queries and utilizing the dependency between
tuples, an adversary can reveal up to 50% more sensitive information about the genome of a target (compared to
original privacy guarantees of standard DP-based mechanisms), while differentially privacy chi-square queries can
reveal up to 40% more sensitive information. Furthermore, we show that the adversary can use the inferred genomic
data obtained from the attribute inference attack to infer the membership of a target in another genomic dataset (e.g.
associated with a sensitive trait). Using a log-likelihood-ratio test, our results also show that the inference power of the
adversary can be significantly high in such an attack even using inferred (and hence partially incorrect) genomes.




