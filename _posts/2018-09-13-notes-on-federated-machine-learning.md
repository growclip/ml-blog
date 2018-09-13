---
title: Notes on Federated Machine Learning
layout: post
---

Federated Machine Learning tries to solve the problem of limited bandwidths and unreliable connections to edge devices (e.g. mobile phones) that collect data. With federated ML, these now also participate in model training.

Training is done on the edge devices, and updated weights, rather than data are sent to the server, reducing packet sizes.

The field is moving quickly:
* 2016 - Konečný, J. et al from Google started this [^1] 
* 2017 - Follow up from Konečný, J. et al [^2]
* 2018 - Federated Recommendation [^3]
* 2018 - Securing Distributed ML [^4]
* 2018 - Backdoor Federated Learning  [^5]






[^1]: Konečný, J. et al. Federated Learning: Strategies for Improving Communication Efficiency. arXiv:1610.05492 [cs] (2016).
[^3]: Chen, F., Dong, Z., Li, Z. & He, X. Federated Meta-Learning for Recommendation. arXiv:1802.07876 [cs] (2018).
[^5]:  Bagdasaryan, E., Veit, A., Hua, Y., Estrin, D. & Shmatikov, V. How To Backdoor Federated Learning. arXiv:1807.00459 [cs] (2018).
[^4]:  Su, L. & Xu, J. Securing Distributed Machine Learning in High Dimensions. arXiv:1804.10140 [cs, stat] (2018).
[^2]:  Konečný, J. Stochastic, Distributed and Federated Optimization for Machine Learning. arXiv:1707.01155 [cs] (2017).