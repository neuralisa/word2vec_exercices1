These questions are not graded but we will discuss them!

### Easy 
- **Why are there two versions of word2vec: Skip-gram and Continuous Bag of Words?** This is a theoretical question that requires understanding the conceptual differences between the two models.
- **Why do we use softmax() for normalization and not just min-max scaling?** This question asks for a theoretical explanation of softmax function usage in machine learning models.

### Medium
- **Write down a derivative of the objective function of the Skip gram model with respect to the model parameters only for a single pair of the center and context words.** Requires mathematical knowledge to derive equations.
- **Will the word embedding change significantly if you add a negation ("not", "no", ...) to the context?** This involves some coding and analysis using NLP tools to demonstrate the effect.
- **Does word2vec take into account word order and the relative word positions?** Theoretical question with a bit of analysis and opinion.
- **Why are there two matrices that contain word embeddings for all words, W and W_prime?** Requires understanding of the Word2Vec architecture.

### Hard
- **Can you do the derivative for the complete objective?** More complex mathematical derivation involving summing across all pairs.
- **Find the bottleneck: Can you tell which line in the demo implementation has the highest time complexity?** Requires code analysis and understanding of algorithmic complexity.
- **Proof that the outer product in the line `dW_prime = np.outer(h, EI)` is justified and is actually a partial gradient of the error function.** Requires a deep understanding of calculus and linear algebra applied to machine learning.
- **Proof that `dW = np.dot(EI, W_prime.T)` is justified and is actually a partial gradient of the error function.** Similar to the above, involves mathematical proof and understanding of neural network training.

### Bonus question
- **Using the vectors from the gensim package, find three words (w1, w2, w3) where w1 and w2 are synonyms and w1 and w3 are antonyms, but cosine distance (w1, w3) < cosine distance (w1, w2).** This is a research-oriented task, requiring extensive experimentation and analysis to find suitable examples and then explaining the counter-intuitive result.

These are estimated times and difficulties, which can vary depending on the individual's background and experience in mathematics, machine learning, and programming.
