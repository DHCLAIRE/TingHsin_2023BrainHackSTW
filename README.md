# TingHsin_project_2023BHSTW

**Title**: "Ngram as syntactic predictor in ESL speech comprehension"

**Type**: "project"

**Date**: "2023-05-25"

Collaborator names: [Ting-Hsin Yen]

github_repo: [TingHsin_project_2023BHSTW](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/tree/main)

### Website URL:
website:

### 4 keywords
tags: [ngram, meg, speech comprehension, trf]

### Project summary
summary: "POS ngram model served as the sequencing process of speech comprehension, hence, with the brain response prediction (TRF) corresponds to the surprisal estimated from ngram model, the underlying mechanism of speech comprehension in ESLs could be presented."

image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background   

Inspired by [Brennan & Hale (2019)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6334990/pdf/pone.0207741.pdf) and [Brodbeck et al., (2021)](https://www.biorxiv.org/content/biorxiv/early/2022/11/17/2021.08.01.454687.full.pdf), which used multiple auditory and linguistic features within the stimuli to apply to temporal response function, the convolution-model-based model, as the new alternative approach to explore and assess the process of speech comprehension. 


### Tools

The "Ngram & MEG" project will rely on the following technologies:
 * Regex, to preprocess the text.
 * Ngram model construction, to build and train the ngram model from scratch.
 * Temporal Response Function (TRF), to estimate the corresponding neural activity by convolution model.

### Data

Lab owned MEG data of 13 Mandarin speakers who are ESLs.  
Lab: Brain and Language Lab, Institute of Cognitive Neuroscience, National Central University, Taiwan  
MEG data: collected through MEG in Academia Sinica, Taiwan.

### Deliverables

At the end of this project, we will have:
 - A functional Ngram model and Instructions about how to build the Ngram model from your own corpus.
 - A POS tagged texts preprocess steps.
 - MEG preprocessing commands and instructions from [MNE-Python](https://mne.tools/stable/auto_tutorials/preprocessing/40_artifact_correction_ica.html#sphx-glr-auto-tutorials-preprocessing-40-artifact-correction-ica-py)
 - Modified TRF procedure originated from [Eelbrain/Alice](https://github.com/Eelbrain/Alice)

## Results

### Progress overview

The project was experimental project to combine research method of [Brennan & Hale (2019)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6334990/pdf/pone.0207741.pdf) and [Brodbeck et al., (2021)](https://www.biorxiv.org/content/biorxiv/early/2022/11/17/2021.08.01.454687.full.pdf). 

### Tools I learned during this project

 * **Regex reference** Ting-Hsin learned how to choose the correct regex command to narrow down the process steps.
 * **Ngram model calculation** In order to swtich from comman semantic ngram model into POS ngram model, .
 * **Project content** Through the project reports generated using the template, it is possible to learn about what exactly the brainhack school students are working on.

### Results

#### Deliverable 1: POS Ngram model

See [BHSTW_POSngram_COCA.py](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/BHSTW_POSngram_COCA.py)

#### Deliverable 2 : A POS tagged texts preprocess steps.

See [BHSTW_POStagged_preprocess.py](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/BHSTW_POStagged_preprocess.py)

#### Deliverable 3 : MEG preprocessing commands and instructions from MNE-Python

See [LTTC_ESLs_MEG_preprocess.ipynb](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/LTTC_ESLs_MEG_preprocess.ipynb)

#### Deliverable 4 (Future aim) : Modified TRF procedure originated from [Eelbrain/Alice](https://github.com/Eelbrain/Alice)

See [procedure](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/BHSTW_TRFs_produce-estimate_LTTC_ESLs.py) 


## Conclusion and acknowledgement

There's still some modification on the Ngram model as well as the neural data analysis using TRF, even though, the owner of this repo hope you will find this template helpful in conducting your project.

