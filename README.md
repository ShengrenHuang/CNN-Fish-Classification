# CNN-Fish-Classification

In this practice, we aim to employ the convolution neural network (CNN) [2] to implement a Fish classification. The classes of the specific fishes lie in 10 kinds, Black Sea Sprat, Gilt-Head Bream, Hourse Mackerel, Red Mullet, Red Sea Bream, Sea Bass, Shrimp, Striped Red Mullet, and Trout. The python package for CNN we use here is PyTorch. The codes are mainly divided into two parts, training and inference part. By referring to [4], the CNN architecture in our code has two convolutional, two max-pooling, and three fully-connected layers with Relu activation functions. The type of training error we adopted here is cross-entropy loss. The training and inference processes run on a desktop computer with CPU: AMD Ryzen™ 5 3600X, GPU: NVIDIA GeForce RTX 2060 (CUDA available). The fish database [3] is separated into three parts, 60% for training, 20% for testing, and 20% for validation. 

# Hyper-parameters  
num_epochs = 30  
batch_size = 1  
learning_rate = 0.001  



# Training Result


## Test dataset accuracy  
Accuracy of the network: 79.22222222222223 %  
Accuracy of Black Sea Sprat: 78.5 %  
Accuracy of Gilt-Head Bream: 67.5 %  
Accuracy of Hourse Mackerel: 54.5 %  
Accuracy of Red Mullet: 83.0 %  
Accuracy of Red Sea Bream: 91.0 %  
Accuracy of Sea Bass: 95.0 %  
Accuracy of Shrimp: 100.0 %  
Accuracy of Striped Red Mullet: 58.0 %  
Accuracy of Trout: 85.5 %     
   
## Validate dataset accuracy  
Accuracy of the network: 82.66666666666667 %  
Accuracy of Black Sea Sprat: 85.0 %  
Accuracy of Gilt-Head Bream: 75.5 %  
Accuracy of Hourse Mackerel: 76.5 %  
Accuracy of Red Mullet: 95.0 %  
Accuracy of Red Sea Bream: 82.0 %  
Accuracy of Sea Bass: 94.5 %  
Accuracy of Shrimp: 100.0 %  
Accuracy of Striped Red Mullet: 87.0 %  
Accuracy of Trout: 48.5 %  

# Inference/Predict Result 
The image of red mullet is downloded from [1].
![image](https://user-images.githubusercontent.com/108604868/188657533-4e6e30f4-a119-4776-aa95-311f0b2fdfd2.png)

# References
[1] https://pixabay.com/photos/fish-red-mullet-fish-market-727222/  
[2] Understanding of a Convolutional Neural Network  
[3] [A Large Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset).  
[4] [Deep Learning With PyTorch - Full Course](https://www.youtube.com/watch?v=c36lUUr864M&ab_channel=PythonEngineer).
