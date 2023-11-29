# Multi-class Classifications  of Malicious URLs using Deep Learning 
SCS 3546 Deep Learning

Jupyter Notebooks:
* [Main Experiment](https://nbviewer.org/github/quickheaven/scs-3546-deep-learning/blob/e2a7056f56934157f64d9585e623204954355812/Multiclass_Classification_of_Malicious_URL.ipynb)

Team members:

| Name | Github Repo |
| --- | --- |
| Arjie Cristobal  | https://github.com/quickheaven |


# Introduction
Artificial Intelligence (AI) and cybersecurity are two of the most rapidly growing sectors in the technology industry.
The global AI in cybersecurity market was valued at \$19.2 billion  in 2022 , and is projected to reach \$154.8 billion by 2032, growing at a CAGR of 23.6% from 2023 to 2032.
The future growth of both AI and cybersecurity is promising and will be critical in the future.

# Objective
This study will explore a lightweight approach to identify and classify malicious URL using deep learning via Keras.

# Dataset

### URL dataset (ISCX-URL2016)

**University of New Brunswick** \
Canadian Institute for Cybersecurity

* Mohammad Saiful Islam Mamun, Mohammad Ahmad Rathore, Arash Habibi Lashkari, Natalia Stakhanova and Ali A. Ghorbani, "Detecting Malicious URLs Using Lexical Analysis", Network and System Security, Springer International Publishing, P467--482, 2016.

Link: [URL dataset (ISCX-URL2016)](https://www.unb.ca/cic/datasets/url-2016.html)

### Loading and Preparing the dataset

This study reused the [UrlDatasetLoader](https://nbviewer.org/github/quickheaven/scs-3253-machine-learning/blob/977a523a096097b350ec78cfcfc7357142e0fe1e/loader_nb.ipynb) from the Machine Learning (ML) project [Detection and categorization of malicious URLs](https://quickheaven.github.io/scs-3253-machine-learning/) for data cleaning and preparation. It is responsible on handling Null and NaN values, feature selections and anomaly detection.

The prepared dataset is then exported to CSV files and uploaded to Deep Learning Git repository for use in training.

**Types of Malicious URLs**
* Defacement
* Benign
* Phishing
* Malware
* Spam


## Presentation
<a href="https://github.com/quickheaven/scs-3546-deep-learning/blob/e2a7056f56934157f64d9585e623204954355812/Multiclass%20Classification%20of%20Malicious%20URLs%20using%20DL_v2.pptx">
	<img src="./images/Presentation_Front.PNG" width="800" height="480" />
</a>




