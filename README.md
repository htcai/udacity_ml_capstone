# Capstone Project

In this project, BERT is fine-tuned on the annotated Twitter data for prescription medication (PM) abuse to detect PM abuse events. This serves as part of the NIH-funded R01 project [MINING SOCIAL MEDIA BIG DATA FOR TOXICOVIGILANCE: AUTOMATING THE MONITORING OF PRESCRIPTION MEDICATION ABUSE VIA NATURAL LANGUAGE PROCESSING AND MACHINE LEARNING METHODS](https://projectreporter.nih.gov/project_info_description.cfm?aid=9577760&icde=41016676&ddparam=&ddvalue=&ddsub=&cr=1&csb=default&cs=ASC&pball=) (Project number: 1R01DA046619-01).

## Run Environment

The code was run on Google Colab using the free instance of Tesla GPU (16 GB RAM).

## Requirements

* keras
* keras-bert
* tabulate
* tensorflow==1.15

## Files

* udacity_ML_capstone.ipynb
* report.pdf

To obtain the following files, please contact Abeed Sarker (abeed@dbmi.emory.edu) and Haitao Cai (hcai.pku@gmail.com).
* train.tsv
* validation.tsv
* test.tsv
* SVM_preds.tsv

## Pre-trained model

The pre-trained BERT model will be downloaded when running the Jupyter notebook, if not already present.
