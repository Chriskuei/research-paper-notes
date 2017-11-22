## [Incomplete Follow-up Question Resolution using Retrieval based Sequence to Sequence Learning](http://dl.acm.org/citation.cfm?id=3080801)

The paper presented a *retrieval* based seq2seq learning system that can generate the complete (or intended) question for an incomplete follow-up question. As there is paucity of labeled conversation data, the authors decompose the original problem into two simpler and independent problems.

#### Key Points

- The first problem focuses on selecting candidate question templates using syntactic and linguistic patterns seen in the data
- The second problem focuses on re-ranking candidate questions using a neural language model which can be trained independently on millions of unlabelled questions
- The system can be added as a plug-in module to an existing IPA or IQA system.

#### Notes / Questions