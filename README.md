# Amazon-Reviews-Analysis

A project analyzing product reviews on Amazon

## Introduction

In this analysis, we aim to gain valuable insights from Amazon customer reviews data. These insights can help Amazon to optimize its recommendation algorithms and enhance the overall customer experience on its platform.

## Key Business Questions

- Who are the high-potential users should Amazon recommend products to?
- Which products should Amazon prioritize for promotion and recommendation?
- Is there any difference between the purchasing behaviour of frequent buyers and not frequent buyers?
- Who usually gave more lengthy reviews between frequent and infrequent users?

## Tools and Techniques

Tools and techniques that I used in this project:
- Python/Pandas
- Viz tools: Matplotlib, Seaborn

## Dataset

The Amazon product reviews dataset can be downloaded on [Kaggle](https://www.kaggle.com/datasets/jillanisofttech/amazon-product-reviews) directly or using Kaggle CLI (you will have to get credentials/API token from Kaggle):

```bash
kaggle datasets download -d jillanisofttech/amazon-product-reviews
```

In this notebook, since the dataset file is large (about 300 MB), I stored the dataset on my personal Google Drive and read the dataset directly from there. If you want to rerun this notebook, please choose a method of reading CSV file based on your preference.