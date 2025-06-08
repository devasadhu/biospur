# BioSpur

**BioSpur** is a self-supervised learning project focused on wildlife species classification using camera trap images.  
The name combines *Bio* (biology) and *Spur* (German for track or trail), reflecting the project's goal of tracking biodiversity through AI.

## Project Overview

Wildlife conservation efforts often rely on camera trap data to monitor animal populations. However, labeled data is limited and costly to obtain.  
BioSpur leverages **self-supervised learning (SSL)** techniques, such as SimCLR or DINO, to train models on large amounts of unlabeled camera trap images, enabling efficient species classification with minimal annotations.

## Features

- Uses state-of-the-art SSL methods for representation learning
- Applies to real-world ecology datasets (e.g., Snapshot Serengeti)
- Designed for low-label, low-resource environments
- Open-source with step-by-step notebooks and demo app

## Dataset

The primary dataset used is the Snapshot Serengeti camera trap dataset, publicly available at [https://lila.science/datasets/snapshot-serengeti](https://lila.science/datasets/snapshot-serengeti).

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/BioSpur.git


2. Install dependencies:
pip install -r requirements.txt

3. Start with the notebook notebooks/data_explore.ipynb to explore the dataset.
