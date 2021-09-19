
# Federated-learning-image-classification
- This repo implements the federated learning concept on the MNIST handwritten digit dataset using central server model<br>
# Architecture
![alt text](https://blogs.nvidia.com/wp-content/uploads/2019/10/federated_learning_animation_still_white.png)

This Architecture is taken from https://blogs.nvidia.com/blog/2019/10/13/what-is-federated-learning/
## About Research paper
```
  title={Communication-Efficient Learning of Deep Networks from Decentralized Data},
  author={H.Brendan McMahan, Eider Moore, Daniel Ramage, Seth Hampson, Blaise Aguera y Arcas},
  booktitle={arXiv:1602.05629v3 [cs.LG] 28 Feb 2017},
  pages={1-11},
  year={2017},
  
```
## Brief Introduction
- Federated learning is a new framework that is implemented for cross-device and cross-silo settings and works for both client-server and peer-to-peer based models
- In this technique, data is not imported to server rather it resides on local devices and on-device training happens. So, its main concern is preserving consumer's privacy.
- It can be merged with differential privacy and thus has potential to be robust to privacy concerns.
- The main goal is to deal with systems and statistical heterogeneity efficiently, which is main cause of concern in on-device training.

## Dependencies
Python 3.7<br>
Tensorflow >= 2.0


## Prerequisites
1. Clone the repository
```
git clone https://github.com/ShobhitDubey0729/Federated-learning-image-classification.git<br>
cd Federated-learning-image-classification/
```
2. Download requirements
 ```
pip3 install -r requirements.txt
```
3. run the file
```
python3 fedavg_client_server.py
```




