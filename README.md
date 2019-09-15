# GoodDocData -- A Template for Simple and Clear Documentation of Hackathon Analyses!

*adapted from [NCBI-Hackathons/GoodDoc](https://github.com/NCBI-Hackathons/GoodDoc) with some tweaks for analysis-driven projects*

*instructions in italics can be deleted as sections are filled in*

*most fields are optional, Conclusion and Important Resources are required*

## Please cite our work -- here is the ICMJE Standard Citation:

### ...and a link to the DOI: *You can make a free DOI with zenodo, synapse, figshare, or other resources <link>*

## Awesome Logo *(if applicable)*

## Website *(if applicable)*

## Abstract *: Summarize everything in a few sentences.* 

## Introduction *: What's the problem? Why should we solve it?*

## Methods *: How did we go about solving it?*

## Results *: What did we observe? Figures are great!*

## Conclusion/Discussion: 

### Please make sure you address ALL of the following:

#### *1. What additional data would you like to have*

#### *2. What are the next rational steps?* 

#### *3. What additional tools or pipelines will be needed for those steps?*

#### *4. What skills would additional collaborators ideally have?*

## Reproduction: *How to reproduce the findings!*

### Docker

*The Docker image contains <R/jupyter> notebooks of all analyses and the dependencies to run them. *Be sure to note if you need any special credentials to access data for these analyses, **don't package restricted data** in your containers!*

Instructions for running the following notebooks: *be sure to adjust these instructions as necessary! check out https://github.com/Sage-Bionetworks/nf-hackathon-2019 for example containers and instructions*

1. `docker pull <your dockerhub repo>/<this container>` command to pull the image from the DockerHub
2. `docker run <your dockerhub repo>/<this container>` Run the docker image from the master shell script

### Important Resources *: primary data, github repository, Synapse project, dockerfile link etc.*




# teamone
_<small><small>(Although this team's name is one, they understand that there are likely multiple etiologies for NF, and will tease them out!)</small>_</small>


## Goal: 
Our goal is to classify and predict responses to a drug based on features like X, Y, Z. We then aimed to correlate the drug targets with relevance in gene expression (RNA-seq) and patient genotypes (WGS) @icon-fas-fa-flask

---
## members

|   |   |   |   |   |   |
|:------:|:------:|:------:|:------:|:-------:|:------:|
|<a href="https://github.com/jacquelinevaleri"><img width=80 src="https://avatars2.githubusercontent.com/u/48304084?s=460&v=4"><br>@jacquelinevaleri</a> <br> Jackie Valeri |<a href="https://github.com/0916kj"><img width=80 src ="https://avatars3.githubusercontent.com/u/41515657?s=460&v=4"><br> @0916kj </a> <br> Kate James |<a href="https://github.com/jzwlin"><img width=80 src="https://avatars2.githubusercontent.com/u/21243979?s=460&v=4"> <br>@jzwlin </a> <br> Wanlin Zheng|<a href="https://github.com/cchristina"> <img width=80 src="https://avatars0.githubusercontent.com/u/3009984?s=460&v=4"> <br>@cchristina </a><br> Christina Cuneo |<a href=""><img width=80 src="https://image.shutterstock.com/image-vector/user-account-profile-circle-flat-260nw-467503004.jpg"> <br> @blaaaaaah </a><br> name name |<a href=""><img width=80 src="https://image.shutterstock.com/image-vector/user-account-profile-circle-flat-260nw-467503004.jpg"> <br> @blaaaaaah </a><br> name name |
|   |   |   |   |   |   |



---

##   What is Neurofibromatosis? 

Neurofibromatosis is a set of three genetic conditions that cause tumors to grow throughout the body. It is automsomal dominant, though about half of all cases occur due to a random mutation.

__NF1__  
* Occurrs in about 1:3000 births  
    * most common genetic predisposition to neurological problems  
* Commonly diagnosed in early childhood or infancy   
* Characteristics (from CTF.org)
    * café-au-lait spots
    * neurofibromas (cutaneous, subcutaneous, plexiform)
    * scoliosis
    * learning disabilities and cognitive differences
    * larger head circumference
    * delayed or early puberty
    * shorter than average
    * optic gliomas
    * bone deformaties
    * cosmetic concerns
    * high blood pressure  
* The affects on an individual can vary wildly, even amongst identical twins! 


__NF2__  
* (info also from ctf.org)
* about 1:25000 worldwide
* characterized by the growth of vestibular schwannomas on the nerve that connects sound and balance information between the ears and bran
* common signs/symptoms
    * tinnitus
    * hearing loss
    * balance issues
    * facial weakness
    * brain and cranial nerve damage
    * swallowing difficulties
    * seizures
    * vision loss
    * balance and mobilitoy loss 


__Schwannomatosis__ (sp?)  
(all from ctf again)
* about 1:40000
* only recently identified
* characterized by the development of schwannomas, usually on spinal and peripheral nerves
    * schwannomas are abnormal growth of Schwann cells which are insulators to nerves (?????)
* common signs
    * numbness, tingling
    * weakness, including favial weakness
    * bowel and urinary dysfunction
    * vision changes
    * headaches 

---

## About the drug study

**this is directly from the page, not in my own words at all**  
To generate this data, we combined compound/drug screens from multiple different projects, representative of about 1.3 million compound-concentration-cell line combinations (some of which are combination experiments, where a mixture of 2 compounds are tested). We then ran these data through a common pipeline to generate summary statistics for each compound-cell line experiment.

---
## steps 

##### 1. Parsing drug screen data and drug metadata into vectors for a model
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


##### 2. Create off-the-shelf machine learning models as well as a simple multi-layer perceptron
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia 

##### 3. Interpretint the results
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia 

##### 4. Correlate the gene targets of drugs with their relevance in RNA-seq and WGS data 
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia 

---

## methods used 

---

## tech stack

---

## results / viz

---


---

## Acknowledgements

Huge thank you to CTF, Sage,  SVAI, NTAP, uuhhh, google launchpad?
