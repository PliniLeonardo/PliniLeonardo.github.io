---
title: "PREGO: online mistake detection in PRocedural and EGOcentric Videos"
collection: publications
category: conferences
permalink: /PREGO
authors: Alessandro Flaborea, Guido Maria D’Amely Di Melendugno, Leonardo Plini, Luca Scofano, Edoardo De Matteis, Antonino Furnari, Giovanni Maria Farinella, Fabio Galasso
excerpt: "This paper proposes PREGO, the first online one-class classification model for mistake detection in procedural egocentric videos."
venue: 'CVF Computer Vision and Pattern Recognition Conference (CVPR)'
publication: IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)
date: 2024-4-29
year: '2024'
paperurl: 'https://arxiv.org/abs/2404.01933'
url_paper: 'https://arxiv.org/abs/2404.01933'
codeurl: 'https://arxiv.org/abs/2404.01933'
image: '/Users/leonardoplini/Desktop/repository github/PliniLeonardo.github.io/images/image-alignment-300x200.jpg'
---

![Teaser Prego](/Users/leonardoplini/Desktop/repository github/PliniLeonardo.github.io/images/image-alignment-300x200.jpg)

Promptly identifying procedural errors from egocentric videos in an online setting is highly challenging and valuable for detecting mistakes as soon as they happen. This capability has a wide range of applications across various fields such as manufacturing and healthcare. The nature of procedural mistakes is open-set since novel types of failures might occur which calls for one-class classifiers trained on correctly executed procedures. However no technique can currently detect open-set procedural mistakes online. We propose PREGO the first online one-class classification model for mistake detection in PRocedural EGOcentric videos. PREGO is based on an online action recognition component to model the current action and a symbolic reasoning module to predict the next actions. Mistake detection is performed by comparing the recognized current action with the expected future one. We evaluate PREGO on two procedural egocentric video datasets Assembly101 and Epic-tent which we adapt for online benchmarking of procedural mistake detection to establish suitable benchmarks thus defining the Assembly101-O and Epic-tent-O datasets respectively. The code is available at [GitHub](https://github.com/aleflabo/PREGO)


<!-- include image -->
![An image](images/teaser_prego.png)