## Multi-Plane Multi-Slice Longitudinal MRI for Deep Ensemble Progression Detection based on Enhanced Residual Multi-Head Self-Attention 

##This repository provides a Keras-based implementation of a study aimed at the early detection of Alzheimer's disease progression using longitudinal MRI data..

To ensure proper execution of the code, please refer to the requirements.txt file for a complete list of required libraries and dependencies.

## Training:
Run the following command to train any desired CNN backbone for feature extraction with a Bayesian optimized classification head. You can also use a CBAM module as an intermediate attention module by specifying a flag in the given command.
```

python train.py --cnnbb [EfficientNet, ResNet, ConvNext, DenseNet, XceptionNet] EfficientNet --ch [mlp, lstm, multihead_attention] multihead_attention --cbam [True, False] --data_dir "path\to\root\folder" 

```


