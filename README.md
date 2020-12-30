### Table of Contents

1. [Installation](#installation)
2. [Problem Statement](#motivation)
3. [File Descriptions](#files)
4. [Conclusion](#results)
5. [Medium Post](#medium)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

To run the Jupyter notebook, one needs to have the following libraries installed.

  - python: 3.*
  - numpy: 1.16.*
  - pandas: 0.24.*
  - seaborn: 0.9.*
  - matplotlib: 0.11.*
  - sklearn: 0.*
  
If you install Python and Jupyter Notebook through Anaconda distribution, you should be all set to run the codes.

## Problem Statement<a name="motivation"></a>

This project is part of the requirements for Udacity Data Scientist Nanodegree. In this project, I used the simulated data provided by Starbucks [here](https://github.com/michellehsu2018/udacity-starbucks-capstone/tree/main/data) to answer the problem statement:
  -  I want to see what factors influence whether a customer completes the Buy One Get One Free (BOGO) offer. Some people might be incentivized after viewing the offer information; some might complete the offer due to certain characteristics other than the offer itself. In short, I want to build a supervised model which can classify whether a customer will complete the BOGO offer.

## File Descriptions <a name="files"></a>

  1. `Starbucks_Capstone_notebook.ipynb`: the notebook contains exploratory data analysis, statistical analysis, and modeling on the Starbucks simulated data.
  2. `data` directory: the directory contains the Starbucks simulated data - portfolio.json, profile.json, transcript.json
  3. `visualization` directory: the directory contains the visualizations created from the notebook
  4. `Starbucks_Capstone_notebook.html`: the html version of the notebook

## Conclusion <a name="results"></a>
  - Random Forest with CV performs the best compared to Naive Bayes, Logistic Regression, KNearestNeighbors, and Neural Network.
  - Random Forest with CV is doing pretty well in terms of classifying the positive class, meaning people who completed the BOGO offer
  - Feature `membership_days` turns out to be the most influential feature. The second and third important features are `time` and `income`

## Medium Post<a name="medium"></a>

  - Here's the link to my Medium post about the project and the findings - https://hsiaopenghsu.medium.com/unveil-the-starbucks-mysteries-of-buy-one-get-one-free-offers-f537f16706b4

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

  - The dataset for the project is from Starbucks simulated data: https://github.com/michellehsu2018/udacity-starbucks-capstone/tree/main/data
  - The project is required by Udacity: https://www.udacity.com/
