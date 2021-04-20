# SoK: Cryptojacking Malware

This repository contains the cryptojacking malware dataset and relevant information for the ["In-Browser Cryptomining for Good: An Untold Story" paper]

## 1. PublicWWW Dataset
The PublicWWW dataset consists of two domain lists and two keyword lists. 
 
1. "known_service_provider_domain_list.csv": This file contains the domains with the publicly known service providers. The list also includes the service provider name for each domain and associated keyword. Please note that some of the domain use multiple service providers. 
2. "unknown_service_provider_domain_list.csv": This file contains the domains with unknown service providers. The second column includes the keyword that is used to identify this domain.
3. "service provider keywords.csv": This file contains the keywords that can be used to identify the 14 service providers uniquely.
4. "unknown service provider keywords.csv": This file contains the keywords that can be used to identify the cryptominer, but the associated service provider is unknown.

### Reproducibility of PublicWW Dataset:

In order to reproduce the dataset and experiments, one can either use the domain lists we released or can download the keyword lists and then make a query on [PublicWWW's website](https://publicwww.com/). Finally, we also release the crawler we used to download the samples.

## 2. Major Instances

This folder (Major_instances_links.xlsx) contains the major cryptojacking attack instances that we used in the paper.
