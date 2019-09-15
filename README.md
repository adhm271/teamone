# HACKNF2 – teamone


## Please cite our work -- here is the ICMJE Standard Citation:

### ...and a link to the DOI: *You can make a free DOI with zenodo, synapse, figshare, or other resources <link>*

<!-- ## Awesome Logo *(if applicable)* -->

<img src="./static/images/templogo.png">

## Website *(if applicable)*


## Abstract *: Summarize everything in a few sentences.* 

To understand the results from the drug screening data, we wanted to see if any chemical or structural properties of the drugs themselves correlated with the screening. We analyzed features from ~1750 of the molecules in the screen via PubChem, exploring properties such as molecular weight, number of hydrogen bonds, total polar surface area, etc. We then used several off-the-shelf classifiers from sklearn, such as a Random Forest Classifier and KNN Classifier, to identify salient features and the predictive property of these molecules. We also looked at a very simple multi-layer perceptron to try to get an increased accuracy. These models were engineered for both regression and classification, with an improvement in accuracy in the classification models. The most important features of drugs contributing to differential AUC and Maximum Response were total polar surface area (TPSA), complexity, and xlogp. Finally, we extended the drug screening data to the top genes targeted by the highest-performing drugs, finding xxx in RNA-seq and xxx in WGS.


## Introduction *: What's the problem? Why should we solve it?*

Modern high-throughput drug screens are useful for testing out drugs in vitro before executing more expensive, resource-intensive animal trials or human clinical trials. However, drug screen data is not always robust, and difficulties arise in translating results from the dish to an in vivo model. Given these challenges, we were interested in understanding if the chemical or structural properties of the drugs were driving their in vitro measured response. Since we wanted to classify and predict responses to a drug based on features like molecular weight and polarity, we looked at how these features correlated with the predictive ability of the three models we used. We then aimed to correlate the drug targets with relevance in gene expression (RNA-seq) and patient genotypes (WGS). 

## Methods *: How did we go about solving it?*


##### 1. Parsing drug screen data and drug metadata into vectors for a model
>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 



##### 2. Create off-the-shelf machine learning models as well as a simple multi-layer perceptron
>Decision tree stuff~



<table>
<tr>
    <td>
<img width=350 src="./static/images/tree1crop.png">
<details>
  <summary>Expand to View Full Size! (warning: v big)</summary>
  
 <!-- <img width=400 src="./static/images/tree1.png"> -->
 <img src="./static/images/tree1.png">
</details>

</td>

<td>
<img width=350 src="./static/images/tree2crop.png">
<details>
  <summary>Expand to View Full Size! (warning: v big)</summary>
  
 <!-- <img width=400 src="./static/images/tree2.png"> -->
 <img src="./static/images/tree2.png">
</details>
</td>
</tr>

<tr>
<td>
<img width=350 src="./static/images/tree3crop.png">
<details>
  <summary>Expand to View Full Size! (warning: v big)</summary>
  
 <!-- <img width=400 src="./static/images/tree3.png"> -->
 <img src="./static/images/tree3.png">
</details>
</td>

<td>

<img width=350 src="./static/images/tree4crop.png">
<details>
  <summary>Expand to View Full Size! (warning: v big)</summary>
  
 <!-- <img width=400 src="./static/images/tree4.png"> -->
 <img src="./static/images/tree4.png">
r</details>
</td>
</tr>
</table>

##### 3. Interpretint the results
>`Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. `

##### 4. Correlate the gene targets of drugs with their relevance in RNA-seq and WGS data 
>`Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia `

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


---
## members

|   |   |   |   |   |   |
|:------:|:------:|:------:|:------:|:-------:|:------:|
|<a href="https://github.com/jackievaleri"><img width=80 src="https://avatars2.githubusercontent.com/u/48304084?s=460&v=4"><br>@jackievaleri</a> <br> Jackie Valeri |<a href="https://github.com/0916kj"><img width=80 src ="https://avatars3.githubusercontent.com/u/41515657?s=460&v=4"><br> @0916kj </a> <br> Kate James |<a href="https://github.com/jzwlin"><img width=80 src="https://avatars2.githubusercontent.com/u/21243979?s=460&v=4"> <br>@jzwlin </a> <br> Wanlin Zheng|<a href="https://github.com/cchristina"> <img width=80 src="https://avatars0.githubusercontent.com/u/3009984?s=460&v=4"> <br>@cchristina </a><br> Christina Cuneo |<a href=""><img width=80 src="https://image.shutterstock.com/image-vector/user-account-profile-circle-flat-260nw-467503004.jpg"> <br> @AAR0NM </a><br> Aaron M |<a href=""><img width=80 src="https://image.shutterstock.com/image-vector/user-account-profile-circle-flat-260nw-467503004.jpg"> <br> @blaaaaaah </a><br> name name |
|   |   |   |   |   |   |



---

<!-- ##   What is Neurofibromatosis? 

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
To generate this data, we combined compound/drug screens from multiple different projects, representative of about 1.3 million compound-concentration-cell line combinations (some of which are combination experiments, where a mixture of 2 compounds are tested). We then ran these data through a common pipeline to generate summary statistics for each compound-cell line experiment. -->



<!-- ## tech stack

--- -->


## Acknowledgements

#
Huge thank you to CTF, Sage,  SVAI, NTAP, uuhhh, google launchpad?
|   |   |   |   |   |   |
|:------:|:------:|:------:|:------:|:-------:|:------:|
|<img width=100 src="./static/images/acknowledgements/ctf.png">|<img width=100 src="./static/images/acknowledgements/sage.png">|<img width=100 src="./static/images/acknowledgements/svai.png">|<img width=100 src="./static/images/acknowledgements/GoogleCloud.png">|<img width=100 src="./static/images/acknowledgements/GoogleLaunchpad.png">|<img width=100 src="./static/images/acknowledgements/ntap.png">|
|<img width=100 src="./static/images/acknowledgements/healx.png">|<img width=100 src="./static/images/acknowledgements/wuxiapp.png">|<img width=100 src="./static/images/acknowledgements/wuxinext.png">|<img width=100 src="./static/images/acknowledgements/vscode.png">|<img width=100 src="./static/images/acknowledgements/docker.png">|


---
other thigns?
requirements 
install/run instructions (make sure all extra files are in the repo et cetera)

talk about the NF Hackathon
