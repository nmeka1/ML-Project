# ML-Project
Name: Sai Teja Meka,NarendraReddy Kanjula

This paper focuses on the challenging task of probabilistic forecasting for non-stationary time series. The goal is to predict a distribution of possible future outcomes while ensuring both accuracy and diversity. To achieve this, the authors propose a model called STRIPE that represents structured diversity based on shape and time features. The model is agnostic to the forecasting method used and includes a diversification mechanism based on determinantal point processes (DPP). The authors introduce two differentiable DPP kernels for modeling diverse trajectories in terms of shape and time. An iterative sampling mechanism is also designed to disentangle shape and time representations in the latent space. Experiments on synthetic and real datasets demonstrate that STRIPE outperforms baseline methods for representing diversity while maintaining accuracy of the forecasting model. The authors emphasize the importance of using different criteria for measuring quality and diversity and highlight the relevance of the iterative sampling scheme. Overall, STRIPE is shown to be a promising approach for probabilistic forecasting of non-stationary time series. We have changed the batch size and observed the loss curve for batch size 200 the loss got increased from 0-100 iterations and from then loss got reduced till 500 iterations and for 300 batch size loss increased from 0-100 and decreased fromm 200-400 and we have seen increase ini loss for 400-500 iterations.
