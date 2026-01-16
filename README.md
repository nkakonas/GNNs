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

## 📖 References

[1] Chong Chen, Weizhi Ma, Min Zhang, Zhaowei Wang,  
Xiuqiang He, Chenyang Wang, Yiqun Liu, and Shaoping Ma,  
“Graph heterogeneous multi-relational recommendation,”  
*Proceedings of the AAAI Conference on Artificial Intelligence*, 2021.

[2] Mehrdad Mollanoroozi,  
“Review on recommender system and architecture,”  
*Majlesi Journal of Telecommunication Devices*, vol. 11, pp. 177–185, 2022.

[3] Gediminas Adomavicius and Alexander Tuzhilin,  
“Toward the next generation of recommender systems: A survey of the state-of-the-art and possible extensions,”  
*IEEE Transactions on Knowledge and Data Engineering*, 2005.

[4] Charu C. Aggarwal,  
*Recommender Systems*, 2016.

[5] Arjan Jeckmans, Michael Beye, Zekeriya Erkin, Pieter Hartel, Reginald Lagendijk, and Qiang Tang,  
“Privacy in recommender systems,”  
*Social Media Retrieval*, 2013.

[6] Robin Burke,  
“Knowledge-based recommender systems,”  
*Encyclopedia of Library and Information Systems*, 69(Supplement 32), 2000.

[7] Dietmar Jannach,  
*Recommender Systems: An Introduction*, 2010.

[8] Xavier Amatriain and Justin Basilico,  
“Netflix recommendations: Beyond the 5 stars (part 1),” 2012.

[9] Davidson James, Liebald Benjamin, Liu Junning, Nandy Palash, and Vleet Taylor Van,  
“The YouTube video recommendation system,”  
*Proceedings of the Fourth ACM Conference on Recommender Systems*, p. 386, 2010.

[10] Carlos A. Gomez-Uribe and Neil Hunt,  
“The Netflix recommender system: Algorithms, business value, and innovation,”  
*ACM Transactions on Management Information Systems*, vol. 6, 2015.

[11] Jayasimha Katukuri, Tolga Kӧnik, Rajyashree Mukherjee, and Santanu Kolay,  
“Recommending similar items in large-scale online marketplaces,”  
*IEEE International Conference on Big Data*, 2014.

[12] Jayasimha Katukur, Tolga Konik, Rajyashree Mukherjee, and Santanu Kolay,  
“Post-purchase recommendations in large-scale online marketplaces,”  
*IEEE International Conference on Big Data*, 2015.

[13] Dietmar Jannach and Michael Jugovac,  
“Measuring the business value of recommender systems,”  
*ACM Transactions on Management Information Systems*, vol. 10, 2019.

[14] Xuan Nhat Lam, Ho Chi Minh, Thuc Vu, Trong Duc Le, and Anh Duc Duong,  
“Addressing cold-start problem in recommendation systems,”  
*Proceedings of the 2nd International Conference on Ubiquitous Information Management and Communication*, 2008.

[15] Siavash Ghodsi Moghaddam and Ali Selamat,  
“A scalable collaborative recommender algorithm based on user density-based clustering,”  
*International Conference on Data Mining and Intelligent Information Technology Applications*, 2011.

[16] Himan Abdollahpouri, Masoud Mansoury, Robin Burke, Bamshad Mobasher, and Edward Malthouse,  
“User-centered evaluation of popularity bias in recommender systems,”  
*UMAP 2021*, pp. 119–129, 2021.

[17] Atika Gupta, Priya Matta, and Bhasker Pant,  
“Graph neural network: Current state of art, challenges and applications,”  
Elsevier, vol. 46, pp. 10927–10932, 2021.

[18] Thomas N. Kipf and Max Welling,  
“Semi-supervised classification with graph convolutional networks,”  
*arXiv preprint*, 2016.

[19] Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, and Philip S. Yu,  
“A comprehensive survey on graph neural networks,”  
*IEEE Transactions on Neural Networks and Learning Systems*, vol. 32, pp. 4–24, 2021.

[20] Peter W. Battaglia et al.,  
“Relational inductive biases, deep learning, and graph networks,”  
*arXiv preprint*, 2018.

