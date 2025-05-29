# IMDB sentiment analysis using LSTM and Transformer

The goal of this project was to perform binary sentiment classification (positive or negative) on IMDB movie reviews.
- LSTM: a sequential deep learning model using word embeddings and recurrent connections;
- Transformer encoder: utilizes self-attention mechanisms for better context modelling.

Approach:
- Tokenized data using BertTokenizer for both models;
- Built a PyTorch dataset and dataloader;
- Trained both models over several epochs;
- Plotted training/validation loss and accuracy;
- Compared final test accuracy.

Results:
- LSTM best test accuracy: 89.01%;
- Transformer best test accuracy: 83.14%.
