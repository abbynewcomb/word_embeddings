# word_embeddings

This repository contains code and data associated with [Word Embeddings to Evaluate Bias in News Sources]()

Developers: Abby Newcomb, Elise Schatzki-McClain, Sean Souksavath

Inspired by [Word embeddings quantify 100 years of gender and ethnic stereotypes](https://www.pnas.org/content/115/16/E3635) by Garg, N., Schiebinger, L., Jurafsky, D. & Zou, J.

To produce models and plots:
1. Download the [all-the-news](https://components.one/datasets/all-the-news-2-news-articles-dataset/) dataset
2. Subset the desired news publication text corpuses using subsetting.ipynb
3. Pre-process the data and generate separate word embedding models in model_prep.ipynb
4. Utilize methods in analysis_and_graphs.ipynb to find associations and create plots

This project uses Google's [word2vec](https://code.google.com/archive/p/word2vec/) model architecture.
