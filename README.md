# Clustering word embeddings

Word embeddings are vector representations of words that are designed to capture some aspect of semantics, such that words that are more similar are closer together in vector space.  One famous example of word embeddings is the [Word2Vec GloVe vectors](https://nlp.stanford.edu/projects/glove/), which was an early deep learning success.

For this assignment, I'd like to you do use the different clustering techniques and dimensionality reduction methods we've covered to explore three different newsgroups from the [20 Newgroups data](http://qwone.com/~jason/20Newsgroups/) in Scikit learn.  Please process the three newgroups that have to do with religion. I'd like you to:



Your goal is to obtain the "best" clustering you can. Use different dimensionality reduction methods (e.g., PCA, tSNE, UMAP, etc.) to project the data, and then different clustering methods (k-Means, HAC, HDBScan, etc.).  Try at least 2 dimensionality reduction methods and 2 clustering methods. You can define best however you want - this could be subjective (explain your criterion) or data driven (explain your choice).

1) What happens if you project the data before you cluster?  What happens if you don't?  Explain which you prefer and why.

2) What are the major clustering in the different newsgroups?  Please summarize them for each of the three newgroups.

3) How do the three newsgroups differ?  How are they the same?  

Note that even though we are using stopwords and TF-IDF to filter the term list, a number of terms sneak in that aren't really relevant (com, edu, etc).  Feel free to remove the high frequency terms that you don't think contribute to your understanding of the data.

Please submit everything in a Jupyter notebook.  There is no need to write a separate markdown file, but be sure to include text in your Jupyter notebook that answers each of the above questions, along with visualizations.  The text in your notebook should be nicely formatted, and free from grammatical and spelling errors.

**Rubric**

1.  Did you explore and identify an effective approach for clustering / dimensionality reduction (20 points).
2.  Did you explore and respond to the 3 questions above (20 points).
3.  Is your Jupyter notebook well formatted and free from errors?  Does it include well written answers, free of grammatical and spelling errors?
