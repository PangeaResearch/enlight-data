# enlight-data
Datasets that accompanies the ENLIGHT manuscript, see (https://www.cell.com/med/fulltext/S2666-6340(22)00455-X?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS266663402200455X%3Fshowall%3Dtrue).  
Each file contains a raw mRNA matrix of size #genes*#patients. Gene names are given in HUGO format, column names are patient IDs.  
Dataset names corresponds to the names in the manuscript (see Table S1).  
Patient IDs corresponds to the "Sample ID" column in "drug_response_classifications.csv".  
mRNA value types and cancer types for each dataset are as follows:   
| File      | mRNA Value type | Cancer type     |
|   :---:     |   :----:    |    :---:      |
| Sorafenib_2.csv      | Microarray       | NSCLC   |
| Cetuximab.csv   | Microarray        | Head and neck |
| Bevacizumab_4.csv | Microarray | Colorectal  
| Bevacizumab_2.csv | Microarray | Colorectal
| Trastuzumab_2.csv | Microarray | Breast
| Rituximab.csv | Microarray  | CLL
| Trastuzumab_3.csv | Microarray  | Breast
|Trastuzumab_4.csv | Microarray  | Breast
|Trastuzumab_5.csv | read counts  | Breast
|Bevacizumab_3.csv | read counts  | Breast
|Selinexor.csv | TPM  | GBM
|Tipifarnib_2.csv | Microarray | AML  
|Tipifarnib_1.csv | Microarray  | AML
|MK2206.csv | Microarray  | Breast
|Vismodegib.csv | FPKM  | BCC
|MGH_Ribociclib.csv | TPM  | Breast
|MGH_Alpelisib.csv | TPM  | Breast
|Lapatinib.csv | Microarray  | Breast
|Sorafenib.csv | Microarray  | HCC
|Bevacizumab.csv | Microarray  | Colorectal
|Trastuzumab.csv | Microarray  | Breast
|BRAFi_1.csv | FPKM  | Melanoma
|BRAFi_2.csv | Microarray  | Melanoma
|BRAFi_3.csv | Microarray  | Melanoma
|Anti-PD1.csv | TPM  | Melanoma
|Anti-PD1_2.csv | read counts  | GBM
|Anti-PD1_3.csv | Microarray  | RCC
|Anti-PD1_4.csv | Microarray  | Breast
|Anti-PD1_5.csv | FPKM  | Melanoma
|Anti-PD1 +- Anti-CTLA4.csv | Microarray | HCC  
