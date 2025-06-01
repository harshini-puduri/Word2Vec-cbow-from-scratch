# CBOW from Scratch (w/ NumPy)

Wanted to understand how word embeddings actually work, so I built a mini version of the CBOW model from scratch using just NumPy.

The model trains on a few lines from MLK's "I Have a Dream" speech and learns to predict a word based on its context. No PyTorch, no TensorFlow — just raw matrix math.

### What it does:
- Tokenizes a tiny corpus
- Builds (context, target) pairs
- Runs forward + backward pass manually
- Learns a word embedding matrix (`W1`)

### Output:
After training, it prints a 10-dim embedding for every word in the vocab as a pandas DataFrame.

---

Run with Python 3.  
You only need NumPy and pandas.

