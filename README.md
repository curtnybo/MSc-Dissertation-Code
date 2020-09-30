# MSc Dissertation Code ReadMe

## Sector Volatility Prediction Performance Using GARCH Models and Artificial Neural Networks
### Curtis Nybo
### MSc Quantitative Finance Dissertation 2020

This repository contains the code developed for my MSc Dissertation. 

# The Data
The data is retrieved from the Kenneth R. French data library (1). The dataset contains all U.S stocks, sorted into five sectors by SIC code. The datasets I have used in this study are provided in the 'Data' folder. The folder contains the original dataset and a summary of the dataset, and each specific has been extracted to its own file. 

# The Code
The thesis paper uses six Jupyter notebooks that were developed for this project. Three GARCH specifications and three ANN architectures are considered with one notebook for each. 

The ANN notebooks are comprised of one notebook per architecture (5,1,1), (5,12,1), and (5,50,1).

The GARCH notebooks are comprised of one notebook for the GARCH(p,q), GARCH(1,1), and EGARCH(p,q) model.

 ## How to use
Each notebook is commented throughout to guide reproducibility. The data in this repository needs to be placed in a local directory, then the code needs to be changed to point to that directory. The script should then read in the data and follow the same computations in this study. 

To replicate the conda environment used to develop and run the code, see the tensorflowML.yml file in the repository. This contains all Python packages used and their corresponding versions. This yml file can be directly imported into Conda to reproduce the environment used in this study.

# References
Many thanks to those who provided resources and prior work to leverage in my notebooks and scripts. More specific referencing is completed in each notebook. 

(1) Data Library - Kenneth R. French - https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html - 2020

(2) Time Series Prediction with LSTM Recurrent Neural Networks in Python with Keras - Jason Brownlee, PhD - https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/ - 2016

(3) Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition - Aurélien Géron - https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/ - 2019

(4) TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems - https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45166.pdf - 2015

(5) Kevin Sheppard, Stanislav Khrapov, Gábor Lipták, mikedeltalima, Rob Capellini, esvhd, … jbrockmendel. (2019, November 22). bashtage/arch: Release 4.13 (Version 4.13). Zenodo. http://doi.org/10.5281/zenodo.3551028

(6) Auquan - Time Series Analysis for Financial Data VI— GARCH model and predicting SPX returns - https://medium.com/auquan/time-series-analysis-for-finance-arch-garch-models-822f87f1d755 - 2017

(7) Sarit Maitra - Forecasting using GARCH Processes & Monte-Carlo Simulations: statistical analysis & mathematical model using Python - https://towardsdatascience.com/garch-processes-monte-carlo-simulations-for-analytical-forecast-27edf77b2787 - 2019
