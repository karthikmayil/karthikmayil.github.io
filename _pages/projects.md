---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Machine Learning on Physics-Based Model Generated Data

I'm working on a project ([Repository](https://github.com/karthikmayil/lfp_graphite_synthetic_data)) that uses data described in Dubarry and Beck's 2020 Journal of Power Sources article, [Big data training data for artificial intelligence-based Li-ion diagnosis and prognosis](https://www.sciencedirect.com/science/article/pii/S0378775320311101).

The data is model-generated ("synthetic") C/25 charge curves for a graphite-LFP cell. Three different degradation modes (loss of LFP, loss of graphite, and loss of lithium inventory in the electrolyte) are simulated. The data can be found [here](https://data.mendeley.com/datasets/bs2j56pn7y/1)

I'm using these data to train machine learning models for two purposes:
1. Parameter estimation. ML trained on physically constrained training sets like the one above can serve as faster surrogate models to physics-based models, as described [here](https://iopscience.iop.org/article/10.1149/1945-7111/abec55) and [here](https://pubs.acs.org/doi/10.1021/acsenergylett.1c00194).
2. Classification of degradation modes

This work is an opportunity for me to learn about and implement ML algorithms. For instance, I explore the role of the nature of the training data, the size of the training data, and the preprocessing steps on performance of a Deep Neural Network for parameter regression. I also take some inspiration from [Severson and Attia's work](https://arxiv.org/abs/2101.01885) on transforming and featurizing voltage profiles as inputs for ML models, and using interpretable ML.


## BatteryDEV: Lifetime prediction

I participated in a hackathon of sorts organized by [BatteryDEV](https://battery.dev/) and [Battery Associates](https://battery.associates/), where I worked with a team to build a model to predict the remaining capacity of an electric bus battery. [Post](https://www.linkedin.com/feed/update/urn:li:activity:6772834980855848960/).
