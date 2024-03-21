# COGS118B Project: Discovering Semantic Patterns In Word Difficulty Using Clustering

## Abstract 

This project seeks to find underlying patterns in English words that can contribute to its difficulty. We define word difficulty as the level of complexity in understanding a particular word. Although word difficulty is largely subjective and experience-dependent, we would like to examine whether certain semantic features in English words also carry independent and/or latent significance to difficulty. In fact, this project will build off from another study, the *Word Difficulty Prediction Using Covolutional Neural Networks study* (Basu, Garain, and Naskar, 2019)<a name="avishek"></a>[<sup>[1]</sup>](#avisheknote), that similarly aligns with our project.

Our project employs exploratory data analysis and machine learning algorithms to find critical semantic patterns contributing to word difficulty using the study's corpus dataset that also contains semantic features, such as `Length`, `Log_Freq_HAL`, and `I_Zscore`. In our case, we define `I_Zscore` as a metric of word difficulty (0 being easy to understand and 1 being hard to understand). This project attempts to find underlying patterns using various unsupervised learning clustering algorithms, yet our findings were unfortunately poor based on silhouette score metrics. However, since these silhouette score metrics were similarly and consistently low, we concluded that our project was limited by the relatively small corpus dataset and unaccounted external factors that could also contribute to word difficulty.

## Getting Started

This project was ran both on Datahub (UCSD) and locally. To install and run this project locally, please install the required dependencies.

```
pip install -r requirements.txt
```

## Notebook

* Code: [FinalProject_groupXXX.ipynb](FinalProject_groupXXX.ipynb)
* [Code PDF Version](notebook.pdf)