[21] Jie Zhou et al.,  
“Graph neural networks: A review of methods and applications,”  
*AI Open*, vol. 1, pp. 57–81, 2020.

[22] Yann LeCun, Yoshua Bengio, and Geoffrey Hinton,  
“Deep learning,”  
*Nature*, vol. 521, pp. 436–444, 2015.

[23] Michael M. Bronstein et al.,  
“Geometric deep learning: Going beyond euclidean data,”  
*IEEE Signal Processing Magazine*, vol. 34, pp. 18–42, 2017.

[24] Franco Scarselli et al.,  
“The graph neural network model,”  
*IEEE Transactions on Neural Networks*, vol. 20, pp. 61–80, 2009.

[25] Keyulu Xu, Weihua Hu, Jure Leskovec, and Stefanie Jegelka,  
“How powerful are graph neural networks?”  
*arXiv preprint*, 2018.

[26] William L. Hamilton, Rex Ying, and Jure Leskovec,  
“Inductive representation learning on large graphs,”  
*NeurIPS*, 2017.

[27] Ziniu Hu et al.,  
“Heterogeneous graph transformer,”  
ACM, 2020.

[28] Si Zhang et al.,  
“Graph convolutional networks: A comprehensive review,”  
*Computational Social Networks*, vol. 6, 2019.

[29] Wenqi Fan et al.,  
“Graph neural networks for social recommendation,”  
*WWW 2019*, pp. 417–426.

[30] Justin Gilmer et al.,  
“Neural message passing for quantum chemistry,”  
*ICML*, 2017.

[31] Hoang N. T. and Takanori Maehara,  
“Revisiting graph neural networks: All we have is low-pass filters,”  
*arXiv preprint*, 2019.

[32] Haggai Maron et al.,  
“Provably powerful graph networks,”  
*NeurIPS*, 2019.

[33] Christopher Morris et al.,  
“Weisfeiler and Leman go neural,”  
*AAAI*, 2019.

[34] Jie Chen, Tengfei Ma, and Cao Xiao,  
“FastGCN,”  
*arXiv preprint*, 2018.

[35] Rex Ying et al.,  
“Graph convolutional neural networks for web-scale recommender systems,”  
*KDD*, 2018.

[36] Saining Xie et al.,  
“Aggregated residual transformations for deep neural networks,”  
*CVPR*, 2017.

[37] Daniel Zügner et al.,  
“Adversarial attacks on graph neural networks,”  
*ACM TKDD*, vol. 14, 2020.

[38] Qi Liu et al.,  
“Constrained graph variational autoencoders for molecule design,”  
*NeurIPS*, 2018.

[39] Weihua Hu et al.,  
“Strategies for pre-training graph neural networks,”  
*arXiv preprint*, 2019.

[40] Chen Gao et al.,  
“A survey of graph neural networks for recommender systems,”  
*ACM Transactions on Recommender Systems*, vol. 1, 2023.

[41] Xiang Wang et al.,  
“Neural graph collaborative filtering,”  
ACM, 2019.

[42] Rianne van den Berg, Thomas N. Kipf, and Max Welling,  
“Graph convolutional matrix completion,”  
*arXiv preprint*, 2017.

[43] Federico Monti et al.,  
“Geometric deep learning on graphs and manifolds,”  
*CVPR*, 2017.

[44] Shu Wu et al.,  
“Session-based recommendation with graph neural networks,”  
*AAAI*, 2019.

[45] Petar Veličković et al.,  
“Graph attention networks,”  
*arXiv preprint*, 2017.

[46] Hao Yuan et al.,  
“Explainability in graph neural networks,”  
*IEEE TPAMI*, 2022.

[47] Xiaohan Li et al.,  
“Dynamic graph collaborative filtering,”  
IEEE, 2020.

[48] Jiechuan Jiang et al.,  
“Graph convolutional reinforcement learning,”  
*arXiv preprint*, 2018.

[49] Liangwei Yang et al.,  
“ConsisRec: Enhancing GNN for social recommendation via consistent neighbor aggregation,”  
ACM, 2021.

[50] Hao Tang, Guoshuai Zhao, Xuxiao Bu, and Xueming Qian,  
“Dynamic evolution of multi-graph based collaborative filtering for recommendation systems,”  
*Knowledge-Based Systems*, vol. 228, 2021.

