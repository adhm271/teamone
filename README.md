# teamone
_Although this team's name is one, they understand that there are likely multiple etiologies for NF, and will tease them out!_

---

## GOAL: 
Our goal is to classify and predict responses to a drug based on features like X, Y, Z. We then aimed to correlate the drug targets with relevance in gene expression (RNA-seq) and patient genotypes (WGS) @icon-fa-flask






---

### What is Neurofibromatosis? 

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


##### 2. Create off-the-shelf machine learning models as well as a simple multi-layer perceptron


##### 3. Interpretint the results


##### 4. Correlate the gene targets of drugs with their relevance in RNA-seq and WGS data 

