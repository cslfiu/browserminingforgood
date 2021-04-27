# In-Browser Cryptomining for Good: An Untold Story

## Dataset
We prepared this repository to provide dataset and the reproduceability instructions of the experiments we made for our paper, In Browser Mining for Good: An Untold Story.

This repo contains the following folders and files,

-> Dataset (Folder)
We present 4 different datasets for this paper. All the datasets can be found under this folder.

 |->  "known_service_provider_domain_list.csv" (file): This file contains the domains with the service providers we discovered during our research. The list also includes the service provider name for each domain and associated keyword. Please note that some of the domains might use more than one service providers in one page.
 
 |-> "unknown_service_provider_domain_list.csv" (file): This file contains the domains with unknown service providers. The second column includes the keyword that is used to identify this domain.
 
 |-> "service provider keywords.csv" (file): This file contains the needed keywords to identify the 14 service providers uniquely.
 
 |-> "unknown service provider keywords.csv" (file): This file contains the keywords that can be used to identify several cryptominers we can not associated with any service providers.
 

### Reproducibility of the Dataset:

In order to reproduce the dataset and experiments, one can either use the domain lists we released or can download the keyword lists and then make a query on [PublicWWW's website](https://publicwww.com/). Finally, we also release the crawler we used to download the samples.
