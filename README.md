# In-Browser Cryptomining for Good: An Untold Story

This repository contains the dataset and relevant information for the "[In-Browser Cryptomining for Good: An Untold Story](https://ieeexplore.ieee.org/abstract/document/9566204)" paper.


------------------------------
If you use any material from this repository, please cite the following work:

```
@INPROCEEDINGS{9566204,  
author={Tekiner, Ege and Acar, Abbas and Uluagac, A. Selcuk and Kirda, Engin and Selcuk, Ali Aydin},  
booktitle={2021 IEEE International Conference on Decentralized Applications and Infrastructures (DAPPS)},   
title={In-Browser Cryptomining for Good: An Untold Story},   
year={2021}, 
pages={20-29},  
doi={10.1109/DAPPS52256.2021.00008}}
```


## Dataset
We prepared several keyword lists to be able to find cryptojacking samples in the wild and create a dataset that covers the list of domains that have in-browser cryptomining script(s).



This repo contains the following folders and files;

### [Dataset](https://github.com/browserminingforgood/browserminingforgood/tree/main/Dataset)
We present 4 different datasets for this paper. All the datasets can be found with their explanation under the dataset folder.

#### Keywords

In order to find in-browser mining samples in the wild, we firstly needed to identify the keywords using by the service providers. With these keywords, we made a static search via several web tools. The main resource for these keywords was known blacklists and other keyword lists released by other studies in the literature.


|-> "[service provider keywords.csv](https://github.com/browserminingforgood/browserminingforgood/blob/main/Dataset/service%20provider%20keywords.csv)" (file): This file contains the needed keywords to identify the 14 known service providers uniquely. Inside the CSV file, we listed the known service providers and the major keywords we can identify during our static keyword search.
 
|-> "[unknown service provider keywords.csv](https://github.com/browserminingforgood/browserminingforgood/blob/main/Dataset/unknown%20service%20provider%20keywords.csv)" (file): This file contains the keywords that can be used to identify several cryptominers we can not associated with any service providers. This file only contains 130 in-browser mining keywords we could not be able to identify the service provider during our research.
 
#### Domain Lists
 
 |->  "[known_service_provider_domain_list.csv](https://github.com/browserminingforgood/browserminingforgood/blob/main/Dataset/known_service_provider_domain_list.csv)" (file): This file contains the domains with the service providers we discovered during our research. The list also includes the service provider name for each domain and associated keyword. Please note that some of the domains might use more than one service providers parallelly in the webpage or whole website.
 
 |-> "[unknown_service_provider_domain_list.csv](https://github.com/browserminingforgood/browserminingforgood/blob/main/Dataset/unknown_service_provider_domain_list.csv)" (file): This file contains the domains with unknown service providers. The second column includes the keyword that is used to identify this domain. Please note that, 267 domains contain more than one unknown service provider keyword.
 
 
 

### Methodology and Reproducibility of the Dataset:

In order to reproduce the dataset and experiments, one can either use the domain lists we released or can download the keyword lists and then make a query on [PublicWWW's website](https://publicwww.com/). For deeper experiments and future research, web crawlers or web spiders can be used to download HTTP files of the webpages.

### Contact

Please send an email to browserminingforgood (at) gmail (dot) com if you have any questions.

