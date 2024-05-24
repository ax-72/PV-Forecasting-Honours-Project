# PV-Forecasting-Honours-Project
This repository contains the code, datasets and saved models for my honours project. 
The "Datasets" folder contains the datasets used for the experiment. 

* The "Solar Power Plant Data.csv" dataset was obtained from Kaggle: https://www.kaggle.com/datasets/pythonafroz/solar-powe-generation-data/data
* The "all_data.csv" dataset was provided by a research fellow in the same research group
* The "1 gazbray.csv" dataset was obtained from a public GitHub repository: https://github.com/gomesramos/PV-Output-Datasets

The "code" folder contains the code and saved models which are in separate folders. The LSTM folder contains the base BI-LSTM model. This model was trained on the "Solar Power Plant Data.csv" dataset. 
The LSTM_w_TL_1 folder contains the first BI-LSTM model with transfer learning applied. This model was trained on the "all_data.csv" dataset.
The LSTM_w_TL_2 folder contains the second and last BI-LSTM model with transfer learning applied. This model was trained on the "1 gazbray.csv" dataset.
