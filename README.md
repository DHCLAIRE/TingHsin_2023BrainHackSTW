# TingHsin_project_2023BHSTW
---
type: "project" 
date: "2023-05-25"
# Title of your project (we like creative title)
title: "Ngram as syntactic predictor in ESL speech comprehension"

# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [Ting-Hsin Yen]

# Your project GitHub repository URL
github_repo: [NgramMEG_2023BrainHackSTW](https://github.com/DHCLAIRE/NgramMEG_2023BrainHackSTW)

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [ngram, meg, speech comprehension, trf]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "POS ngram model served as the sequencing process of speech comprehension, hence, with the brain response prediction (TRF) corresponds to the surprisal estimated from ngram model, the underlying mechanism of speech comprehension in ESLs could be presented."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background   `What is this??`

Inspired by the [Recurse Centre](https://www.recurse.com/) initiative (formally known as the "hacker school"), Brainhack School was established in 2018 with the mission to train students from multidisciplinary backgrounds to a panoply of reproducible tools for neural data science, using a project-based approach. Following an initial 3-weeks long pilot, a 4th week was added with an intensive bootcamp, so that students could choose what tools to learn more deeply in their projects. As the course became integrated in standard curriculum at different universities, the formula seemed to be working. In order to streamline the different stages of the project, some standard template and milestones needed to be incorporated in a github-based workflow. The "project template" project (which is also our first BHS meta-project) aims at establishing such a standardized template. You can check the following [video](https://youtu.be/PTYs_JFKsHI) where Pierre Bellec gives an overview of the Brainhack school.

<iframe width="560" height="315" src="https://www.youtube.com/embed/PTYs_JFKsHI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Tools

The "project template" project will rely on the following technologies:
 * Regex, to preprocess the text.
 * Ngram model construction, to build and train the ngram model from scratch.
 * Temporal Response Function (TRF), to estimate the corresponding neural activity by convolution model.

### Data

Lab owned MEG data of 13 Mandarin speakers who are ESLs.  
Lab: Brain and Language Lab, Institute of Cognitive Neuroscience, National Central University, Taiwan  
MEG data: collected through MEG in Academia Sinica, Taiwan.

### Deliverables

At the end of this project, we will have:
 - A functional Ngram model and Instructions about how to build the Ngram model from your own corpus, see [BHSTW_POSngram_COCA](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/BHSTW_POSngram_COCA.py)
 - A preprocess steps, see [BHSTW_POStagged_preprocess](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/BHSTW_POStagged_preprocess.py)
 - MEG preprocessing commands and instructions from [MNE-Python](https://mne.tools/stable/auto_tutorials/preprocessing/40_artifact_correction_ica.html#sphx-glr-auto-tutorials-preprocessing-40-artifact-correction-ica-py)
 - Modified TRF [procedure](https://github.com/DHCLAIRE/TingHsin_project_2023BHSTW/blob/main/BHSTW_TRFs_produce-estimate_LTTC_ESLs.py) originated from [Eelbrain/Alice](https://github.com/Eelbrain/Alice)

## Results

### Progress overview

The project was a idea combination experiment initiated by Ting-Hsin, based on the research by Brennnan & Hale (2019) and Brobecj

swiftly initiated by P Bellec, based on the existing template created in 2019 by Tristan Glatard and improved by different students. It was really not that hard. Community feedback is expected to lead to rapid further improvements of this first version.

### Tools I learned during this project

 * **Regex reference** Ting-Hsin learned how to choose the correct regex command to narrow down the process steps.
 * **Ngram model calculation** In order to swtich from comman semantic ngram model into POS ngram model, .
 * **Project content** Through the project reports generated using the template, it is possible to learn about what exactly the brainhack school students are working on.

### Results

#### Deliverable 1: POS Ngram model

See [BHSTW_POSngram_COCA.py](https://github.com/DHCLAIRE/NgramMEG_2023BrainHackSTW/blob/main/BHSTW_POSngram_COCA.py)

#### Deliverable 2 (Future aim): Temporal Responce Function (TRF)

To be announced.

#### Deliverable 3 (Future aim): Syntactic surprisal as predictor in speech comprehension process (Statistical results)

To be announced,

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni


## Conclusion and acknowledgement

The BHS team hope you will find this template helpful in documenting your project. Developping this template was a group effort, and benefitted from the feedback and ideas of all BHS students over the years.

You can also make submit your project to neurolibre https://neurolibre.org/. It is a preprint server for interactive data analyses. It is tailored for publishing interactive neuroscience notebooks that can seamlessly integrate data, text, code and figures.The submission instructions can be found here https://docs.neurolibre.org/en/latest/index.html and the jupyter book docs there https://jupyterbook.org/intro.html.

