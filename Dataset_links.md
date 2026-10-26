# VulSight --- Dataset Resources

This document provides the Google Drive links to the datasets used in
the VulSight project for tokenizer training, RoBERTa pre-training, and
vulnerability-detection fine-tuning.

## Dataset Links

### 1. Fine-Tuning Dataset

**Purpose:** Supervised fine-tuning and evaluation of the VulSight
vulnerability classification models.

[Open the fine-tuning dataset
folder](https://drive.google.com/drive/folders/1Mc5k9bx0bJbnrtfn_i9_ssuivuWZeQ0j?usp=sharing)

### 2. Pre-Training Dataset

**Purpose:** Source-code data used for RoBERTa masked language modeling
(MLM) pre-training.

[Open the pre-training dataset
folder](https://drive.google.com/drive/folders/1Sooz_Hu6sxW5EDF9W5PScgpwAQrGTLK7?usp=sharing)

### 3. Tokenizer Training Dataset

**Purpose:** C/C++ source-code corpus used to train or prepare the
tokenizer.

[Open the tokenizer training dataset
file](https://drive.google.com/file/d/1tPozFCLKQhYSGFcU4UMI_qJuJmtlxOLG/view?usp=sharing)

## Workflow Overview

The datasets correspond to the following stages of the VulSight
pipeline:

1.  **Tokenizer training:** Prepare the source-code corpus and tokenizer
    vocabulary/merges.
2.  **RoBERTa pre-training:** Use the pre-training corpus for masked
    language modeling (MLM).
3.  **Fine-tuning:** Fine-tune and evaluate the VulSight-CNN and
    VulSight-MLP vulnerability classifiers on the selected labelled
    datasets.

## Access Notes

-   Open the links using a Google account that has permission to access
    the files.
-   If a link does not open, request access from the dataset owner.
-   Check each dataset's accompanying documentation for its structure,
    labels, splits, and any usage or licensing requirements before
    running experiments.

## Reproducibility

For reproducible experiments, record the dataset version, preprocessing
steps, train/validation/test split, tokenizer version, model
configuration, and random seed used for each run.
