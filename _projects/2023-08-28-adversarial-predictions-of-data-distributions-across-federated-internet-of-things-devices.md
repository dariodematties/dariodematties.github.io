---
title: "Adversarial Predictions of Data Distributions Across Federated Internet-of-Things Devices"
collection: publications
permalink: /publication/2023-08-28-adversarial-predictions-of-data-distributions-across-federated-internet-of-things-devices
excerpt: 'This paper demonstrates that the model weights shared in FL can expose revealing information about the local data distributions of IoT devices.'
date: 2023-08-28
venue: 'IEEE WF-IoT'
paperurl: 'https://arxiv.org/abs/2308.14658'
citation: 'Samir Rajani, et al. (2023). &quot;Adversarial Predictions of Data Distributions Across Federated Internet-of-Things Devices.&quot; <i>IEEE WF-IoT</i>.'
---
Federated learning (FL) is increasingly becoming the default approach for training machine learning models across decentralized Internet-of-Things (IoT) devices. A key advantage of FL is that no raw data are communicated across the network, providing an immediate layer of privacy. Despite this, recent works have demonstrated that data reconstruction can be done with the locally trained model updates which are communicated across the network. However, many of these works have limitations with regard to how the gradients are computed in backpropagation. In this work, we demonstrate that the model weights shared in FL can expose revealing information about the local data distributions of IoT devices. This leakage could expose sensitive information to malicious actors in a distributed system. We further discuss results which show that injecting noise into model weights is ineffective at preventing data leakage without seriously harming the global model accuracy.
