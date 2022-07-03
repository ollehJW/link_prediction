### Link prediction
Graph에서 두 개의 노드가 연결 될 것인지를 예측하는 Task

### Data
Node feature 정보: node_feat.txt
Train Edge 정보: train_edges.txt
예측해야할 Edge List: unlabeled_edges.txt

### Method
- "Link prediction with ML".ipynb: Machine learning 방법 (Logistic Regression, Random Forest, XGBoost)

- gnn folder: Graph Neural network 방법
GCN: gcn_type == 'gcn', gcn_type == 'sage'
DGCNN: https://muhanzhang.github.io/papers/AAAI_2018_DGCNN.pdf
환경설정: Pytorch 1.5.0+, dgl 0.6.0 +, ogb, pandas, tqdm, scipy
pip install torch==1.10.1+cu111 torchvision==0.11.2+cu111 torchaudio==0.10.1 -f https://download.pytorch.org/whl/torch_stable.html



