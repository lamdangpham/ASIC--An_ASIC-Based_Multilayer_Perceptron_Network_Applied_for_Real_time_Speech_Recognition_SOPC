# An ASIC-Based Artificial Neural Network Applied Real-time Speech Recognition SOPC

Work for “Develop an Artificial Neural Network
(ANN) digital hardware architecture applying Vietnam speech recognition
automatically” project funded by Department Science and Technology of Ho Chi
Minh City, Vietnam.

We achieved a dynamic VLSI architecture of ANN successfully, which
perform ability of reconfiguration as regards both multiple layers and multiply
nodes per layer. 

1/ Hierarchy:

|
|---01_Publications_Docs : Contain published papers and Documentation
|    |
|    |--01_An ASIC-Based Artificial Neural Network Applied Real-time Speech Recognition SOPC.pdf : Paper_01 
|    |
|    |--02_2_Efficient Hardware Architecture for Single Neuron in Artificial Neural Network.pdf  : Paper_02
|    |
|    |--03_Short_Introduction.pdf : Short Introduction of Neural Network archiecture mentioned in Paper_01
|
|---02_Codes : Contain coding package for the system mentioned in Paper_01
|
|-README.md

2/ Summary:

Section '02_Codes' contains code lines for the system mentioned in Paper_01. 
This system consits Feature Extraction (Mel-Frequency Ceptral Coefficients) and Classifier (Multi-layer perceptron - MLP Model).

+ MFCC is implemented by Software (both Matlab and C). Matlab version is for training process on computer, and C version is for recognition on DE2 Kit (Altera).

+ MLP model is implemented by Verilog HDL. MLP model consist a lot of neural node and they show similar functions. The Paper_02 shows how to implement one neural node by Verilog HDL.

