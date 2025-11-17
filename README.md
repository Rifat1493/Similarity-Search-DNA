# Similarity-Search-DNA

Word2Vec-based similarity search on DNA sequences. The notebook trains variable-length k-mer embeddings (k ∈ {3..8}) from non-overlapping ~2kb fragments, then evaluates cosine similarity vs. alignment scores and analyzes their correlation.

## Data

Download the FASTA data from [Google Drive](https://drive.google.com/file/d/1hckhB5I2lCozXiYe_GncbR5tur9kcAvg/view?usp=sharing) and place it under `data/`:




## Environment

- Python 3.9+ recommended
- Install dependencies:

```
pip install --upgrade pip
pip install gensim biopython numpy scipy matplotlib plotly
```

