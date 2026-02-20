# data-urban-adapted species
## An open database of seven urban-adapted mammal species virus surveillance
### Suggested citation:

Please cite the following:

- Xuemin Wei, Hongfeng Li, Zheng Y.X. Huang, Shuo Li, Yuhao Wang, Jie Lan, Li Hu, Yang Li, Daniel J. Becker, Fuwen Wei, Yifei Xu (2024) **Risk assessment of zoonotic viruses in urban-adapted wildlife**. _bioRxiv_ DOI: 10.1101/2024.12.18.629064. 

### What's in the dataset

Each row of the dataset corresponds to the testing data we were able to identify based on reported sampling procedures. Each row has three fields that describe the accompanying publication:  

|  column name | description |
|  --------    |  --------------- |
|   PMID/Title |  PMID/Title of publication |
|   Authors   |   Authors of publication |
|   Year   | Year of publication  | 

All other fields describe the actual  seven urban-adapted mammal species virus positivity data, often with several rows from each study:

|  column name | description |
|  --------    |  --------------- |
|  Virus   |  The name of virus family/genus/species |
|  HostSpecies   |  The urban-adapted mammal species |
|  Detection_method   |  Type of test used (e.g.,  PCR, ELISA)  |
|  Positive_sample_number   |  The number of samples positive for coronaviruses (as identified below)  |
|  Total_sample_number   |  The number of samples tested   |
|  Positivity   |  Reported or estimated values of virus positivity across samples (should usually equal nPositive / nSamples)  |
|  VirusOrder   |  The virus order |
|  VirusFamily   |   The virus family  |
|  VirusSpecies   | The virus species |
|  Country   |   Country of sampling site  |
|  Continents  |   Continents of sampling site  |
