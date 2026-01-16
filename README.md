Graph Neural Networks in Recommender Systems

An Overview and Comparative Analysis

Overview

This repository accompanies the thesis Graph Neural Networks in Recommender Systems: An Overview and Comparative Analysis, which investigates how Graph Neural Networks (GNNs) enhance modern recommender systems by addressing key limitations of traditional approaches, such as data sparsity, cold-start problems, and scalability.

The work provides:

A structured introduction to recommender systems and Graph Neural Networks

An analysis of how GNNs improve recommendation quality

A comparative study of state-of-the-art GNN-based recommender models

Discussion of business impact, research challenges, and future directions

Motivation

Traditional recommender systems (e.g., matrix factorization, collaborative filtering) struggle to model complex user–item relationships and higher-order interactions.
GNNs naturally represent recommendation data as graphs, enabling:

Rich relational modeling

High-order connectivity reasoning

Better generalization in sparse or cold-start scenarios

This thesis explores how these properties translate into measurable performance improvements and practical business value.

Core Topics Covered
Recommender Systems

Collaborative Filtering

Content-Based Filtering

Knowledge-Based & Knowledge-Graph Systems

Hybrid & Context-Aware Recommenders

Business value: engagement, CTR, retention, revenue

Graph Neural Networks

Graph representation (nodes, edges, features)

Message passing & neighborhood aggregation

Graph Convolutional Networks (GCN)

Graph Attention Networks (GAT)

GraphSAGE & heterogeneous GNNs

Scalability and graph isomorphism invariance

GNNs for Recommendation Systems

GNN-based recommender systems model users, items, and auxiliary information as graph structures, allowing:

Learning from direct and indirect (high-order) interactions

Improved handling of sparse data

Context-aware and personalized recommendations

Better cold-start performance

Models Analyzed
1. ConsisRec

Use case: Social recommendation
Key idea: Consistent neighbor aggregation using relation attention and query-aware sampling
Datasets: Ciao, Epinions
Metrics: RMSE, MAE
Result: Outperforms classical and GNN-based baselines by reducing social inconsistency

2. DMGCF (Dynamic Multi-Graph Collaborative Filtering)

Use case: Dynamic collaborative filtering
Key idea:

Multiple dynamically evolving graphs

Dual-path GNN architecture for low- and high-order features

Datasets:
ML-100K, ML-1M, Yelp, YahooMusic, Flixster

Metrics: RMSE, MAE
Result:
Consistently outperforms NGCF and deep learning baselines, especially on sparse datasets

3. KGNN-LS (Knowledge-Aware GNN with Label Smoothness)

Use case: Knowledge-graph-enhanced recommendation
Key idea:

User-specific relation scoring

Label smoothness regularization for edge learning

Datasets:
MovieLens-20M, Book-Crossing, Last.FM, Dianping-Food

Metrics: Recall@K, AUC
Result:
Strong improvements in top-K recommendation and CTR prediction, particularly in cold-start scenarios

Key Findings

GNN-based recommenders consistently outperform traditional models

High-order connectivity is crucial for recommendation quality

Knowledge graphs significantly improve performance when integrated with GNNs

Model performance is sensitive to hyperparameters and graph construction choices

Challenges & Open Problems

Interpretability of GNN-based recommendations

Scalability on very large or dynamic graphs

Robustness to adversarial graph perturbations

Transfer learning across different graph domains

Efficient training of large-scale GNNs

Future Research Directions

Explainable GNN-based recommender systems

Dynamic and temporal graph modeling

Multi-modal recommendation (text, images, knowledge graphs)

Integration with reinforcement learning

More efficient and scalable GNN training algorithms

Author

Nikolaos Kakonas
Athens University of Economics and Business
