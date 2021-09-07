---
title: "DLO3"
excerpt: "Predicting summertime ozone using a deep learning model<br/><img src='/images/500x300.png'>"
collection: portfolio
---

This project was undertaken Summer 2021. Being guided by Professor Dylan Jones and senior PhD student Tai-Long He, both at the University of Toronto. I was sitting in London (not the one in Ontario), and was working "remotely" with the 5 hour time difference, due to COVID-19. Fortunately, I was still able to attend the weekly group meetings on Thursdays 7pm, with a cup of tea. I learnt about the group members' research, all falling broadly under Atmospheric Modelling and Composition.

# Research

Following the work of Tai-long [1], I further investigated a deep learning model which was used to predict summertime ozone concentration over the US. We were interested in what gave the model it's temporal skill, and why it was able to capture the dynamics 

#### Background - Why is ozone important?

Tropospheric (ground-level/near-surface) ozone, is a major air pollutant and a greenhouse gas. As an air pollutant, ozone risks those who are already have a compromised respiratory systems (e.g. asthma), outdoor workers and children. As a greenhouse gas, it is much more **potent greenhouse gas than CO2****


### Why is this a tricky problem?

Ozone is not directly emitted by anthropogenic activity. Instead, it's produced in the atmosphere as a chemical reaction, composed of NOx (nitrous oxides), VOCs (volatile organic compounds) and UV radiation. Due to the photochemical reaction, ozone concentrations are high during summertime. This reaction, however is complicated and non-linear. 

A recent example demonstrating this complexity would be the ozone concentration during the COVID-19 pandemic. When lockdown's been imposed in several countries (China, India, US, UK), NOx emissions from transport (and indirectly other sectors)* were reduced. However, this would not immediately be obvious in the ozone concentrations.

_Atmospheric models used to simulate the distribution of ozone typically do not reproduce the observed long-term trend in tropospheric ozone. Furthermore, these models tend to overestimate summertime surface ozone abundances in the United States. [1]


### The model

Being inspired by Shi et al, [2] Tai-long devised a hybrid CNN-LSTM model, to capture spatial and temporal variation

### Regional analysis

My results

### Future work

SHAP



## References

[1] - see Tailong repo DLO3 with arXiv paper (forked)

[2] - cite precipitation now-casting paper

[3] - Ozone during the COVID era
