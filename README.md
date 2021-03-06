# Predicting-electric-energy-consumption-using-different-neural-networks-by-Keras
---
-These codes are used to experimentally record the paper you see, and practice building NN models to compare the effects of different NNs.
-There are some experimental or long redundant traces in the code.

---
-Requirements
 - Keras
 - tensorflow-gpu

---
-Dataset download
 - https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

---
- Result Plot
CNN-LSTM
![](https://github.com/TechFinBrown/Predicting-electric-energy-consumption-using-different-neural-networks-by-Keras/blob/master/CNN-LSTM.png)

CNN-BiLSTM
![](https://github.com/TechFinBrown/Predicting-electric-energy-consumption-using-different-neural-networks-by-Keras/blob/master/CNN-BiLSTM.png)

---
Referece 
- [1] CNN-LSTM.ipynb is reference 'Predicting residential energy consumption using CNN-LSTM neural
networks'
  - Using CNN-LSTM model architecture ; instead author CNN layer -> 1d cnn layer
  - http://sclab.yonsei.ac.kr/publications/Papers/IJ/2019_Energy_TYK.pdf

- [2] CNN-Bi-LSTM.ipynb is reference 'Improving Electric Energy Consumption Prediction
Using CNN and Bi-LSTM'
  - Using CNN-Bi-LSTM model architecture ; 
  - http://sclab.yonsei.ac.kr/publications/Papers/IJ/2019_Energy_TYK.pdf
  
- 'How to Develop Multi-Step LSTM Time Series Forecasting Models' for Power Usage by brownlee
  - https://machinelearningmastery.com/how-to-develop-lstm-models-for-multi-step-time-series-forecasting-of-household-power-consumption/
