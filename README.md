# EFG-IDS-A-Scalable-Federated-Graph-Neural-Network-Framework
This repository hosts the implementation of EFG‑IDS, a federated learning framework designed to strengthen intrusion detection in Internet of Things (IoT) environments. By combining graph neural networks with temporal imputation, EFG‑IDS delivers scalable, privacy‑preserving, and resilient detection capabilities across heterogeneous IoT networks.

The framework addresses critical challenges in IoT security, including incomplete traffic records, non‑IID data distributions, and privacy concerns inherent in centralized approaches. Federated learning enables distributed IoT nodes to collaboratively train models without sharing raw data, while GNNs capture structural dependencies among devices and communication flows. Temporal imputation ensures robustness by reconstructing missing or corrupted data streams, maintaining detection accuracy under real‑world conditions.

Key Features
Federated learning with FedProx aggregation for scalable collaboration.

GraphSAGE and TGAT layers for relational and temporal modeling.

Differential privacy mechanisms to safeguard client data.

Modular components for preprocessing, training, evaluation, and benchmarking.

Support for benchmark datasets such as CIC‑IoT‑2023 and BoT‑IoT.
