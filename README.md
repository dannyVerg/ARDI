# Entity Extraction from AI Research Papers

This project focuses on the automatic extraction of key entities such as tasks, datasets, metrics, and scores from AI research papers. The extracted information facilitates knowledge consolidation, accessibility, and benchmarking for AI models. This code implements entity extraction using the SciBERT model, fine-tuned on a large dataset of scholarly articles to improve performance and generalization.

## Requirements

- Python 3.8 or higher
- PyTorch
- Transformers library
- Pandas
- NumPy

## Usage
To set up the training and prediction environments, download following preprocessed SOTA datasets:

### SciBERT Training on SOTA 
1. https://www.kaggle.com/datasets/httpwwwfszyc/sota-all-ready
2. https://www.kaggle.com/datasets/daniiavergazova/sota-preprocessed-v3/settings

### SciBERT Prediction on SOTA
The training process can be skipped, and a pretrained model can be directly used to predict the results on the preprocessed few-shot SOTA test set. The pretrained model can be downloaded at the following link: https://www.kaggle.com/datasets/httpwwwfszyc/ready-dataset-negfrac0-0-lr3e-5

### Kaggle Notebooks
The notebooks with the necessary datasets and models already linked can be directly used in Kaggle at the following links:
1. **SciBERT Training**: https://www.kaggle.com/daniiavergazova/training-script-scibert
2. **SciBERT Prediction**: https://www.kaggle.com/code/daniiavergazova/prediction-script-scibert
