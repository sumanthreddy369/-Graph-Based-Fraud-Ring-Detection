# -Graph-Based-Fraud-Ring-Detection
Graph-based fraud detection system modeling financial transaction networks using network feature engineering and machine learning classification. Designed to identify coordinated fraud rings and high-risk connected entities with scalable analytics workflows aligned to financial risk monitoring use cases.

## Project Description
This project implements a graph analytics framework to identify coordinated fraud rings in financial transaction networks. The solution models relationships between entities as graph structures and applies network feature engineering and machine learning classification to detect high-risk connected components.

## Business Objective
Financial fraud often occurs through organized networks of accounts or entities. This project aims to develop graph-driven risk intelligence models that support fraud investigation teams in detecting suspicious clusters and preventing large-scale financial losses.

## Dataset
- Elliptic Bitcoin Transaction dataset  
- Nodes represent transaction entities or wallets  
- Edges represent transactional relationships  

## Tech Stack
- Python  
- Graph Analytics: NetworkX  
- Machine Learning: Gradient Boosting Classifier  
- Cloud: Amazon Neptune, Amazon S3, Amazon SageMaker  

## Project Workflow
1. Graph construction from transactional relationship data  
2. Network feature engineering (degree, clustering coefficient)  
3. Machine learning model training for fraud node classification  
4. Performance evaluation using Precision-Recall AUC metric  
5. Graph visualization for fraud cluster interpretation  

## Results
- PR-AUC Score: 0.66  
- Successfully identifies suspicious fraud clusters and network anomalies  

## Future Improvements
- Graph neural network experimentation  
- Real-time fraud network monitoring pipelines  
- Integration with streaming transaction data  
