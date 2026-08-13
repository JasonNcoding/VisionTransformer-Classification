## Overview

Image classification project built around a Vision Transformer (ViT) architecture, covering data preprocessing, model training, and evaluation in Jupyter notebooks.

## How It Works

- **Data preprocessing** — resizing, normalization
- **Model** — a Vision Transformer splits each image into fixed-size patches, embeds them as a token sequence, and applies self-attention across patches instead of convolutional filters
- **Training** — PyTorch

## Tech Stack

- Python, Jupyter Notebooks
- PyTorch

## Setup & Installation

```bash
git clone https://github.com/JasonNcoding/VisionTransformer-Classification.git
cd VisionTransformer-Classification
```

## Usage
`ViT_Classification_Workspace.ipynb` — prepares and splits the dataset

## Dataset

This dataset contains images of animals across 20 different classes, totaling more than 150GB in size.

## Results

Achieved a total accuracy of 96.65% accuracy on the test set against a 80% of normal CNN


## Future Improvements

- Try different patch sizes and architecture 
- Add key metric to track
