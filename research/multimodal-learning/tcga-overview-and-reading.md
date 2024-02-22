## Contents

- [Datasets](#datasets)
	- [TCGA-PRAD (Prostate Carcinoma)](#tcga-prad-prostate-carcinoma)
	- [TCGA-BRCA (Breast invasive carcinoma)](#tcga-brca-breast-invasive-carcinoma)
	- [TCGA-LUAD and TCGA-LUSC (Lung carcinomas)](#tcga-luad-and-tcga-lusc-lung-carcinomas)
	- [TCGA-OV (Ovarian serous cystadenocarcinoma)](#tcga-ov-ovarian-serous-cystadenocarcinoma)
	- [TCGA-GBM (Glioblastoma multiforme)](#tcga-gbm-glioblastoma-multiforme)
- [Selected reading](#selected-reading)
	- [Review and overview articles](#review-and-overview-articles)
	- [Methodological articles](#methodological-articles)
	- [Application articles](#application-articles)
- [Bibliography](#bibliography)

# Datasets

Useful links:

- [Abreviations](https://gdc.cancer.gov/resources-tcga-users/tcga-code-tables/tcga-study-abbreviations)
- [All cancers overview](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/studied-cancers)

The following is an overview of the TCGA projects selected for further investigation, which have high case numbers and cover well-studied diseases.

## TCGA-PRAD (Prostate Carcinoma)

- [Overview](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/studied-cancers/prostate-carcinoma-study) 
- [Data on GDC portal](https://portal.gdc.cancer.gov/projects/TCGA-PRAD)  (n=500)
- Key publication: [ The Molecular Taxonomy of Primary Prostate Cancer](https://www.cell.com/cell/fulltext/S0092-8674(15)01339-2)

## TCGA-BRCA (Breast invasive carcinoma)

- [Overview](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/studied-cancers/breast-lobular-carcinoma-study)
- [Data on GDC portal](https://portal.gdc.cancer.gov/projects/TCGA-BRCA) (n=1098)
- Key publications: 
	- Lobular carcinoma: [Comprehensive Molecular Portraits of Invasive Lobular Breast Cancer](https://www.cell.com/cell/fulltext/S0092-8674(15)01195-2)
	- Ductal carcinoma: [Comprehensive molecular portraits of human breast tumours](https://www.nature.com/articles/nature11412)

## TCGA-LUAD and TCGA-LUSC (Lung adeno- and squamous cell carcinoma)

### Squamous cell carcinoma (LUSC)

- [Overview](https://www.cancer.gov/ccg/research/structural-genomics/tcga/studied-cancers/lung-squamous-cell-carcinoma-study)
- [Data on GDC portal](https://portal.gdc.cancer.gov/projects/TCGA-LUSC)  (n=504)
- Key publication: [Comprehensive genomic characterization of squamous cell lung cancers](https://www.nature.com/articles/nature11404)

### Adenocarcinoma (LUAD)

- [Overview](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/studied-cancers/lung-adenocarcinoma-study) 
- [Data on GDC portal](https://portal.gdc.cancer.gov/projects/TCGA-LUAD) (n=585)
- Key publication: [Comprehensive molecular profiling of lung adenocarcinoma](https://www.nature.com/articles/nature13385)

## TCGA-OV (Ovarian serous cystadenocarcinoma)

- [Overview](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/studied-cancers/ovarian-serous-adenocarcinoma)
- [Data on GDC portal](https://portal.gdc.cancer.gov/projects/TCGA-OV)  (n=608)
- Key publication: [Integrated genomic analyses of ovarian carcinoma](https://www.nature.com/articles/nature10166)

## TCGA-GBM (Glioblastoma multiforme)

- [Overview](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/studied-cancers/glioblastoma-multiforme-study)
- Data
	- [GDC portal](https://portal.gdc.cancer.gov/projects/TCGA-GBM ) (n=617)
	- [Radiology](https://www.cancerimagingarchive.net/collection/tcga-gbm/) (n=262)
- Publications
	- TCGA expanded study: [The Somatic Genomic Landscape of Glioblastoma](https://www.cell.com/fulltext/S0092-8674%2813%2901208-7)
	- Radiomics: [Advancing The Cancer Genome Atlas glioma MRI collections with expert segmentation labels and radiomic features](https://www.nature.com/articles/sdata2017117)


# Selected reading

## Review and overview articles

|Title | Description |
|------|-------------|
| Hutter and Zenklusen, ‘The Cancer Genome Atlas’. ([Hutter and Zenklusen 2018](https://doi.org/10.1016/j.cell.2018.03.042)) | Comment article, summarising recent efforts (contemporary publications) in onological research using the dataset |
| Wu et al., ‘Data Mining in Clinical Big Data’. ([Wu et al. 2021](https://doi.org/10.1186/s40779-021-00338-z)) | General review on big datasets (incl. TCGA and others), with descriptions of access process and processing techniques for each |
| Rappoport and Shamir, ‘Multi-Omic and Multi-View Clustering Algorithms’. ([Rappoport and Shamir 2018](https://doi.org/10.1093/nar/gky889)) | Does what is says on the tin. Benchmarking multi-omics clustering algorithms on TCGA data |

## Methodological articles

|Title | Description |
|------|-------------|
| Lock et al., ‘Joint and Individual Variation Explained (JIVE) for Integrated Analysis of Multiple Data Types’. ([Lock et al. 2013](https://doi.org/10.1214/12-AOAS597)) | Introducing a method of capturing joint variation across genomic data-types, similar to PCA; demonstated in glioblastoma (TCGA-GBM) gene expression and miRNA associations |
| Ching, Zhu, and Garmire, ‘Cox-Nnet’. ([Ching, Zhu, and Garmire 2018](https://doi.org/10.1371/journal.pcbi.1006076)) | Cox-nnet, alternative to Cox-PH model, with hidden layers that provide additional biological info? Unclear how much of a gamechanger this is relative to standard Cox-PH |

## Application articles

### Unimodal prediction (outcomes)

> **Review**
>
> Zhu, Wan, Longxiang Xie, Jianye Han, and Xiangqian
> Guo. ‘The Application of Deep Learning in Cancer Prognosis
> Prediction’. *Cancers* 12, no. 3 (March 2020): 603.
> <https://doi.org/10.3390/cancers12030603>.

|Title | Model | Prediction | Cancer |
|------|-------|------------|--------|
| Coudray et al., ‘Classification and Mutation Prediction from Non–Small Cell Lung Cancer Histopathology Images Using Deep Learning’. ([Coudray et al. 2018](https://doi.org/10.1038/s41591-018-0177-5)) | CNN  | **FROM:** Pathology, WSI <br>**TO:** cancer subtype                                        | Lung       |
| Yu et al., ‘Predicting Non-Small Cell Lung Cancer Prognosis by Fully Automated Microscopic Pathology Image Features’. ([Yu et al. 2016](https://doi.org/10.1038/ncomms12474))                                | Cell feature extraction; ensemble of classifiers (incl. SVM, random forests,…; for diagnostic classification); Cox PH (for prognosis) | **FROM:** Pathology, WSI <br>**TO:** Survival/prognosis; malignancy and                    | Lung (Lung cancer patients have very diverse outcomes, even within the same stage and grade) |
| Kather et al., ‘Predicting Survival from Colorectal Cancer Histology Slides Using Deep Learning’; ([Kather et al. 2019](https://doi.org/10.1371/journal.pmed.1002730))                              | CNN; Cox PH                                                                                                                           | **FROM:** Pathology, WSI <br>**TO:** Survival; tumour microenvironment “deep stroma score” | Colorectal |

See also a brief review in Section II.A of ([Chen et al.
2022](https://doi.org/10.1109/TMI.2020.3021387))

### Multi-omics prediction (outcomes from multi-omics)

|Title | Model | Prediction | Cancer |
|------|-------|------------|--------|
| Chaudhary et al., ‘Deep Learning–Based Multi-Omics Integration Robustly Predicts Survival in Liver Cancer’. ([Chaudhary et al. 2018](https://doi.org/10.1158/1078-0432.CCR-17-0853)) | Autoencoder | **FROM**: Multiomics (RNA, miRNA, methylation)<br><br>**TO**: survival subgroups (prognosis) | Liver  |

### Multimodal prediction (linking or combining modalities)

> “strategies for fusing data in the biomedical domain (e.g. histology
> images, molecular proﬁles) are relatively unexplored. In cancer
> genomics, most works have focused on establishing correspondences
> between histology tissue and genomics” [(Chen et al., 2022, p. 759)](https://doi.org/10.1109/TMI.2020.3021387)

|Title | Model | Prediction | Cancer |
|------|-------|------------|--------|
| Sun et al., ‘A Radiomics Approach to Assess Tumour-Infiltrating CD8 Cells and Response to Anti-PD-1 or Anti-PD-L1 Immunotherapy’. ([Sun et al. 2018](https://doi.org/10.1016/S1470-2045(18)30413-3))  | linear elasitc-net regularised regression | **FROM**: CT (radiomics), RNA-seq<br> <br>**TO**: CD8B expression (proxy for CD8 cell infiltration/abundance) | multi; 3 cohorts |
| Weitz et al., ‘Transcriptome-Wide Prediction of Prostate Cancer Gene Expression from Histopathology Images Using Co-Expression-Based Convolutional Neural Networks’. ([Weitz et al. 2022](https://doi.org/10.1093/bioinformatics/btac343)) | CNN   | **FROM**: WSI<br><br>**TO:** gene expression  | prostate |
|**Chen et al., ‘Pathomic Fusion’.** [(Chen et al., 2022, p. 759)](https://doi.org/10.1109/TMI.2020.3021387) | - CNN (pathology features)<br>- GCN (pathology cell organisation features)<br>- Feed-foward NN (genomic profile)<br>→ Tensor fusion with Kronecker product | **FROM**:  <br>- Pathology WSI<br>- Genomic molecular profile<br><br>**TO**:<br>Grading, treatment response, survival prediction | renal cell carcinoma |

# Bibliography

Chaudhary, Kumardeep, Olivier B. Poirion, Liangqun Lu, and Lana X.
Garmire. 2018. “Deep LearningBased Multi-Omics Integration Robustly
Predicts Survival in Liver Cancer.” *Clinical Cancer Research* 24 (6):
1248–59. <https://doi.org/10.1158/1078-0432.CCR-17-0853>.

Chen, Richard J., Ming Y. Lu, Jingwen Wang, Drew F. K. Williamson, Scott
J. Rodig, Neal I. Lindeman, and Faisal Mahmood. 2022. “Pathomic Fusion:
An Integrated Framework for Fusing Histopathology and Genomic Features
for Cancer Diagnosis and Prognosis.” *IEEE Transactions on Medical
Imaging* 41 (4): 757–70. <https://doi.org/10.1109/TMI.2020.3021387>.

Ching, Travers, Xun Zhu, and Lana X. Garmire. 2018. “Cox-Nnet: An
Artificial Neural Network Method for Prognosis Prediction of
High-Throughput Omics Data.” *PLOS Computational Biology* 14 (4):
e1006076. <https://doi.org/10.1371/journal.pcbi.1006076>.

Coudray, Nicolas, Paolo Santiago Ocampo, Theodore Sakellaropoulos,
Navneet Narula, Matija Snuderl, David Fenyö, Andre L. Moreira, Narges
Razavian, and Aristotelis Tsirigos. 2018. “Classification and Mutation
Prediction from Nonsmall Cell Lung Cancer Histopathology Images Using
Deep Learning.” *Nature Medicine* 24 (10): 1559–67.
<https://doi.org/10.1038/s41591-018-0177-5>.

Hutter, Carolyn, and Jean Claude Zenklusen. 2018. “The Cancer Genome
Atlas: Creating Lasting Value Beyond Its Data.” *Cell* 173 (2): 283–85.
<https://doi.org/10.1016/j.cell.2018.03.042>.

Kather, Jakob Nikolas, Johannes Krisam, Pornpimol Charoentong, Tom
Luedde, Esther Herpel, Cleo-Aron Weis, Timo Gaiser, et al. 2019.
“Predicting Survival from Colorectal Cancer Histology Slides Using Deep
Learning: A Retrospective Multicenter Study.” *PLOS Medicine* 16 (1):
e1002730. <https://doi.org/10.1371/journal.pmed.1002730>.

Lock, Eric F., Katherine A. Hoadley, J. S. Marron, and Andrew B. Nobel.
2013. “Joint and Individual Variation Explained (JIVE) for Integrated
Analysis of Multiple Data Types.” *The Annals of Applied Statistics* 7
(1): 523–42. <https://doi.org/10.1214/12-AOAS597>.

Rappoport, Nimrod, and Ron Shamir. 2018. “Multi-Omic and Multi-View
Clustering Algorithms: Review and Cancer Benchmark.” *Nucleic Acids
Research* 46 (20): 10546–62. <https://doi.org/10.1093/nar/gky889>.

Sun, Roger, Elaine Johanna Limkin, Maria Vakalopoulou, Laurent Dercle,
Stéphane Champiat, Shan Rong Han, Loïc Verlingue, et al. 2018. “A
Radiomics Approach to Assess Tumour-Infiltrating CD8 Cells and Response
to Anti-PD-1 or Anti-PD-L1 Immunotherapy: An Imaging Biomarker,
Retrospective Multicohort Study.” *The Lancet Oncology* 19 (9): 1180–91.
<https://doi.org/10.1016/S1470-2045(18)30413-3>.

Weitz, Philippe, Yinxi Wang, Kimmo Kartasalo, Lars Egevad, Johan
Lindberg, Henrik Grönberg, Martin Eklund, and Mattias Rantalainen. 2022.
“Transcriptome-Wide Prediction of Prostate Cancer Gene Expression from
Histopathology Images Using Co-Expression-Based Convolutional Neural
Networks.” Edited by Inanc Birol. *Bioinformatics* 38 (13): 3462–69.
<https://doi.org/10.1093/bioinformatics/btac343>.

Wu, Wen-Tao, Yuan-Jie Li, Ao-Zi Feng, Li Li, Tao Huang, An-Ding Xu, and
Jun Lyu. 2021. “Data Mining in Clinical Big Data: The Frequently Used
Databases, Steps, and Methodological Models.” *Military Medical
Research* 8 (1): 44. <https://doi.org/10.1186/s40779-021-00338-z>.

Yu, Kun-Hsing, Ce Zhang, Gerald J. Berry, Russ B. Altman, Christopher
Ré, Daniel L. Rubin, and Michael Snyder. 2016. “Predicting Non-Small
Cell Lung Cancer Prognosis by Fully Automated Microscopic Pathology
Image Features.” *Nature Communications* 7 (1): 12474.
<https://doi.org/10.1038/ncomms12474>.