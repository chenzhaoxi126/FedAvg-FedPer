# 传统联邦学习和个性化联邦学习的对比研究
摘  要：
本文从理论和实验角度对传统联邦学习和个性化联邦学习进行对比分析。联邦学习将模型训练过程迁移至本地设备，仅在本地更新模型参数，然后客户端将更新后的模型参数上传至中央服务器聚合出一个全局模型，这种方法可以保护用户隐私和数据安全。但是由于各个客户端数据不同，对于模型的需求也不一致，一个统一的全局模型很难得到一个令各方满意的结果。个性化联邦学习可以在每个客户端训练出属于其的个性化模型，更加适合各客户端自身的需求。本文选取FedAvg和FedPer算法作为两种联邦学习的代表算法，在不同的非独立同分布数据集MNIST、CIFAR-10、CIFAR-100下对这两种算法的性能进行对比实验。实验结果表明，FedPer在各数据集下的准确率均明显高于FedAvg，这也验证了FedPer在处理特定任务上相较于FedAvg的优越性。本文探讨了传统联邦学习与个性化联邦学习的原理、优势、差异和挑战，并提出了未来研究的方向。

关键词：传统联邦学习；个性化联邦学习；非独立同分布；对比分析

Abstract:
This article provides a comparative analysis of traditional federated learning and personalized federated learning from both theoretical and experimental perspectives. Federated learning transfers the model training process to local devices, where only local model parameters are updated, and then the updated model parameters are uploaded to a central server to aggregate a global model. This approach can protect user privacy and data security. However, due to the different data on each client, and thus varied requirements for the model, it is challenging to obtain a globally satisfactory model. Personalized federated learning can train personalized models for each client, which are more suitable for the individual needs of each client. This article selects FedAvg and FedPer algorithms as representative algorithms for the two types of federated learning and conducts comparative experiments on different non-independent and identically distributed datasets such as MNIST, CIFAR-10, and CIFAR-100. The experimental results show that the accuracy of FedPer is significantly higher than FedAvg on each dataset, which also verifies the superiority of FedPer over FedAvg in handling specific tasks. This article explores the principles, advantages, differences, and challenges of traditional federated learning and personalized federated learning, and proposes directions for future research.

Keyword: Traditional federal learning; Personalized federated learning; Non-independent and identically distributed; Comparative analysis

详见https://www.kaggle.com/code/chenzhaoxi/mnist-avgper/notebook?scriptVersionId=180541508

https://www.kaggle.com/code/chenzhaoxi/cifar10-non
