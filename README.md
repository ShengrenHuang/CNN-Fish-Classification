# CNN-Fish-Classification

在本練習中，我們利用捲積神經網路 (CNN) 來時做一個魚種分類器，分為10種魚種Black Sea Sprat, Gilt-Head Bream, Hourse Mackerel, Red Mullet, Red Sea Bream, Sea Bass, Shrimp, Striped Red Mullet, and Trout，所利用的神經網路函式庫為PyTorch，The codes are divided two parts, training and inference part. CNN 網路架構為一層convolution, 一層pooling 一層 convolution 一層 max pooling ，然後flatten之後接三層full connected 的 神經網路with ReLU activation, 在 error 上利用 crossentropyloss 來做評估。我們電腦設備 CPU: AMD Ryzen™ 5 3600X, GPU: NVIDIA GeForce RTX 2060。

# Hyper-parameters  
num_epochs = 30  
batch_size = 1  
learning_rate = 0.001  

# Training Result




Test dataset accuracy  
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
Validate dataset accuracy  
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

![image](https://user-images.githubusercontent.com/108604868/188657533-4e6e30f4-a119-4776-aa95-311f0b2fdfd2.png)

# References
[1] https://pixabay.com/photos/fish-red-mullet-fish-market-727222/  
[2] Understanding of a Convolutional Neural Network  
[3] A Large Scale Fish Dataset:
https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset .
