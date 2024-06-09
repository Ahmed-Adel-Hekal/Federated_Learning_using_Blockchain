# Federated_Learning_using_Blockchain
This repo present my work to use federated Learning (Weighted learning).Known that dataset wasn't perfect for Federated Learning.

## Tools :
- Ganache
- Truffle
- Tensorflow
- Jupyter Notebook

## Description : 
Federated LEarning is  a machine learning technique that trains models across multiple decentralized devices or servers holding local data samples, without exchanging their data.

## Federated Learning vs. Distributed Learning

### Federated Learning
Federated learning is a machine learning technique that trains models across multiple decentralized devices or servers holding local data samples, without exchanging their data. This approach enhances data privacy by keeping raw data localized and only sharing model updates (e.g., gradients) with a central server for aggregation.

### Distributed Learning
Distributed learning is a machine learning approach where the training process is split across multiple machines or nodes, which can be in a single data center or spread across multiple locations. Unlike federated learning, distributed learning often involves transferring data between nodes and a central server to optimize training efficiency and performance. Data can be partitioned in different ways (e.g., horizontally, vertically) across the nodes to leverage parallel processing and reduce training time.

### Key Differences
- **Data Location:** Federated learning keeps data localized on devices, enhancing privacy, whereas distributed learning may involve moving data between nodes and a central server.
- **Privacy:** Federated learning focuses on privacy by sharing only model updates, while distributed learning can involve more extensive data sharing.
- **Application:** Federated learning is suitable for scenarios where data privacy is paramount (e.g., personal devices), while distributed learning is used to speed up training on large datasets across powerful computing clusters.
