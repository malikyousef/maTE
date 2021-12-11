# maTE : Discovering expressed interactions between microRNAs and their targets.

## Abstract

Disease is often manifested via changes in transcript and protein abundance. MicroRNAs (miRNAs) are instrumental in regulating protein abundance and may measurably influence transcript levels. miRNAs often target more than one mRNA (for humans, the average is three), and mRNAs are often targeted by more than one miRNA (for the genes considered in this study, the average is also three). Therefore, it is difficult to determine the miRNAs that may cause the observed differential gene expression. We present a novel approach, maTE, which is based on machine learning, that integrates information about miRNA target genes with gene expression data. maTE depends on the availability of a sufficient amount of patient and control samples. The samples are used to train classifiers to accurately classify the samples on a per miRNA basis. Multiple high scoring miRNAs are used to build a final classifier to improve separation.

Publication : Malik Yousef, Loai Abdallah, Jens Allmer, maTE: discovering expressed interactions between microRNAs and their targets, Bioinformatics, Volume 35, Issue 20, 15 October 2019, Pages 4020–4028, https://doi.org/10.1093/bioinformatics/btz204




The KNIME workflow can be accessed from the following file (maTE_new_year2021_RF_v3_multipleFiles.knwf).


More details on how to use the workflow: https://malikyousef.com/matemate-discovering-expressed-microrna-target-interactions/
