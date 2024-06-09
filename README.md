# Federated_Learning_using_Blockchain
This repo present my work to use federated Learning (Weighted learning).Known that dataset wasn't perfect for Federated Learning.

## Tools :
- Ganache
- Truffle
- Tensorflow
- Jupyter Notebook

## Description : 
**Federated Learning** is  a machine learning technique that trains models across multiple decentralized devices or servers holding local data samples, without exchanging their data. it provide a new way to train model without moving data making it compromise for cyber attack. 
using Toolchain we add another layer of protection by protecting model weights while it transfered.

## Federated Learning vs. Distributed Learning

| **Aspect**          | **Federated Learning**                                                                                     | **Distributed Learning**                                                                                   |
|---------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| **Data Location**   | Keeps data localized on devices, enhancing privacy.                                                       | May involve moving data between nodes and a central server.                                               |
| **Privacy**         | Focuses on privacy by sharing only model updates (e.g., gradients).                                       | Can involve more extensive data sharing, less emphasis on data privacy.                                    |
| **Application**     | Suitable for scenarios where data privacy is paramount (e.g., personal devices).                          | Used to speed up training on large datasets across powerful computing clusters.                            |
| **Data Transfer**   | Model updates are sent to a central server for aggregation, no raw data transfer.                         | Data can be transferred between nodes and a central server to optimize training efficiency.                |
| **Data Partitioning** | Each device or server holds local data samples, and training is performed locally.                       | Data can be partitioned in various ways (e.g., horizontally, vertically) across nodes for parallel processing. |

**Ganache** is a program for local Ethereum blockchain development, while **Truffle** is a toolchain for Ethereum smart contract development. They streamline the process of building, testing, and deploying decentralized applications (dApps) on the Ethereum network.

A **smart contract** is a self-executing contract with the terms of the agreement directly written into code. It automatically executes and enforces the terms of the contract when predefined conditions are met, without the need for intermediaries. Smart contracts are typically deployed on blockchain platforms, such as Ethereum, and can facilitate a wide range of transactions and agreements in a transparent, secure, and decentralized manner.


- Using smart contract we define how to transform Model Weights between Clients and Server
- 













