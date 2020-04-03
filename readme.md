# FlowNet
This is an implementation of the contents of the paper [2015_FlowNet: Learning Optical Flow with Convolutional Networks](https://arxiv.org/pdf/1504.06852) with tensorflow. The version is adapted to tensorflow release 1.14.
## Dataset
[FlyingChairs](https://lmb.informatik.uni-freiburg.de/data/FlyingChairs/FlyingChairs.zip)
Download and extract to media/csc105/Data/dataset
## Program list
train_flownet_simple.py - Train the network using this script and the dataset provied above.
test_flownet_simple.py - Test the network using this script
test_visual.m - visualize the predicted flow on the basis of a default images
### Tools for flow visualization
flow-code-cpp  
flow-code-matlab  
