# Information-Retrieval

### Information Retrieval 1

Used Pandas and PyTerrier and performed Information Retrieval tasks on Vaswani dataset -

1. Indexing a collection
2. accessing an index
3. BatchRetrieve transformer for searching an index
4. reformulating queries
5. creating retrieval pipelines.


### Information Retrieval 2

Examined "50pct" and the "trec-wt-2004" datasets and performed -

1. Retrieval & Evaluation by calculating MAP performance of each type of retrieval(TFIDF, BM25 and PL2), drawing interpolated recall precision graphs.
2. Performed Query expansion to improve the search engine and evaluated using query delta bar-chart.
3. Implemeted a word2vec-based query expansion model using Genism and built a custom transformer by handling out-of-vocabulary (OOV) words, eliminating similar terms, more emphasis to the original query terms and, considering special characters.

### Information Retrieval 3

Examined "50pct" and the "trec-wt-2004" datasets and performed -

1. USed BatchRetrieve as baseline and PL2 as weighting model.
2. deployed two new features (url and body) for each document retrieved.
3. A 5 feature Learning to Rank Model
