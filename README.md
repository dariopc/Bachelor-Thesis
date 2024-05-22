# Bachelor-Thesis
This repository contains the Python code in the form of Jupyter Notebooks for the Bachelor Thesis titled "Neural Network Applications in Financial Derivatives: Optimizing European Call Option Pricing with MLPs and CNNs."

## Abstract
This thesis explores the potential of multilayer perceptrons (MLPs) and convolutional neural networks (CNNs) for pricing European call options, focusing specifically on out-of-the-money and at-the-money options. It utilizes S&P 500 Index data from the OptionMetrics platform to develop models that overcome the traditional Black-Scholes model’s limitations, particularly its assumptions of constant volatility and normal distribution of returns. A novel, biologically inspired approach is introduced, applying CNNs to mimic human visual analysis of volatil- ity surface images. This approach leverages the CNN’s capability to recognize complex spatial patterns in image data, exploring the application of image recognition models in financial deriva- tive pricing. The main findings reveal that MLPs, particularly when augmented with additional features, outperform the Black-Scholes model in both stable and volatile market conditions. However, CNNs, though effective in stable markets, demonstrate no reliability in volatile condi- tions. These results highlight the potential of neural network models to enhance the accuracy of financial derivative pricing.

## Files
- Data_Overview_Cleaning.ipynb:     Data preperation 
- MLP_code_final (1).ipynb:         Multilayer Perceptron models (MLP)
- CNN_code_final.ipynb:             Convolutional neural networks models (CNN)
- Performance_MLP_code_final.ipynb: Performance MLP models (PER)
