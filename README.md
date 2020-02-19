# EVA4_Assignment_5

Code:1  
https://colab.research.google.com/drive/1LOOOYi-egbsig0H0PP0R_x6wXOINydLr  
Target:  
1)To reduce the parameters from the 13k  
2)We reduce it by using less initial filters  
Results:  
Parameters-8996  
Best Test Accuracy-98.78  
Best Train Accuracy-99.16  
Analysis:  
The drastic reduction of parameters has reduced the ability to describe the features probably.  

Code:2  
https://colab.research.google.com/drive/1cdQOsSeIInN2ZkWwLghOHWBK8qDuyPxR  

Target:  

1)8896 parameters are low enough  
2)removing dropouts to make the training more relaxing for the NN as in to reduce penalties. already we have augumentation as rotations  

Results:  

Parameters-8996  
Best Test Accuracy- 99.04  
Best Train Accuracy-99.38  

Analysis:  

Removing dropout did not help much

Code:5  
https://colab.research.google.com/drive/1AaUPUyplphbGhWk7PncRgr35Zu-i56hz  
Target:  
1)Using Lr sheduler to guide the step towards convergence  

Results:
Parameters-9896  
Best Test Accuracy-98.96  
Best Train Accuracy-99.40  
Analysis:  
At the later stages of training the lr helps to reuce the step size thereby stabilising near 99.40
