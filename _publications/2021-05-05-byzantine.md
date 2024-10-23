---
title: "Byzantine-Robust and Privacy-Preserving Framework for FedML"
collection: publications
permalink: /publications/2021-05-05-byzantine
excerpt:
date: 2021-05-05
venue: 'Security and Safety in Machine Learning Systems ICLR 2021 Workshop'
paperurl: 'https://arxiv.org/pdf/2105.02295'
citation: 'Hanieh Hashemi, Yongqin Wang, and Murali Annavaram. 2021. Byzantine-Robust and Privacy-Preserving Framework for FedML.'
---
Federated learning has emerged as a popular paradigm for collaboratively training a model from data distributed among a set of clients. This learning setting presents, among others, two unique challenges: how to protect privacy of the clients’ data during training, and how to ensure integrity of the trained model. We propose a two-pronged solution that aims to address both challenges under a single framework. First, we propose to create secure enclaves using a trusted execution environment (TEE) within the server. Each client can then encrypt their gradients and send them to verifiable enclaves. The gradients are decrypted within the enclave without the fear of privacy breaches. However, robustness check computations in a TEE are computationally prohibitive. Hence, in the second step, we perform a novel gradient encoding that enables TEEs to encode the gradients and then offloading Byzantine check computations to accelerators such as GPUs. Our proposed approach provides theoretical bounds on information leakage and offers a significant speed-up over the baseline in empirical evaluation.