# Textstellar 🌌

Capability and skill mapping using transformer-based/contextual text embeddings.

## Overview

On a high level, the `Textstellar` pipeline broadly consists of three modules:

1. Semantic Ranking:
    - Given a definition for "X" (a list of *reference* sentences capturing X), which could be a theme, challenge, or a concept, we find the top-K related items based on their semantic similarity. The reference sentences could be either handcrafted, or GPT-3 prompted
    - We apply this to finding relevant research outcomes (and researchers) that are most salient for a given excercise

2. Topic Clustering:
    - Perform unsupervised clustering for topic discovery
    - Using Topic Coherence to automatically select the optimal cluster size etc.
3. Visualization:
    - Plot highest matching outputs and their corresponding authors
    - Generate a 2D "night sky" visualization of topics

## Setup 
1. Clone this repo and get started with `textstellar.ipynb` notebook to use on your own dataset
2. Preferably run on a GPU (faster; recommended: Google Colab)
3. Replace all system path(s) as needed

Most importantly, explore the low-dimensional semantic space—at your leisure.

Click [here](textstellar.com/climate_change) for a live demo.