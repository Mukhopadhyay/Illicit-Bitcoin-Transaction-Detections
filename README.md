# Illicit-Bitcoin-Transaction-Detections
Training a Graph Neural Network to detect illicit bitcoin transactions

#### About Dataset

I am using the [Elliptic Data Set](https://www.kaggle.com/datasets/ellipticco/elliptic-data-set) for this project. 
This data set is a transaction graph collected from the Bitcoin blockchain. 
- The nodes in the graph represents a trasaction (203,769 nodes).
- The edges determine the flow of transactions (234,355 edges).
- Every node has 166 features associated with it.
- Every node is labelled into "licit", "illicit" or "unknown".
- 2% are labelled as "ilicit", 21% are labelled as "licit", rest as "unknown".

##### Reference:
- M. Weber, G. Domeniconi, J. Chen, D. K. I. Weidele, C. Bellei, T. Robinson, C. E. Leiserson, "Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics", KDD ’19 Workshop on Anomaly Detection in Finance, August 2019, Anchorage, AK, USA.
