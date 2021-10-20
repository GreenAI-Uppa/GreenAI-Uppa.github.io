---
title: 
feature_text: |
  ## Efficient Deep Learning Competition
  ###  Be low power on cifar
layout: workshop
feature_image: "/assets/ossau_lurien.png"
excerpt: "Longer intro"
aside: false 
---

Submit your algorithm, and be ranked according to your energy consumption.

#### What

A competition where participants record their energy consumtion in order to optimize the generalization ability of NNs over the CIFAR-10 dataset.

#### Why 

Unlike previous competitions on specific low power devices to enhance portability on smartphones or raspberry pi embedded in Unmanned vehicles, the idea is to monitor the consumption on standard workstation’s processors and GP-GPU as these are the most commonly used devices and are responsible for the majority of energy consumption and carbon footprint in the AI/deep learning field. 

#### Evaluation
The best algorithm will be promoted for different levels of accuracy. The different thresholds are **90%**, **95%**, and **99%**. 

For instance: if three algorithms have the follwing performances: 
- Algo1 : 96.5% accuracy and 150Kj of energy consumption
- Algo2 : 92.5% accuracy and 10Kj of energy consumption
- Algo3 : 98.5% accuracy and 5000Kj of energy consumption

Then, Algo1 will be ranked first in the **95%** category, Algo3 will be second, and Algo2 will be ranked first in the **90%**

The [https://github.com/GreenAI-Uppa/IAPowerMeter](IA Power Meter) will be used to measure the amount of energy used by the program inference. You can already use it to check how good you are.

Keras or pytorch are the same? but we allow for any library as some useful features such as binary networks might not be well supported
Evaluation is a tricky process, as so many things are coming into account, and 
We reserve the right to modify the ranking if the paper supports with enough evidence that the solution is interesting

Not allowing cloud or external, everything must run on our machine


### submission
Every team should supply:
- a docker with your submission, so that we can run it on our server. 
- a two page description of your method. The winners will present their approach at the workshop in a 5 minutes presentation.


#### Important dates

- Submission deadline : 12/11/2021
- Results and online workshop : 17/11/2021

