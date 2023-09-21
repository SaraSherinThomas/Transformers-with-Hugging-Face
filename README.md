# Transformers 
Transformers are novel neural network architecture for sequence modelling. This architecture outperforms the RNN on machine translation tasks. The transformes are mainly composed of 2 block: Encoder and Decoder

## Encoder:
Converts input sequence of tokens into a sequence of embeddings that is well suited for tasks like classification, NER etc.
BERT and its variants belong to this class of architecture.


Encoder contains the following sublayers:
- multihead self attention layer
- fully connected FF layer
