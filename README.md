# Deep Learning Projects — PyTorch

A collection of deep learning projects implemented in PyTorch,
covering a range of core topics from supervised learning to 
self-supervised representation learning and sequence modeling.

---

## Projects

### 01 — MLP Image Classification on MNIST
- Built a Multi-Layer Perceptron (MLP) from scratch in PyTorch
- Trained and evaluated on the MNIST handwritten digit dataset
- Explored effect of hidden layer size on accuracy
- **Skills:** PyTorch, MLP, Classification, MNIST

### 02 — Convolutional Autoencoder on MNIST
- Implemented a Convolutional Autoencoder (CAE) for unsupervised 
  image representation learning
- Used learned representations to train a downstream classifier
- Compared linear probing vs full fine-tuning
- **Skills:** PyTorch, CNN, Autoencoder, Transfer Learning, MNIST

### 03 — SimCLR Self-Supervised Representation Learning on STL-10
- Implemented SimCLR contrastive learning framework from scratch
- Pretrained encoder on unlabeled STL-10 images using NT-Xent loss
- Fine-tuned with linear classifier; compared against supervised baseline
- Visualized learned representations using t-SNE
- **Skills:** PyTorch, SimCLR, Contrastive Learning, ResNet, t-SNE, STL-10

### 04 — LSTM Time Series Forecasting
- Built LSTM-based models for temperature time series forecasting
- Implemented many-to-one and many-to-many sequence prediction
- Compared RNN architectures on daily temperature data
- **Skills:** PyTorch, LSTM, RNN, Time Series, Sequence Modeling

### 05 — Character-Level RNN: Text Generation & Classification
- Implemented character-level LSTM with embedding layer for joke generation
- Built news article generator using one-hot encoding on AG News dataset
- Trained character-level RNN classifier for 4-class news categorization
- **Skills:** PyTorch, LSTM, NLP, Text Generation, Embedding, AG News

---

## Tech Stack
- Python 3.10+
- PyTorch
- HuggingFace Datasets
- Scikit-learn
- Matplotlib
- Google Colab (T4 GPU)
