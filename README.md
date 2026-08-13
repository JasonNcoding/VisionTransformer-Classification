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
pip install -r requirements.txt
```

## Usage

[Order to run the notebooks, e.g.:]
1. `01_preprocessing.ipynb` — prepares and splits the dataset
2. `02_train.ipynb` — trains the ViT model
3. `03_evaluate.ipynb` — evaluates on the held-out test set

## Results

Achieved a total accuracy of 96.65% accuracy on the test set against a 80% of normal CNN


## Future Improvements

- Try different patch sizes and architecture 
- Add key metric to track
