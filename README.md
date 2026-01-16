# Graph Neural Networks in Recommender Systems
## An Overview and Comparative Analysis

## 📌 Overview
This repository contains the work related to the thesis **“Graph Neural Networks in Recommender Systems: An Overview and Comparative Analysis”**.  
The thesis explores how **Graph Neural Networks (GNNs)** can enhance recommender systems by addressing key limitations of traditional approaches such as data sparsity, cold-start problems, and scalability issues.

---

## 🎯 Motivation
Traditional recommender systems struggle to model complex user–item relationships and higher-order interactions.  
By representing recommendation data as graphs, GNNs enable:
- Rich relational modeling
- High-order connectivity reasoning
- Improved performance in sparse and cold-start scenarios

---

## 📚 Topics Covered

### Recommender Systems
- Collaborative Filtering  
- Content-Based Filtering  
- Knowledge-Based Recommender Systems  
- Hybrid & Context-Aware Systems  
- Business value of recommender systems  

### Graph Neural Networks
- Graph representation (nodes, edges, features)
- Message passing and neighborhood aggregation
- Graph Convolutional Networks (GCN)
- Graph Attention Networks (GAT)
- GraphSAGE and heterogeneous GNNs
- Scalability and graph isomorphism invariance

---

## 🔗 GNN-based Recommender Systems
GNN-based recommender systems model users, items, and their interactions as graph structures, allowing:
- Learning from both direct and indirect interactions
- Better handling of sparse data
- More personalized and context-aware recommendations
- Improved cold-start performance

---

## 🧪 Models Analyzed

### ConsisRec
- Focus: Social recommendation
- Key idea: Consistent neighbor aggregation
- Evaluation metrics: RMSE, MAE
- Datasets: Ciao, Epinions

### DMGCF (Dynamic Multi-Graph Collaborative Filtering)
- Focus: Dynamic and multi-graph collaborative filtering
- Key idea: Dynamic graph evolution with dual-path GNNs
- Evaluation metrics: RMSE, MAE
- Datasets: ML-100K, ML-1M, Yelp, YahooMusic, Flixster

### KGNN-LS (Knowledge-Aware GNN with Label Smoothness)
- Focus: Knowledge-graph-based recommendation
- Key idea: Label smoothness regularization over knowledge graphs
- Evaluation metrics: Recall@K, AUC
- Datasets: MovieLens-20M, Book-Crossing, Last.FM, Dianping-Food

---

## 📊 Key Findings
- GNN-based models consistently outperform traditional recommender systems
- High-order connectivity significantly improves recommendation quality
- Knowledge graphs further enhance performance, especially in cold-start cases
- Model performance is sensitive to graph construction and hyperparameters

---

## ⚠️ Challenges & Limitations
- Limited interpretability of GNN-based models
- Scalability on very large and dynamic graphs
- Sensitivity to hyperparameter tuning
- High computational cost

---

## 🔮 Future Work
- Explainable GNN-based recommender systems
- Dynamic and temporal graph modeling
- Multi-modal recommendation (text, images, knowledge graphs)
- More scalable GNN training methods

---

## 👤 Author
**Nikolaos Kakonas**  
Athens University of Economics and Business

---

## 📖 Reference
If you use or cite this work, please refer to:

Nikolaos Kakonas, *Graph Neural Networks in Recommender Systems: An Overview and Comparative Analysis*, Athens University of Economics and Business.
