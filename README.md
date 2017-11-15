# Cleaning dirty documents
[Kaggle Competition Homepage](https://www.kaggle.com/c/denoising-dirty-documents)

### Aim
Improve the quality/apperance of documents to make them readable.

### Data
The data for this competition can be obtained through Kaggle page for this competition. However, they use the reduced dataset from NoisyOffice "https://archive.ics.uci.edu/ml/datasets/NoisyOffice"

### Analysis

I first established a benchmark by not editing the images, and using them as it is, and then used thresholding for finding the clean images. The statistics obtained are as follows: 

Median

| Measure     | Value            |
| :---------- | :--------------- |
| threshold   | 0.6347           |
| train_error | 0.1994           |
| test_error  | 0.24312          |
