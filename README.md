# Multi-output time series forecasting with randomized multivariate Fuzzy Cognitive Maps
This repository containes the code for a randomized MIMO FCM-based forecasting approach called MO-RHFCM to predict low-dimensional multivariate time series. More specifically, MO-RHFCM is a hybrid model merging 
the concepts of multivariate fuzzy time series, high order FCM (HFCM), and Echo State Networks (ESN). The structure of MO-RHFCM consists of three layers: input layer, reservoir (internal) layer, and output layer.
Only the output layer is trainable using the Least Squares minimization algorithm; hence training the proposed MO-RHFCM method is fast and simple. The weights inside each sub-reservoir are selected randomly and 
remain fixed during the training process. The obtained results indicate the efficacy and validity of the proposed MO-RHFCM technique compared with some machine learning and deep learning baseline models.

## Objectives and contributions
1) The code implemets MO-RHFCM as reservoir computing integrating Multivariate Fuzzy Time Series (MVFTS), Fuzzy Cognitive Maps (FCM), and Echo State Networks (ESN).
2) It presents the first multiple-input, multiple-output (MIMO) time series forecasting method inspired by R-HFCM.
3) Cost-Effective and Less Complex: The proposed method is cheaper, less complex, and more parsimonious compared to deep learning approaches.
4) Efficient Training Methodology: The model employs a time-effective learning approach, using least squares regression and randomly chosen weights for training.

## References
Orang, O., de Lima e Silva, P. C., & Guimarães, F. G. (2023). Multi-output time series forecasting with randomized multivariate Fuzzy Cognitive Maps. Chaos, Solitons & Fractals, 176, 114077. 
DOI: 10.1016/j.chaos.2023.114077

## Computational Experiments

To use the R-HFCM model, upload your cleaned and pre-processed dataset, then run the Jupyter Notebook to visualize the results. Before running the model, it is necessary to install the pyFTS library using the command !pip3 install -U git+https://github.com/PYFTS/pyFTS. 
All computational experiments in this study were implemented using Python 3.6.12 with open-source packages such as Scikit-learn, Pandas, Numpy, and pyFTS.
