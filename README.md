## MueNet-A-Mutual-Based-Framework-for-Unsupervised-Anomaly-Detection

## Overview

We propose the MueNet as follows, which comprises three submodules: the local information extraction module (L-module), the supplementary learning of residual information module (S-module), and the global representation generation module (G-module). These modules collectively enhance the model’s capability to learn local content, supplement residual content, and generate global representation. The MueNet learning process is guided by a multitask entropy loss function. 

<img src="D:\Desktop\论文\PAMI\code_to_github\MueNet5.png" alt="The MueNet structure." style="zoom:50%;" />



## How to use

#### Dependencies

This tutorial depends on the following libraries:

PyTorch == 1.8

Scikit-learning ==0.24

Python == 3.7

#### Run Torch_MueNet_train.py

You can get a "checkpoint.pt" in the folder of "model".

#### Run Torch_MueNet_test.py

You will see the predicted results of MueNet.

#### Run heatmap_input.py and heatmap_feature.py

You can acquire a heatmap about input data and another about feature data by checkpoint.pt. 

### Results

<img src="D:\Desktop\论文\PAMI\code_to_github\Numerical2.png" alt="Numerical2" style="zoom:50%;" />

