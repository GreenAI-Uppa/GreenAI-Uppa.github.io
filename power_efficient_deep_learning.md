---
title: 
feature_text: |
  ## ACML 2021 WORKSHOP:                Power efficient deep learning  
layout: workshop
feature_image: "/assets/singapore.jpg"
excerpt: "Longer intro"
aside: false 
---

Neural networks (NN) have become the most used family of machine learning algorithms. Among the universality of architectures emerging now, NNs are still prohibitive regarding environmental impact due to electric consumption.

In this workshop, we expect to address these issues, based on both a theoretical and practical deep learning analysis of standard pipeline and new paradigms. The main theoretical discussions lie on how mathematical statistics or recent mathematical models can be applied to learn lighter architectures in order to reduce training and inference. We also propose to use recent softwares like RAPL and nvidia-smi in a dedicated tutorial and competition where the energy consumed by deep learning algorithms will be measured and reduced. 


## Program

**7:00 am (UTC)**
Sébastien Loustau (UPPA) [slides](/seminars/acml_morning_introduction.pdf) 
###  Introduction on Low Power deep learning 


<img src="../images/sebastien.png" align="center" width="200"/>
**Bio** After a PHD thesis defended in 2008, at Institut de Marseille Sebastien worked as Associated professor at Université d’Angers in the lab LAREMA where he defended his Habilitation thesis in 2014. He found the AI start-up LumeanAI in 2015 and the non-profit organization IAPau in 2016. Since 2020, he is researcher at the LMAP at UPPA and found with Paul Gay the GreenAi UPPA Group. His research interest are online learning, mathematical statistics, information theory for machine learning and more recently, in the applications of these activities to deep learning techniques and environmental challenges. For contact, send an email at sebastien[dot]loustau[at]univ-pau.fr

**Abstract** In this introduction, we propose a non-exhaustive survey of classical and recent techniques to reduce training and inference of neural networks. We then present recent advances of [GreenAIUppa](/) in order to learn lighter architectures based on mathematical statistics and the PAC-Bayesian paradigm. We derive a greedy MCMC algorithm that shows good robustness to pruning up to 90% of coefficients.

---

**7:30 (UTC)**
Johannes Lederer (Ruhr-University Bochum)[slides](/seminars/JohannesLederer.pdf) 
### Sparse Deep Learning 

<img src="../images/johannes_lederer.png" align="center" width="200"/>
**Bio** Johannes is Professor of Mathematical Statistics at the Ruhr-University Bochum. After receiving a MSc in Physics, he completed his Doctor of Sciences at ETH Zürich. He then held positions at UC Berkeley, Cornell University, and University of Washington prior to his appointment in Bochum. His research interests include high-dimensional statistics, empirical process theory, and deep learning.

**abstract** Sparsity is popular in statistics and machine learning, because it can avoid overfitting, speed up computations, and facilitate interpretations. In deep learning, however, the full potential of sparsity still needs to be explored. In this presentation, we first discuss sparsity in the framework of high-dimensional statistics and corresponding statistical theories. We then use these insights to further our understanding of sparsity in deep learning.

---

**8:15 (UTC)**
Guillaume Bellec (EPFL)[slides](/seminars/Bellec.pdf) 

### Spiking neural networks 

<img src="../images/guillaume_lebellec_circle.png" align="center" width="200"/> 
**Bio** Guillaume Bellec develops theories to advance our under-standing of brains and intelligent machines. He studied artificial intelligence during his Master in Paris and he completed his PhD with Wolfgang Maass in the Institute for Theoretical Computer Science of TU Graz in Austria. He is now a postdoc with Wulfram Gerstner in the Laboratory of Computational Neuroscience at EPFL in Switzerland. His work is most well-known for showing that powerful artificial intelligence can emerge from simple mathematical models of biologically realistic neural networks. This work is having a direct impact on the development of neuromorphic-hardware for energy efficient artificial intelligence applications.


**Abstract** The brain is a natural inspiration to develop energy efficient
artificial intelligence devices. Yet they are essential principles of
brain computation that are radically different from today's artificial
neural networks models. We will focus here on two of them: (1)
information is transmitted via rare electrical pulses called spikes
and (2) learning mechanisms that are based on local plasticity rules
relying on the local neural activity. This is very different in deep
artificial neural networks where neurons are sending information
synchronously everywhere and learning happens via back-propagation. In
this talk we will survey recent mathematical models enabling deep
artificial intelligence based on spikes and local plasticity rules: it
includes demonstrations that bio-inspired artificial intelligence can
be successful in machine learning benchmarks and reduce the
power-consumption when porting these brain-inspired technologies to
dedicated neuromorphic-chips


---


**9:30 (UTC)** Paul Gay (UPPA)[slides](/seminars/paul_gay_workshop_acml_2022.pdf)
### Green AI Team Tutorial: Energy consumption of AI

<img src="../images/paul.png" align="center" width="200"/>
**Bio** Paul Gay is a researcher at the LMAP. He obtained his phd at the [University of Maine](https://lium.univ-lemans.fr/) in 2014 on unsupervised Audio-visual person identification in broadcast data. Then, he went through a teaching period at the [LIA](https://lia.univ-avignon.fr/) (2015) a Post-doc in computer vision, at [IIT/PAVIS](https://pavis.iit.it/) (2016 - 2018), and worked at the [LumenAI](https://www.lumenai.fr/) on community detection (2019 - 2020). i

**Abstract** The ability of measuring power and consumption of machine learning algorithms is necessary to design new efficient ones. Nowadays, there is a growing interest in the machine learning and IT community for measuring the consumption at different scale, from the AI model to the entire data center. In this talk, we survey recent tools and softwares based on RAPL and NVIDIA-SMI and highlight the dependancy to the hardware considered (CPU, GPU), as well as the different sources of consumption in the architecture of a computer. The final goal is to give to engineers and data scientists the capacity to measure the consumption of deep/machine learning algorithms via the open source software [AIPowerMeter](https://greenai-uppa.github.io/AIPowerMeter/) designed by [GreenAIUppa](/).

--- 
**10:30 (UTC)**   Anne-Cécile Orgeriei (Université de Rennes) [slides](/seminars/ACML_Workshop_2021-Orgerie.pdf)
### Measuring and modeling the energy consumption of ICT distributed systems

<img src="../images/anne_cecile_orgerie_circle.png" align="center" width="200"/>
**Bio** Anne-Cécile Orgerie is research scientist at CNRS, in the IRISA laboratory in Rennes. She got her PhD in 2011 in Lyon. She belongs to the Myriads team, dealing with large-scale distributed systems, Cloud computing and edge infrastructures. Her research interests include measuring, modeling, simulating and improving the energy efficiency of ICT distributed systems. She is currently the director of the working group EcoInfo studying the environmental impact of ICT devices.

**Abstract** ICT distributed systems are increasingly spanning worldwide, with digital services hosted all around the globe and often belonging to complex systems, utilizing many other services and hardware resources themselves. Along with this increase comes an alarming growth of ICT devices and their related energy consumption. Despite the distributed systems' complexity, understanding how they consume energy is important in order to hunt wasted Joules. This talk will deal with measuring the energy consumption of ICT infrastructures, deriving models from these measurements and implementing these models into simulation tools that can be used to experiment new energy-efficient strategies.




