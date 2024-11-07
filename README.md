# Graph Neural Networks on Cora Dataset

## Project Overview

This project implements and evaluates three Graph Neural Network (GNN) architectures: **Graph Convolutional Network (GCN)**, **GraphSAGE**, and **Graph Attention Network (GAT)** for node classification on the **Cora dataset**. The objective is to classify scientific publications based on citation relationships.

## Dataset

- **Cora Dataset**:
  - **Nodes**: 2708 (scientific publications)
  - **Edges**: 5429 (citation links)
  - **Features**: 1433 binary attributes (word presence)
  - **Classes**: 7 categories

## GNN Architectures

1. **GCN**: Utilizes graph convolutional layers for feature extraction.
2. **GraphSAGE**: Employs sampling and aggregation for inductive learning.
3. **GAT**: Incorporates attention mechanisms to weigh node contributions.

## Key Results

| Model      | Accuracy | Precision | Recall | F1 Score |
|------------|----------|-----------|--------|----------|
| GCN        | 0.7950   | 0.7714    | 0.8072 | 0.7862   |
| GraphSAGE  | 0.8040   | 0.7841    | 0.8223 | 0.7996   |
| GAT        | 0.7960   | 0.7714    | 0.8154 | 0.7881   |


### Requirements
- Python 3.7+
- PyTorch
- PyTorch Geometric
- Other dependencies listed in `requirements.txt`

### Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/gnn-cora-comparison.git
   cd gnn-cora-comparison

2. Install Dependencies:
    pip install -r requirements.txt

3. Download the Dataset from Cora Dataset.

4. Run the Code