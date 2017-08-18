## [A Neural Conversational Model](http://arxiv.org/abs/1506.05869)

The authors train a seq2seq model on conversations, building a chat bot. The first data set is an IT Helpdesk dataset with 33M tokens. The trained model can help solve simple IT problems. The second data set is the OpenSubtitles data with ~1.3B tokens (62M sentences). The resulting model learns simple world knowledge, can generalize to new questions, but lacks a coherent personality.

#### Key Points

- IT Helpdesk: 1-layer LSTM, 1024-dimensional cells, 20k vocabulary. Perplexity of 8.
- OpenSubtitles: 2-layer LSTM, 4096-dimensional cells, 100k vocabulary, 2048 affine layer. Attention did not help.
- OpenSubtitles: Treat two consecutive sentences as coming from different speakers. Noisy dataset.
- Model lacks personality, gives different answers to similar questions (What do you do? What's your job?)
- Feed previous context (whole conversation) into encoder, for IT data only.
- In both data sets, the neural models achieve better perplexity than n-gram models.

#### Notes / Questions
