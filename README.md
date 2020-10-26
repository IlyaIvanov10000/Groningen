![alt text](https://github.com/igemsoftware2020/Groningen/blob/main/RootPatch_icon.png)

# iGEM-Groningen
The population dynamics models focusing on the Globodera pallida nematode and the (RootPatch) bacterial population on the roots. 

## RootPatch - What is it?

**RootPatch** is an innovative technology developed by iGEM-Groningen to protect the potato plants from the _Globodera pallida_ nematodes. **RootPatch** is an easy-to-use, targeted, and environmentally friendly product for crop protection in agriculture. It is a bacterial (_Bacillus mycoides_) community that forms a biofilm-like structure on the surface of potato roots. The bacteria will produce and secrete NLP-14a, a neuropeptide-like protein, native to _G. pallida_. After taking up NLP-14a, it will reverse the chemoattraction of the nematodes to the roots, repelling the harmful parasites away from the plant. 

## RootPatch - Motivation

Potatoes are beloved in the Netherlands, being part of many national dishes. Moreover, potatoes are an important export crop for the Dutch economy. We were worried to realize that the _G. pallida_ problem is very prominent in the Netherlands compared to other EU countries. The current measures include crop rotation, use of nematicides, and genetic breeding but these approaches are either neglected, are harmful to the environment, or take a very long time to implement. Therefore, our aim is to develop an efficient and reliable crop protection technology that is least harmful to the soil biome and the environment. 

## Modelling approach

![alt text](https://github.com/igemsoftware2020/Groningen/blob/main/Model_overview.png)

Our modelling efforts this year were directed towards understanding the dynamics of the nematode populations and their effect on the plant, growth and robustness of _B. mycoides_ biofilm, and the ability of RootPatch to effectively protect the plant. We reason that the best way to describe such systems is with ordinary differential equations (ODEs). Our models take great care in simulating the environmental factors to make the most accurate predictions based on the different enviornmental scenarios. They will be useful for people who want to predict the impact of various soil pests on the health of a plant or for the microbiologists who wish to study the biofilm growth. 

### Bacteria population model

When your project involves establishing bacterial biofilms in the field conditions with no option for future monitoring, it is important to predict what happens to it throughout the season. With this model we look at factors like water activity, temperature, and intraspecific competition that have a potential to affect the growth and maintenance of the **RootPatch** biofilm. This model allows you to visualize how the density of your bacteria changes throughout the season but also how various factors affect the final bacterial density. 

### Nematode population model

Understanding the seasonal dynamics of _G. pallida_ populations was crucial to us to implement the impact of **RootPatch** into the system. The model was built up from an existing data, and standard values were taken where the experimental ones were not available. This model can be used by plant experts and people interested in ecology to predict the spread and the damage of a particular biological pest. 

### Software 

Our models were developed either with Mathematica (Bacterial model) or with Python (Nematode model). 

## Attributions

We give our special thanks to the people who helped us develop these models with their professional expertise and support:

Sander van Doorn (University of Groningen, the Netherlands)
Matthew Biggs (AgBiome, the US)



**We hope that our work will help someone in the future. Enjoy!**
