# Home buyer’s guide to Airbnb: NYC
As a long-time fan of Starbucks’ rewards system (gives me free breakfast every now & then 🥪), I was curious about it worked under the hood. Specifically, there are probably countless campaign possibilities (by combining different prices, products, durations, content, and more) from which Starbucks’ data scientists would have to identify the best-performing ones.

The objective of the analysis is to identify the key relationships between offers and demographic segments. In order to narrow down which promotions are relevant to each segment, we’re performing a heuristical & regressional analysis on the relationships between the 10 promotions and our identified segments.

Specifically, we will:
1. Determine which promotion(s) each segment is most responsive to.
2. Determine which promotion(s) to send to each segment based on expected revenues.

This repo contains all the details of the CRISPR-DM analysis performed to generate key insights.

## Table of Contents
1. [Installation](#installation)
2. [File Descriptions](#file-descriptions)
3. [Results](#results)
4. [Licensing](#licensing)

## Installation
To run the scripts in the Jupyter notebooks, you will only require the Anaconda distribution of Python (v3.0+).

## File Descriptions
**Raw Data (in "data" folder)**
1. portfolio.json: containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json: demographic data for each customer
3. transcript.json: records for transactions, offers received, offers viewed, and offers completed

**Analysis**
1. [Starbucks_Capstone_notebook.ipynb](https://github.com/jbbae/starbucks_promotion_strategy/blob/master/Starbucks_Capstone_notebook.ipynb): The bulk of our analysis
2. [profile_proc.csv](https://github.com/jbbae/starbucks_promotion_strategy/blob/master/profile_proc.csv): Pre-processed "profile" data, saved to avoid re-running a time-intensive pre-processing step with every tweak in the code.

## Results
A blog post that details the results & findings of this code can be found [here](https://medium.com/@jbbae/starbucks-promotion-optimization-ca56e29fb584).

## Licensing
Kudos to Starbucks & Udacity for the incredible dataset! Other than crediting _Starbucks_ for use of their promotion testing datasets, feel free to use the code as you like!
