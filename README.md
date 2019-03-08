# Rescaling-Data-Python-using-torch

This code is to rescale the tensor or the data before feeding it to machine. Question is why rescaling or normalize is required. Let me explain you this first so that you may realize why to understand this code.  

## Why rescaling or normalization is needed.  
I would like to explain you the concept using the tensor/data used in this code. Let us look at the data as below  
```
X = torch.tensor(([554, 877], [333, 666], [3, 6]), dtype=torch.float) # 3 X 2 tensor
```  
If you see the output of this line by writing the below line  
```
print(x)
```
<em><strong>You will see the below output</em></strong>    
[[4., 877.],  
[8., 666.],  
[  3.,   6.]])  

If you see values in both the columns they are very far away from each other and hence it becomes difficult for the machine to find the patterns. This is the reason why we need to do normalization of both the columns. If you want to execute the above code, you need to install torch as well as import it.  

<strong>Command to install torch</strong>  
```
pip3 install torch torchvision  
```  
<strong>How to import it</strong>
```
import torch
``` 
## How to run this code  

Since this is a python code and hence it can be run using the below command.  
```
python/python3 torch_normalization.py  
```





