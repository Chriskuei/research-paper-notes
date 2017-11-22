## [Skip-Thought Vectors](https://arxiv.org/abs/1506.06726)

The paper describes an approach for unsupervised learning of a generic, distributed sentence encoder. The authors next introduce a simple vocabulary expansion method to encode words that were not seen as part of training.

#### Key Points

- **skip-thought vectors**: An encoder maps words to a sentence vector and a decoder is used to generate the surrounding sentences. (one encoder(GRU-RNN), two decoder(GRU-RNN)).
- **Vocabulary expansion**: solve an un-regularized L2 linear regression loss for the matrix W, allowing them to expand vocabulary to a million words.

#### Notes/Questions

- The model can be improved by many aspects: 
   - Deep encoders and decoders
   - Larger context windows (current is 2)
   - Encoding and decoding paragraphs
   - Other encoders, such as convnets
- The paper is about sentence level embeding.