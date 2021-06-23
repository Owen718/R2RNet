# R2RNet
Official code of "R2RNet: Low-light Image Enhancement Via Real-low to Real-normal Network".
## Network Architecture
![image](https://user-images.githubusercontent.com/86350392/123072534-382ae080-d448-11eb-856c-8086578a308e.png)
# Pytorch
This is a Pytorch implementation of R2RNet.
## Requirements
1. Python 3.x 
2. Pytorch 1.x.0
## Dataset
You can download the LSRW dataset from:https://pan.baidu.com/s/1G0k_AZ2nylwm_xNkWBs7mA (code:scua).
You shold download the VGG model (https://pan.baidu.com/s/1Rn2NwHt9eZgfg6hQP-DrlQ code:wmr1)and put it into ./model.
## Pre-trained model
You can download the pre-trained model from:https://pan.baidu.com/s/14XXmWgnWqo4EsVjjhtkSyQ (code:ckpt )
## Testing Usage
python predict.py
## Training Usage
python trian.py
