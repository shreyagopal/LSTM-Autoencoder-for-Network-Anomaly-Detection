# LSTM Autoencoder for Network Anomaly Detection
Training an LSTM-based autoencoder to detect anomalies in the KDD99 network traffic dataset.

# Project Instructions

In this project, you will combine what you have learned in the previous two sections to create and train an LSTM-based autoencoder 
to detect anomalies in the KDD99 network traffic dataset. For this task, you should use the same encoding technique as that of the model 
presented in Section 4. As for the architecture of the LSTM autoencoder, you can use the one presented in Section 5. However, feel free to 
explore other architectures as well. 

Note that KDD99 does not include timestamps as a feature. The simplest approach to making these discrete datapoints into time-domain data 
is to assume that each datapoint occurs at the timestep immediately after the previous datapoint. However, more sophisticated approaches 
can also be adopted (e.g., grouping by TCP connections). The choice of serialization technique (i.e., conversion into time-domain) is up 
to you.

This project must be implemented in a Jupyer Notebook, and must be compatible with Google Colab (i.e., if you are using a particular 
library that is not on Colab by default, your notebook must install it via !pip install ... ). Your notebook must also contain a section 
on performance analysis, where you report the performance of your IDS model via performance metrics and/or plots (similar to Section 5).
the
**A very important note:** You should not expect very high detection rates from the model. 

Happy Coding!!!!! 
