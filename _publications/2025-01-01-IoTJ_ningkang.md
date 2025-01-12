---
title: "Yang, N., Lu, Q. L., Yamnenko, I., & Antoniou, C. (2024). Efficient Cloud-Sourced Transport Mode Detection Using Trajectory Data: A Semi-Supervised Asynchronous Federated Learning Approach. IEEE Internet of Things Journal."
collection: publications
date: 2025-01-01
venue: 'IEEE Internet of Things Journal'
paperurl: https://doi.org/10.1109/JIOT.2024.3516695 
---

The Internet of Things enables collaborative efforts
in pattern recognition tasks within intelligent transportation
systems, such as transport mode detection (TMD). However, collecting individual trajectories, like GPS records, typically involves
privacy issues. To address this, federated learning frameworks
have recently been applied. In such frameworks, users retain
their private client datasets and are responsible for training local
models. Only the updated client model parameters are sent to a
central server, where these parameters are aggregated to update
a global model. Then, the server broadcasts the updated global
model to all users for the next round of local training. In this way,
users can contribute to the global model without sharing private
data. However, traditional federated learning frameworks are
inefficient as the server has to wait for multiple users to upload
their model parameters for synchronous parameter aggregation
and consistency updates. This process also faces risks from
unreliable clients. Furthermore, private client datasets are often
unlabeled, posing challenges for local model training. Therefore,
this paper proposes a semi-supervised asynchronous federated
learning framework for both point-level and segment-level TMDs.
Specifically, the proposed framework incorporates model splitting
techniques, model shift penalties, and entropy-based aggregation
strategies to address model complexity, model drift, and data
imbalance, respectively. Moreover, a CNN-based deep learning
model with multiple encoders is proposed, and a pseudo-labelingbased approach is applied to utilize unlabeled datasets. The case
study demonstrates that the proposed model achieves satisfactory
performance on a real-world dataset, and the proposed federated
learning framework is robust under varying hyperparameter
configurations.
