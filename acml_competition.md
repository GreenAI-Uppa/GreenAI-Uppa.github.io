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

A competition where participants optimize both their energy consumption and the generalization ability of their models over the CIFAR-10 dataset with common GPU architectures.


**A prize of 1000 euros** will reward the best teams. 

#### Why 

The growth of AI powered services hosted on gpu servers has been so far guided by accuracy performance, although it is likely that the a better compromis in terms consumes Joules should be possible. 

Unlike previous competitions on specific low power devices to enhance portability on smartphones or raspberry pi embedded in Unmanned vehicles, the idea of this competition is to monitor the consumption on standard workstation’s processors and GP-GPU as these are the most commonly used devices and are responsible for the majority of energy consumption and carbon footprint in the AI/deep learning field. 

#### Evaluation

The best algorithm will be promoted for different levels of accuracy. The different thresholds are **90%**, **95%**, and **99%**. 
TODO Check with the values of benchmark algorithms to decide the threshold

For instance: if three algorithms have the follwing performances: 
- Algo1 : 96.5% accuracy and 150Kj of energy consumption
- Algo2 : 92.5% accuracy and 10Kj of energy consumption
- Algo3 : 98.5% accuracy and 5000Kj of energy consumption

Then, Algo1 will be ranked first in the **95%** category, Algo3 will be second, and Algo2 will be ranked first in the **90%**

The [IAPowerMeter](https://github.com/GreenAI-Uppa/IAPowerMeter) will be used to measure the amount of energy used by the program inference. You can already use it to check how good you are.


In practice, we will run 200 iterations of predicting the full cifar10 dataset and sum the CPU (total_intel_power) and GPU (nvidia_draw_absolute) energy consumptions. If you want to test the procedure on your server, be carefull, that your program must be the only one running when you are doing the measurement.

### Submission
Every team should supply:

- a docker with your submission, so that we can run it on our server, and 

- a two page description of your method. The winners will present their approach at the workshop in a 5 minutes presentation.


You can check our template submission for more practical information. TODO add link to the repo with the samples

The website will be updated with a link to a submission procedure later this month. 

#### Important dates

- Submission deadline : 12/11/2021
- Results and online workshop : 17/11/2021

