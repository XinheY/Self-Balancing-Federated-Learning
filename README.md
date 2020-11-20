# CSCI596-FedLearningProject
## Goal: Try to solve data imbalance problem in Federated Learning

### Backgroud:
*Federated Learning*:

Federated learning (also known as collaborative learning) is a machine learning technique that trains an algorithm across multiple decentralized edge devices or servers holding local data samples, without exchanging them. This approach stands in contrast to traditional centralized machine learning techniques where all the local datasets are uploaded to one server, as well as to more classical decentralized approaches which often assume that local data samples are identically distributed.
![Federated Learning](https://github.com/ivishalanand/Federated-Learning-on-Hospital-Data/raw/master/images/federated-learning.png)


**Data imbalance**:

1) Size Imbalance, where the data size on each device (or client) is uneven; 
2) Local Imbalance, i.e., independent and non-identically distribution (non-IID), where each device does not follow a common data distribution; 
3) Global Imbalance, means that the collection of data in all devices is class imbalanced

**proposed solution**:

Paper Link: https://ieeexplore.ieee.org/document/9141436



**Benchmark and Dataset**:

https://github.com/chaoyanghe/Awesome-Federated-Learning#Benchmark-and-Dataset

**Baseline Code (just examples)**:
- https://github.com/shaoxiongji/federated-learning

- https://github.com/ivishalanand/Federated-Learning-on-Hospital-Data


### Steps:
- Replicate Baseline Code
- Run evaluation pipeline
- Improve the baseline by https://docs.google.com/document/d/1qa0Cv-axRw9ZSVDB-C5YZMp9lEd6qp3d1FmzX7D8Mgg/edit methods
- Propose our own method (optional)