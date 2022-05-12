# LSTM Neural Network

Original dataset used: www.kaggle.com/datasets/uciml/electric-power-consumption-data-set

Due to some days in the dataset having missing lines, there was a need to clean the dataset, for that the fix_dataset.py removed all the days that had a missing measurement  
It is possible to visualy see the data separated in each day with the read_dataset.py  
![image](https://user-images.githubusercontent.com/94933775/168104463-d8ed6fdd-d7bf-4d6b-bb41-2515032c7d74.png)

The training of the neural network is done in the nn.py  
New predictions can be made using the prediction.py