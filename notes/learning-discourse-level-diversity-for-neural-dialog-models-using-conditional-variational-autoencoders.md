## [Learning Discourse-level Diversity for Neural Dialog Models using Conditional Variational Autoencoders](https://arxiv.org/abs/1703.10960)

End-to-end dialog models based on encoder-decoder models have shown great promises for modeling open-domain conversations, due to its flexibility and scalability. However, dul response problem. Current solutions include: 1) Add more info to the dialog context; 2) Improve decoding algorithm, e.g. beam search.

#### Key Points

- Response generation in conversation is a **ONE-TO-MANY** mapping problem at the discourse level.
- A similar dialog context can have many different yet valid responses.
- Learn a **probabilistic distribution** over the valid responses instead of only keep the most likely one.
- **CVAE**: an E2E dialog model adapted from Conditional Variational Autoencoder.
- Enable integration of **expert knowledge** via knowledge-guided CVAE.
- Improve the training method of optimizing CVAE/VAE for text generation.