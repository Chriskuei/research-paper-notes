## [Open Domain Question Answering via Semantic Enrichment](https://www.microsoft.com/en-us/research/publication/open-domain-question-answering-via-semantic-enrichment/)

The paper developed a new QA system that mines answers directly from the Web, and meanwhile employs KBs as a significant auxiliary to further boost the QA performance.

#### Key Points

- **New QA Framework**: The authors maked the first attempt to incorporate entity linking in QA systems to ground answer candidates on entities in knowledge bases. Then they developed semantic features for each answer candidate based on their rich semantics in KBs, including entity description texts and types, when evaluating their possibility as true answers.
- **Answer Type Checking Models**: They developed two novel probabilistic models to directly evaluate the appropriateness of an answer candidate's  type (available in KBs) given a question. One is *WAT* (WORD TO ANSWER TYPE MODEL) model, and the other is *JQA* (JOINT <QUESTION, ANSWER TYPE> ASSOCIATION)
- **Extensive Experimental Evaluation**: They built a new testing question set, composed of free-form questions extracted from search engine query logs.

#### Notes / Questions

- Seem that the system is limited to answer simple question (e.g. one-word-answer question) ?

