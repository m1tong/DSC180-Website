---
layout: project
title: Full Project
subtitle: Congestion Prediction in IC Design using Graph Neural Network
permalink: /project/
description: A growing collection of your cool projects.
nav: true
nav_order: 3
date: 2024-03-16

profile:
  align: left
  image: gnn_graph.gif
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Something</p>
    
giscus_comments: false
featured: true

authors:
  - name: Michelle Tong
    url: "https://m1tong.github.io/"
    affiliations:
      name: HDSI, UCSD
  - name: Yuyang Pang
    url: "https://www.linkedin.com/in/yuyang-pang-667285241/"
    affiliations:
      name: HDSI, UCSD
  - name: Hang Liu
    url: "https://www.linkedin.com/in/hang-liu-2b4b371aa/"
    affiliations:
      name: HDSI, UCSD
  - name: Vivian Chen
    url: "https://www.linkedin.com/in/vnchen01/"
    affiliations:
      name: HDSI, UCSD
  - name: Lindsey Kostas
    affiliations:
      name: Qualcomm Inc.
  - name: Guillaume Shippee
    affiliations:
      name: Qualcomm Inc.
  - name: Lea Hagen
    affiliations:
      name: Qualcomm Inc.
    
bibliography: 2018-12-22-distill.bib

# Optionally, you can add a table of contents to your post.
# NOTES:
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
#   - we may want to automate TOC generation in the future using
#     jekyll-toc plugin (https://github.com/toshimaru/jekyll-toc).
toc:
  - name: Introduction
  - name: Methodology
    subsections:
      - name: Dataset
      - name: Feature Selection and Engineering
  - name: Graph Neural Network
    subsections:
      - name: GCN Model
      - name: GAT Model
  - name: Side-by-side Comparison
  - name: Analysis
  - name: References
    # if a section has subsections, you can add them as follows:
    # subsections:
    #   - name: Example Child Subsection 1
    #   - name: Example Child Subsection 2

# Below is an example of injecting additional post-specific styles.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }
---

## Introducion

Predicting congestion in IC design is a critical yet challenging task. Congestion occurs when excessive wiring or routing is required in certain regions of the chip layout, often resulting from suboptimal floor planning or high cell density. This can lead to significant issues, such as timing discrepancies, crosstalk, increased power consumption, reduced reliability, and high production costs. Early prediction and mitigation of congestion are thus essential to avoid these complications.

Current optimization tools for calculating congestion are extremely time-consuming given the complexity of modern chips. A machine learning model that utilizes the existing information of netlists and their congestion can accelerate the optimization process in IC design. Predicting congestion is generally complex due to the intricate nature of IC layouts. This project seeks to address this challenge by leveraging Graph Neural Networks (GNNs), which hold promise due to their ability to model complex relationships and interactions in graph-structured data. 

Related Work: The approach of using graph neural networks in congestion prediction has been explored in recent works. Kirby et al. utilized deep Graph Attention Networks on the hypergraph representation of IC designs to predict congestion <d-cite key="Kirby2019CongestionNet"></d-cite>. This graph neural network-based approach has outperformed existing methods of congestion prediction by accuracy and speed. Moreover, GNNs can predict congestion on a per-cell level and don't require any placement information.

Given the advantages of GNNs in circuit congestion prediction, our project aims to explore similar GNN architectures from Kirby et al.'s work on the NCSU-DigIC-GraphData dataset and compare the performance of different GNN architectures. NCSU-DigIC-GraphData has a much smaller scale compared to the netlists used in Kirby et al.'s paper, which has roughly 50 million cells from tens of designs. Experimenting with graph neural networks on different sizes of netlists can give us insights into how well GNNs scale and how different GNN architectures perform on a smaller-scale dataset.

--- 
## Methodology
### Dataset

### Feature Selection and Engineering

---

## Graph Neural Network


### GCN Model
### GAT Model

--- 

## Side-by-side Comparison

--- 

## Analysis

---
## References

  
