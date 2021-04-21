# In-Browser Cryptomining for Good: An Untold Story

This repository contains the cryptojacking malware dataset and relevant information for the ["In-Browser Cryptomining for Good: An Untold Story" paper]

## 1. Abstract
Abstract—In-browser   cryptomining   uses   the   computationalpower  of  a  website’s  visitors  to  mine  cryptocurrency,  i.e.,  tocreate  new  coins.  With  the  rise  of  ready-to-use  mining  scriptsdistributed  by  service  providers  (e.g.,  Coinhive),  it  has  becometrivial  to  turn  a  website  into  a  cryptominer  by  copying  andpasting  the  mining  script.  Both  legitimate  webpage  owners  whowant to raise an extra revenue under users’ explicit consent andmalicious  actors  who  wish  to  exploit  the  computational  powerof  the  users’  computers  without  their  consent  have  started  toutilize  this  emerging  paradigm  of  cryptocurrency  operations.In-browser  cryptomining,  though  mostly  abused  by  maliciousactors  in  practice,  is  indeed  a  promising  funding  model  thatcan  be  utilized  by  website  owners,  publishers,  or  non-profitorganizations for legitimate business purposes, such as to collectrevenue   or   donations   for   humanitarian   projects,   inter   alia.However,  our  analysis  in  this  paper  shows  that  in  practice,regardless of their being legitimate or not, all in-browser miningscripts  are  treated  the  same  as  malicious  cryptomining  samples(akacryptojacking)  and  blacklisted  by  browser  extensions  orantivirus programs.   Indeed, there is a need for a better under-standing of the in-browser cryptomining ecosystem. Hence, in thispaper,  we  present  an  in-depth  empirical  analysis  of  in-browsercryptomining processes, focusing on the samples explicitly askingfor  user  consent,  which  we  callpermissioned  cryptomining.  Tothe  best  of  our  knowledge,  this  is  the  first  study  focusing  onthe  permissioned  cryptomining  samples.  For  this,  we  created  adataset of 6269 unique websites containing cryptomining scriptsin their source codes to characterize the in-browser cryptominingecosystem  by  differentiating  permissioned  and  permissionlesscryptomining  samples.We  believe  that  (1)  this  paper  is  thefirst attempt showing that permissioned in-browser cryptominingcould be a legitimate and viable monetization tool if implementedresponsibly and without interrupting the user, and (2) this paperwill catalyze the widespread adoption of legitimate cryptominingwith  user  consent  and  awareness.


## 2. PublicWWW Dataset
The PublicWWW dataset consists of two domain lists and two keyword lists. 
 
1. "known_service_provider_domain_list.csv": This file contains the domains with the publicly known service providers. The list also includes the service provider name for each domain and associated keyword. Please note that some of the domain use multiple service providers. 
2. "unknown_service_provider_domain_list.csv": This file contains the domains with unknown service providers. The second column includes the keyword that is used to identify this domain.
3. "service provider keywords.csv": This file contains the keywords that can be used to identify the 14 service providers uniquely.
4. "unknown service provider keywords.csv": This file contains the keywords that can be used to identify the cryptominer, but the associated service provider is unknown.

### Reproducibility of PublicWW Dataset:

In order to reproduce the dataset and experiments, one can either use the domain lists we released or can download the keyword lists and then make a query on [PublicWWW's website](https://publicwww.com/). Finally, we also release the crawler we used to download the samples.

## 2. Major Instances

This folder (Major_instances_links.xlsx) contains the major cryptojacking attack instances that we used in the paper.
