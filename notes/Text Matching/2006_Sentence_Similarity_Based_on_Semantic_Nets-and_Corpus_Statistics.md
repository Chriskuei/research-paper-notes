## [Sentence Similarity Based on Semantic Nets and Corpus Statistics](https://dl.acm.org/citation.cfm?id=1159278)

This paper focuses directly on computing the similarity between very short texts of sentence length. It presents an algorithm that takes account of semantic information and word order information implied in the sentences. The semantic similarity of two sentences is calculated using information from a structured lexical database and from corpus statistics.

#### Related Work

- word co-occurence methods
  - Bag-of-words, similarity between the query vector and the document vector
  - Drawbacks
    - sentence representation is not very efficient
    - exclude function words such as *the, of, an* etc
    - sentences with similar meaning do not necessarily share many words
- corpus-based methods
  - Latent semantic analysis (LSA), Hyperspace Analogues to Language (HAL)
- descriptive features-based methods
  - represent a sentence using a set of predefined features
  - Difficulties: definition of effective features and automatically obataining values for features from a sentence

Work well for long texts because long texts have adequate information

#### Key Points

- Semantic similarity between words

  - semantic knowledge bases (WordNet, Spatial Date Transfer Standard and Gene Ontology)

  - similarity $$s(w_1, w_2)$$ between words $w_1$ and $w_2$ is a function of pathlength and depth as follows:
    $$
    s(w_1, w_2)=f_1(l)\cdot f_2(h)
    $$

  - Contributing factors

    - Path length
    - Scaling depth effect
    - a joint word set

- Word order similarity between sentences

  - measure how similar the word order in two sentences is

- Overall Sentence Similarity

  - combination of semantic similarity and word order similarity
  - syntax plays a subordinate role for semantic processing of text
#### Notes / Questions

- Similarity ranges [0, 1]
- lack of benchmark dataset

