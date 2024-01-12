Please view the original link of the code:  
https://www.kaggle.com/code/junyang680/cnnconnectlstm-woa7015/  
Please see the data:  
https://www.kaggle.com/datasets/wwwdiviner/7015-dataset  
Please view OpenPose data:  
https://www.kaggle.com/datasets/junyang680/openposedataset/  

Version5.ipynb uses frozen convolution layer and finetune fully connected layer settings for training.
![CNNs-LSTM](https://github.com/Wdiviner/WOA7015/assets/46164563/28e53189-0182-4e3d-9680-22793268d3d4)

The fully connected layer was deleted in Version8.ipynb and the convolutional layer was finetune directly.

|   Test     | Acc   | F1   | Auc  | 
|  ----  | ----  | ----  | ---- |
| Version5  | 0.98165 | 0.88889 | 0.94056 |  
| Version8  | 0.92661 | 0.66667 | 0.96278 |  

openpose-pytorch.ipynb  
openpose-pytorch.ipynb provides code for openpose detection of normal images and image saving based on the detected bone key points.
