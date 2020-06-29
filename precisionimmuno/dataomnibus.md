# Challenge: come up with sensitive, specific and reproducible best-practice pipelines for precision treatment of infectious disease using betacoronaviruses as a test case!
## Challenge Modules and Desired App Output:
Clustering of RNAseq data 
Virus response
Cutoff for “CoVID19” “RNAseq signature” vs normal
Drug response
Predicted drug response
Detailed calculation metrics
From RNA-seq
From HLA

Risk factors -- HLA typing
Predict which drugs are most effective with HLA types
Prediction of HLA type from RNAseq


TCR typing
Disease correlation
BCR typing 
Disease correlation
Ig (e.g. IgH) typing for coronaviruses
Disease correlation

EMR integration 
OMOP compliant formatting
Integration of bethematch barcoding system for HLA types



With a little help from our friends...

AWS -- sponsorship, announcement
Ma’ayan lab -- Initial analysis of drug response data
NMDP? -- HLA typing/Datasets 
DNAnexus Research Group -- HLA typing/Datasets 
AIRR -- Individuals have been essential in co-organization, plus datasets!
Regeneron
Geisinger


Potential Datasets:
AIRR Data

https://b-t.cr/t/publicly-available-covid-19-airr-seq-data-sets/849
RNA-seq/microarray

There are 1287 Datasets in GEO

In SRA there are three human RNAseq datasets for SARS-2 per se, plus ~100 more for SARS and MERS

PRJNA233943 -- 143
PRJNA580021 -- 12
PRJNA608742 -- 6

A particularly nice (and preprocessed) one -- 
Coronavirus RNAseq sets from human assays
Ideally human CoVID-19
https://www.ncbi.nlm.nih.gov/Traces/study/?acc=PRJNA615032&o=acc_s%3Aa
22 datasets from 2 cell lines
The two cell lines have very different covid peptide complements
Postmortem from lung tissue: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM4462415; https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM4462416
Xiong, et al. Transcriptomic characteristics of bronchoalveolar lavage fluid and peripheral blood mononuclear cells in COVID-19 patients
Paper: https://doi.org/10.1080/22221751.2020.1747363
Data: 
Raw sequencing reads: https://bigd.big.ac.cn/bioproject/browse/PRJCA002326; https://bigd.big.ac.cn/gsa/browse/CRA002390
Table of their DEG results: Supplemental File 1
Code: https://github.com/zhouyulab/ncov/
About: RNA-seq was employed to investigate host responses to SARS-CoV-2 infection in the bronchoalveolar lavage fluid (BALF) and peripheral blood mononuclear cells (PBMC) samples of COVID-19 patients.
scRNA-seq
Liao et al. The landscape of lung bronchoalveolar immune cells in COVID-19 revealed by single-cell RNA sequencing. (See also AIRR data)
Preprint: https://www.medrxiv.org/node/72689.external-links.html
Data: to be deposited in GEO (not avail yet)
scRNA sequencing, ala: https://www.medrxiv.org/content/10.1101/2020.03.23.20039362v2.full.pdf
Other Data of Potential Interest/Utility
Proteomics + Metabolomics
[EMBARGO] Shen et al. Proteomic and Metabolomic Characterization of COVID-19 Patient Sera.
Preprint: https://www.medrxiv.org/node/75597.external-links.html
Data: http://proteomecentral.proteomexchange.org/cgi/GetDataset
EMBARGOED: “All data are available in the manuscript or the supplementary material. The proteomics and metabolomics data are deposited in ProteomeXchange Consortium (https://www.iprox.org/). Project ID: IPX0002106000. All the data will be publicly released upon publication.”
Metabolomics + Lipidomics
Wu et al. Plasma Metabolomic and Lipidomic Alterations Associated with COVID-19.
Preprint: https://www.medrxiv.org/node/75564.external-links.html
Data: “Available upon request”
Proteomics
Gordon, et al. A SARS-CoV-2-Human Protein-Protein Interaction Map Reveals Drug Targets and Potential Drug-Purposing.
Preprint: https://www.biorxiv.org/content/10.1101/2020.03.22.002386v3
Data: http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD018117


Human Genomic
PacBio Data?
Still hoping for some 10X data
We’ll reach out to our contacts there
HLAcovid19.org

Future Datasets:

Genome England -- planning to sequence 35K datasets
Planning to share with patients
Reached out to us!
Spoke to AWS account manager
UKBioBank CoVID data
Adaptive/Microsoft Data

Existing Software Tools (TBD)

E.g. Repseq


Additional sets:
https://github.com/urmi-21/COVID-19-RNA-Seq-datasets/blob/master/README.md

