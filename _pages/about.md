---
layout: about
title: about
permalink: /
subtitle: <a href='https://datascience.ucsd.edu/'>UC San Diego, Halıcıoğlu Data Science Institute</a>

profile:
  align: right
  image: gnn_graph.gif
  image_circular: false # crops the image to make it circular
  more_info: >

news: false # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---
[Authors](https://m1tong.github.io/DSC180-Website/contributors/): Michelle Tong, Yuyang Pang, Hang Liu, Vivian Chen

[Mentors](https://m1tong.github.io/DSC180-Website/contributors/): Lindsey Kostas, Guillaume Shippee, Lea Hagen

<a href='https://m1tong.github.io/DSC180-Website/project/'><img src='https://img.shields.io/badge/Read_Full_Project-HTML-green'> <a href=''><img src='https://img.shields.io/badge/Report-PDF-blue'> <a href=''><img src='https://img.shields.io/badge/Poster-PDF-red'>

---

# Abstract
Congestion prediction is a crucial part of the design process of Integrated Circuits (IC). It allows chip designers to discover areas that have excessive routing demand and optimize the circuit accordingly. This paper presents insights into the use of Graph Neural Networks for early congestion prediction in IC designs. Utilizing the NCSU-DigIC-GraphData dataset, which includes 13 small netlists with distinct congestion characteristics, our methodology includes node feature engineering, multi-graph train-test split, and a comparison between model architectures, which features Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs). Results show that Graph Neural Networks do not scale well on small netlists that only contain a few thousand nodes. GATs can perform better than GCNs but have significantly longer training time. Moreover, GRC-based prediction models are inferior to node-based prediction models.



