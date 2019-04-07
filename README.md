# Human Presence Sensing

Data: Consists of outputs from 4 sensors that predict the presence of Humans in a room. Additionally, it also contains the prediction from a black-box algorithm that uses the outputs from the sensors to predict human presence.

Analysis: Implemented a Time Series classification model that predict Human Presence in a room, with a ROC-AUC score of 0.9. After fixing the sampling rate of the data using two-step resampling, used sensor outputs, lagged features, and rolling-window statistics to train the model.
