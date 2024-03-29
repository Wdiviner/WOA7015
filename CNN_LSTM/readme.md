Please view the original link of the code:  
https://www.kaggle.com/code/junyang680/cnnconnectlstm-woa7015/  
Please see the data:  
https://www.kaggle.com/datasets/wwwdiviner/7015-dataset  
Please view OpenPose data:  
https://www.kaggle.com/datasets/junyang680/openposedataset/  

**Version5**.ipynb uses frozen convolution layer and finetune fully connected layer settings for training.
![CNNs-LSTM](https://github.com/Wdiviner/WOA7015/assets/46164563/28e53189-0182-4e3d-9680-22793268d3d4)

The fully connected layer was deleted in **Version8**.ipynb and the convolutional layer was finetune directly.

|   Test     | Acc   | F1   | Auc  | 
|  ----  | ----  | ----  | ---- |
| Version5  | 0.98165 | 0.88889 | 0.94056 |  
| Version8  | 0.92661 | 0.66667 | 0.96278 |  

openpose-pytorch.ipynb  
openpose-pytorch.ipynb provides code for openpose detection of normal images and image saving based on the detected bone key points.
![image](https://github.com/Wdiviner/WOA7015/assets/46164563/d3cc1edd-8cab-4198-882b-128108a4da4b)


A simple attempt was made on **3D convolution**, but unfortunately the effect was not good. The original version link is:   
https://www.kaggle.com/code/junyang680/3dcnn-woa7015/notebook  


Data on kaggle can be obtained from colab and the local environment for training.    
The code is as shown in **Colab_Version**.ipynb. The original link is:   
https://colab.research.google.com/drive/1HF7G-i8zvfIa_VCZDmIw2jjx7RzXMQm9?usp=sharing  
**Ps**: The **kaggle.json** file is necessary. To obtain it, please refer to https://www.kaggle.com/docs/api  
