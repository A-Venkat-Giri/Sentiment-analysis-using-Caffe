# experiments

Sentiment analysis using Caffe 

The data set that is used for sentiment analysis is the Large Movie Review Dataset.
The model used consists of the:   
Data layer   
Two Common Layers: InnerProduct (ip1, ip2)    
One ReLU layer  
Two Loss Layers: (Accuarcy, SoftmaxWithLoss)    
The input layer is given in the LMDB format.   
After creating paragraph vectors from the dataset, the training file and testing file are converted to the LMDB format, which is supported as an input to the Neural Network.  
The Neural network is trained with 10000 iterations.

