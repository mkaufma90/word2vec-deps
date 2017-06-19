## Intro
Word2vec-Dependencies is an attempt to implement [Dependency-Based Word Embeddings](https://levyomer.files.wordpress.com/2014/04/dependency-based-word-embeddings-acl-2014.pdf) using Keras/NumPy. This paper describes the skip-gram model of word2vec, but using dependency parses as context, instead of words.

This is for my own edification, and not production grade. 

If you look at the bottom of the notebook, at [49], you can see that, despite the small amount of training data, the algorithim is already learning to cluster similar dependency types (e.g., `nsubj`, `dobj`) together. In some cases, such as `nummod_foot`, it is clustering them together based on dependency conext and the target arguments. 


