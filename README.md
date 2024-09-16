# Paper Title [TBD]

This repository contains the official implementation of our paper titled " _TBD_ " published in the journal " _TBD_ ". [Paper Link]

## Files
- **Dataset.csv**: Contains experimental data for Perovskites **MAPbBr3** and **MAPbI3**.
- **train.csv**: Contains data from different temperatures, used to train various machine learning models.
- **test.csv**: Contains data from **5 unseen** temperatures, used to evaluate results from the best-performing trained models.
- **train_X.csv**: Contains scaled and transformed data for feature columns _[Ionic radius, Temperature, Frequency]_, used to train different ML models.
- **train_y.csv**: Contains scaled and transformed data for target columns _[Re(z), Img(z)]_, used during the training of ML models.
- **test_X.csv**: Derived from test.csv, contains scaled and transformed data for feature columns _[Ionic radius, Temperature, Frequency]_, used to evaluate results from the best-performing models.
- **test_y.csv**: Derived from test.csv, contains scaled and transformed data for target columns _[Re(z), Img(z)]_, used to obtain final output from trained ML models.
- **predicted_data_for_fitting.csv**: Contains predicted outputs from the best-performing model and is used for circuit curve fitting.
- **temp** : this folder contains fitting files extracted during fitting process.
---
